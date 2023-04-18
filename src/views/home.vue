<template>
    <!--banner image-->
  
    <div class="banner-image w-100 vh-100 d-flex justify-content-center align-items-center">
      <div  class="images">
        <div class="profile">
        <img src="../assets/kimau.png" class="rounded-circle"
             height="300px" width="300px">
      </div>
      <div class="content text-center">
        <h1>Muhammad Rizky Maulana</h1>
        <h3>12150114879</h3>
        <h4>Mahasiswa Teknik Informatika Angkatan 21</h4>
        <h5>Universitas Islam Negeri Sultan Syarif Kasim Riau</h5>
      </div>
      <div class="background">
      </div>
      </div>
    </div>
  
  
</template>
  
<script>
  export default {
    name: 'App',
    components: {
      // HelloWorld
    }
  }
</script>
  
<style>
.text-center{
  margin-top: 10px;
  color: #181818;

}

.images {
  margin-top: -90px;
}

.profile {
    
  padding-top: 20px;
}

#app{
  background: linear-gradient(rgba(126, 9, 9, 0.96), rgb(245, 9, 9), rgba(218, 224, 224, 0.96)),center/cover no-repeat;
}


</style>
  