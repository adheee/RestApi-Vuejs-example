<template>
  <div class="about">
    <h1>Test API</h1>

    <ul>
      <li v-for="provinsis in data" :key="provinsis">
        <span>{{ provinsis.nama_provinsi }}</span> &#160;
      </li>
    </ul>
  </div>
</template>

<style lang="scss">
ul {
  li {
    list-style: none;
    margin-bottom: 10px;
  }
}
</style>

<script>
import axios from "axios";

export default {
  data() {
    return {
      data: [],
    };
  },
  created() {
    this.getAllUser();
  },
  methods: {
    getAllUser() {
      axios
        .get("https://galung-app.asdar12.my.id/api/provinsi")
        .then((response) => {
          this.data = response.data.data;
          console.log(response);
        })
        .catch((err) => {
          console.log(err);
        });
    },
  },
};
</script>
