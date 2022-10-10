<template>
    <section class="am-jumbotron d-flex justify-content-around align-items-center">

        <div class="am-jumbo-title mt-5">
          
            <h1 class="mb-4">Complete Your Dreams in JavaS Programming</h1>
            <p class="mb-4">Learn any coding program in distance and for a reasonable fee. You don't have to struggle alone, you've got our assistance and help.</p>
            <button>Download free E-book</button>

        </div>

        <div class="mt-5"> 
            <img src="../assets/home-5-hero-image.png" alt="man writing on computer"> 
        </div>
        
    </section>
  </template>
  
  
  <!-- *****JAVSCRIPT***** -->
  <script>
  export default {
  name: 'JumbotronComponent'
  }
  </script>
  
  
  
  <!-- *****CSS STYLE***** -->
  <style lang="scss" scoped>
  @import "../style/common.scss";
  .am-jumbotron{
    background-color: #E9E6E3;
    height: 52rem;
    background-image: url(../assets/wave.svg);
    background-repeat: no-repeat;
    background-position-y: bottom;
  }

  .am-jumbo-title{
    width: 23rem;
  }

 p{
  line-height: 1.7rem;
  }

  </style>