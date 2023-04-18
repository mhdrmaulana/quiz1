<template>
    <div class="main-container">
     <div class="container-one">
       <div class="profile">
         <img src="../assets/kimau.png" alt="">
         <h3>Muhammad Rizky Maulana</h3>
         <p>Universitas Islam Negeri Sultan Syarif Kasim Riau</p>
       </div>
       <div class="sosial-links">
           <div class="link">
             <a href="https://www.instagram.com/mhdrmaulana/"><img src="../assets/instagram.jpeg" alt="" style="width:30px;height:30px;">
               <h2>Instagram</h2></a>
           </div>
           <div class="link">
             <a href="https://github.com/mhdrmaulana"><img src="../assets/github.jpeg" alt="" style="width:30px;height:30px;" >
               <h2>GitHub</h2></a>
           </div>
           <div class="link">
             <a href="http://wa.me/6281371908215"><img src="../assets/wa.jpeg" alt="" style="width:30px;height:30px;">
               <h2>WhatsApp</h2></a>
           </div>
         
       </div>
     </div>
     <div class="container-two">
        <div class="about-me">
         <h1>Tentang Ku</h1>
         <p>Nama Saya Muhammad Rizky Maulana </p>
        </div>
       <div class="tecnology-section">
          <h1>Education</h1>
         
        </div>
        <div class="button-container">
           <div class="project-button">
             <a href="">Formal</a>
            </div>
            <div>
            <div class="project-button">
             <a href="">Non Formal</a>
            </div>
            </div>
          </div>
      </div>
    </div>
   </template>
     
   <script>
   
   </script>
     
   <style scoped>
     img{
       height: 45px;
     }
     .main-container{
       display: flex;
       flex-direction: row;
       background-color: rgb(255, 255, 255);
       border-radius: 150px;
       
     }
     .container-one{
       background: linear-gradient(rgba(126, 9, 9, 0.96), rgb(245, 9, 9), rgba(218, 224, 224, 0.96)),center/cover no-repeat;
       padding: 2.5%;
       margin: 2%;
       color: antiquewhite;
       width: 30%;
       border-radius: 15px;
     }
   
     .profile img{
       background-color: rgb(255, 255, 255) ;
       height: 15rem;
       padding-top: 2%;
       border-radius: 55%;
     }
     .link a{  
       text-decoration: none;
       color: rgb(67, 67, 67);
       font-size: 10px;
     }
     .link img{
       height: 13rem;
     }
     .container-two{
       background: linear-gradient(rgba(126, 9, 9, 0.96), rgb(245, 9, 9), rgba(218, 224, 224, 0.96)),center/cover no-repeat;
       margin: 2%;
       padding-top: 2%;
       padding-left: 2%;
       margin-left: 1%;
       border-radius: 5%;
       color: antiquewhite;
       width: 70%;
     }
     .about-me{
       text-align: left;
     }
     .logo img{
       height: 4rem;
     }
   
     .button-container{
       margin-top: 5px;
       display: flex;
       flex-direction: row;
       justify-content: center;
       align-items: center;
   
       
     }
   
     .project-button{
       background-color: rgb(82, 77, 77) ;
       border-radius: 35%;
       padding: 5px;
       margin: 6px;
     }
     .project-button a{
       text-decoration: none;
       color: rgb(255, 255, 255);
     }
   
   </style>
     