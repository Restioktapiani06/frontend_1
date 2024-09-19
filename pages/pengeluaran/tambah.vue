<template>
  <div class="container-fluid">
    <div class="col">
      <h1 class="text-center">TABUNGAN KELAS XII PPLG 4</h1>
    <div class="row justify-content-center mt-5">
      <div class="col-5 card shadow rounded-4 p-3" style="background-color: #D9D9D9;">
        <h1 class="text-center">FORM KELUAR</h1>
        <form class="" action="#" method="post">
          <div class="col-auto">
            <label for="nama" class="col-form-label">Nama</label>
          </div>
          <div class="col-auto">
            <select id="nama" class="form-select mb-3" aria-label="Default select example">
              <option selected>Pilih Nama Siswa</option>
              <option value="1">AGNI ANJELITA</option>
              <option value="2">NENG WAFI</option>
              <option value="3">RESTI OKTAPIANI</option>
              <option value="3">TIARA ANDRIYANI</option>
            </select> 
          </div>
          <div class="col-auto">
            <label>Jumlah</label>
          </div>
          <div class="col-auto mb-3">
            <input type="number" name="jumlah" class="form-control">
          </div>
                              
          <div class="d-grid gap-2 d-md-flex justify-content-md-end">
              <button class="btn btn-primary me-md-2" type="button">Kirim</button>
          </div>
        </form>
      </div>
    </div>
  </div>
  </div>
    
</template>

<style setup>

</style>