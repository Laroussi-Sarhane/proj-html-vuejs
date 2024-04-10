<script>
export default {
  data(){
    return{
      Menu:[
        {
          title: 'HOME',
          link: '#'
        },
        {
          title: 'MISSION',
          link: '#'
        },
        {
          title: 'CAUSES',
          link : '#'
        },
        {
          title: 'JOURNAL',
          link: '#'
        },
       
      ]
    }
  }

}
</script>
<template>

  <header>
    <!-- top header -->

    <div class=" container d-flex justify-content-between pt-3">
   
     <div class=" pt-2">
       <img src="../assets/img/avada-charity-logo.png" alt="">
     </div>
   
     <div>
       <ul class=" d-flex list-unstyled  ">
         <li v-for="(item, index) in Menu " :key="index" class=" p-2 ">
          <a :href="item.link">{{ item.title }}</a>
        </li>
        <li  class=" my_botton p-2 ">
          <a href="">DONATE</a>
        </li>
       </ul>
     </div>
    </div>
    <!-- fine top header -->
    <div class=" d-flex flex-column  justify-content-center align-content-center ">

     <div class="my_paragraf cdeb d-flex  justify-content-center ">
       <h1>MAKE A DIFFERENCE</h1>
     </div>

     <div class=" cdeb d-flex justify-content-center align-content-center ">
      <p>as long as poverty, injustice & inequality persist, none of us can truly rest </p>
     </div>

     <div class="cdeb d-flex justify-content-center align-content-center  ">
        <div class="my_bottone">
          <button type="button" class="btn btn-outline-light">OUR MISSION</button>
        </div>

        <div class="my_secbottone">
          <button type="button" class="btn btn-outline-warning">DONATE NOW</button>
        </div>

     </div>

     

    </div>
  </header>


</template>


<style scoped>
header{
  min-height: 600px;
  background-color: grey;
  background-image: url(../assets/img/home-page-slider.jpg);
  background-size: cover;
  width: 100%;
}
a{
  color: white;
  padding-top: 10px;
  text-decoration: none;
}
a:hover{
  text-decoration: underline;
  color: #FCD66C;
}
img{
  width: 250px;
}
.my_botton{
  background-color: #FCD66C;
  color: black;
}
.my_botton.a:hover{
  color: black;
}
.my_paragraf{
  
  margin-top: 150px;
}
.cdeb{
  color: white
}
.my_bottone{
  padding-right: 5px;

}
.my_bottone:hover{
  color: #FCD66C;
}
.my_secbottone{
  padding-left: 5px;
  
}

</style>