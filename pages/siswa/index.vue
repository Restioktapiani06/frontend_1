<template>
  <div class="container-fluid">
    <div class="row mb-3">
      <div class="col">
        <h1 class="text-center m-5">DATA NAMA SISWA XII PPLG 4</h1>
        <NuxtLink class="text-decoration-none" href="siswa/addSiswa"><button class="btn btn-success d-flex justify-content-start">Tambah Data</button></NuxtLink>
      </div>
    </div>
    <div class="row">
      <div class="col">
        <table class="table table-bordered">
          <thead>
            <tr>
              <th scope="col">NO</th>
              <th scope="col">Nama</th>
              <th scope="col">Jenis Kelamin</th>
              <th scope="col">NO HP</th>
              <th scope="col">Alamat</th>
              <th scope="col">Aksi</th>
            </tr>
          </thead>
          <tbody class="table-group-divider">
            <tr>
              <th scope="row">1</th>
              <th scope="row">AGNI ANJELITA</th>
              <td>PEREMPUAN</td>
              <td>085846175690</td>
              <td>KP.GOBANG</td>
              <td><i class="bi bi-pencil-square"></i> | <i class="bi bi-trash"></i></td>
            </tr>
            <tr>
              <th scope="row">2</th>
              <th scope="row">RESTI OKTAPIANI</th>
              <td>PEREMPUAN</td>
              <td>085793351316</td>
              <td>JL.BEBEDHAN 2</td>
              <td><i class="bi bi-pencil-square"></i> | <i class="bi bi-trash"></i></td>
            </tr>
            <tr>
              <th scope="row">3</th>
              <th scope="row">NENG WAFI</th>
              <td>PEREMPUAN</td>
              <td>085797557734</td>
              <td>KP.CIBODAS</td>
              <td><i class="bi bi-pencil-square"></i> | <i class="bi bi-trash"></i></td>
            </tr>
            <tr>
              <th scope="row">4</th>
              <th scope="row">TIARA ANDRIYANI</th>
              <td>PEREMPUAN</td>
              <td>081779818289</td>
              <td>KP.CIMERAK</td>
              <td><i class="bi bi-pencil-square"></i> | <i class="bi bi-trash"></i></td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </div>
</template>

<style setup>


</style>