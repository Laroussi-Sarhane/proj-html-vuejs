  <script>
  export default {
    data(){
    return{
      social:[
        {
          title: '<i class="fa-brands fa-facebook"></i>',
          link: '#'
        },
        {
          title: '<i class="fa-brands fa-instagram"></i>',
          link: '#'
        },
        {
          title: '<i class="fa-brands fa-x-twitter"></i>',
          link : '#'
        },
        {
          title: '<i class="fa-brands fa-youtube"></i>',
          link: '#'
        },
       
      ]
    }
  }
  
  }
  </script>
<template>
 <footer>

  <div class="footer_top d-flex  justify-content-center ">
    <div>
      <img src="../assets/img/avada-charity-mobile-logo-retina.png" alt="">
    </div>

  </div>

  <div class=" my_cont  ">

    <div class=" col-12  text-center d-flex  justify-content-center  ">
      <div class=" mt-3 d-flex ">
        <div class=" d-flex">
          <li><i class="fa-solid fa-copyright my_font"></i></li>

          <div>
            <p class="my_font p-1 ">copyright 2010-2020 AVADA THEME BY THEM FUSION |</p>
          </div>
        </div>

        <div>
          <p class=" my_font p-1 ">  ALL RIGHTS RESERVED  |</p>
        </div>

        <div>
          <p class="my_font p-1 "> POWERED BY BOOLEAN</p>
        </div>
      </div>
    </div>

    <div class=" col-12 text-center d-flex  justify-content-center">
      <div class=" d-flex ">
        <div class=" d-flex">
          <li v-for="(item, index) in social" :key="index">
            <a :href="item.link" v-html="item.title" ></a>
          </li>
        </div>
      </div>

    </div>
    
  </div>

  
 </footer>

</template>



<style scoped>
.footer_top{
  padding-top: 30px;
  height: 130px;
}
img{
  width: 250px;

}
.my_cont{
  background-color: #F9F9F9;
  height: 130px;
}
a {
  background-color: white;
  border-radius: 50%;
  padding: 10px;
  color: #FCD66C;
  margin: 6px;
  font-size:20px;
}
li{
  text-decoration: none;
  list-style: none;
}
.my_font{
  font-size: 10px;
  color: #B1B1B0;
}
</style>