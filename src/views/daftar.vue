<template>
  <div class="daftar">
    <h1>Data Petani</h1>

    <div class="container">
      <form>
        <div class="form-group">
          <label for="exampleInputEmail1">Nama</label>
          <input
            type="text"
            class="form-control"
            id="exampleInputEmail1"
            aria-describedby="emailHelp"
            placeholder="Enter email"
          />
        </div>
        <div class="form-group">
          <label for="exampleInputPassword1">Email</label>
          <input
            type="email"
            class="form-control"
            id="exampleInputPassword1"
            placeholder="Password"
          />
        </div>
        <div class="row">
          <div class="col-md-6">
            <div class="form-group">
              <label for="exampleInputPassword1">Tempat Lahir</label>
              <input
                type="text"
                class="form-control"
                id="exampleInputPassword1"
                placeholder="Password"
              />
            </div>
          </div>
          <div class="col-md-6">
            <div class="form-group">
              <label for="exampleInputPassword1">Tanggal Lahir</label>
              <input
                type="text"
                class="form-control"
                id="exampleInputPassword1"
                placeholder="Password"
              />
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-md-6">
            <div class="form-group">
              <label for="exampleInputPassword1">Kecamatan</label>
              <input
                type="text"
                class="form-control"
                id="exampleInputPassword1"
                placeholder="Password"
              />
            </div>
          </div>
          <div class="col-md-6">
            <div class="form-group">
              <label for="exampleInputPassword1">Kelurahan</label>
              <input
                type="text"
                class="form-control"
                id="exampleInputPassword1"
                placeholder="Password"
              />
            </div>
          </div>
        </div>
        <div class="form-group">
          <label for="exampleInputPassword1">Kelurahan</label>
          <div class="form-check form-check-inline">
            <input
              class="form-check-input"
              type="radio"
              name="inlineRadioOptions"
              id="inlineRadio1"
              value="option1"
            />
            <label class="form-check-label" for="inlineRadio1"
              >Laki - Laki</label
            >
          </div>
          <div class="form-check form-check-inline">
            <input
              class="form-check-input"
              type="radio"
              name="inlineRadioOptions"
              id="inlineRadio2"
              value="option2"
            />
            <label class="form-check-label" for="inlineRadio2">Perempuan</label>
          </div>
        </div>
        <div class="form-group">
          <label for="exampleInputPassword1">No Hp</label>
          <input
            type="tel"
            class="form-control"
            id="exampleInputPassword1"
            placeholder="Password"
          />
        </div>
        <div class="form-group">
          <label for="exampleInputPassword1">Alamat Lengkap</label>
          <input
            type="text"
            class="form-control"
            id="exampleInputPassword1"
            placeholder="Password"
          />
        </div>
        <button type="submit" class="btn btn-primary">Submit</button>
      </form>
    </div>
  </div>
</template>

<style lang="scss">
form {
  text-align: left;
}
</style>