<template>
  <div class="container-fluid">   
    <div class="row justify-content-center mt-5">
      <div class="col-5 card shadow rounded-4 p-3" style="background-color: #D9D9D9;">
        <h1 class="text-center">FORM TABUNGAN SISWA</h1>
        <form class="" action="#" method="post">
          <div class="col-auto">
            <label for="nama" class="col-form-label">Nama</label>
          </div>
          <div class="col-auto">
            <select id="nama" class="form-select mb-3" aria-label="Default select example">
              <option selected>Pilih Nama Siswa</option>
              <option value="1">AGNI ANJELITA</option>
              <option value="2">RESTI OKTAPIANI</option>
              <option value="3">NENG WAFI</option>
            </select> 
          </div>
          <div class="col-auto">
            <label for="Jenis Kelamin" class="col-form-label">Jenis Kelamin</label>
            <select id="Jenis Kelamin" class="form-select mb-3" aria-label="Default select example">
              <option selected>Pilih Jenis Kelamin</option>
              <option value="1">PEREMPUAN</option>
              <option value="2">LAKI-LAKI</option>
            </select> 
          </div>
        <div class="mb-3">
          <label for="exampleInputEmail1" class="form-label">No Hp</label>
          <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
        </div>
        <div class="mb-3">
          <label for="exampleInputEmail1" class="form-label">Alamat</label>
          <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
        </div>
                              
          <div class="d-grid gap-2 d-md-flex justify-content-md-end">
              <button class="btn btn-primary me-md-2" type="button">Kirim</button>
          </div>
        </form>
      </div>
    </div>
  </div>  
</template>

<style setup>

</style>