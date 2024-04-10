<script>
export default {

}
</script>
<template>

<section>

  <div class="my_p d-flex justify-content-center col-12  text-center flex-column ">

    <div>
      <p class="my_title">OUR MISSION</p>
    </div>

    <div class="my_cont d-flex justify-content-center "></div>
    
    <div class=" text-center text-white py-3">
      <p>Think Big.Act Bigger</p>
      
    </div>

  </div>
  <!-- cards -->

  <div class="my_margin d-flex justify-content-center">

    <div class=" flex-column my_card ">

      <div class="my_icon text-center ">
        <i class="fa-solid fa-droplet"></i>
      </div>

      <div class=" text-center text-white ">
        <h5>Clean water</h5>
      </div>

      <div class=" text-center  text-white">
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Velit aliquam har</p>
      </div>

       <div class=" text-center text-white ">
        <button type="button" class="btn btn-outline-warning">OUR MISSION</button>
       </div>

    </div>
    <!-- fine primo -->
    <div class=" flex-column my_card ">

      <div class="my_icon text-center ">
        <i class="fa-solid fa-stethoscope"></i>
      </div>

      <div class=" text-center text-white ">
        <h5>vaccinations</h5>
      </div>

      <div class=" text-center  text-white">
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Velit aliquam har</p>
      </div>

       <div class=" text-center text-white ">
        <button type="button" class="btn btn-outline-warning">OUR MISSION</button>
       </div>

      </div>
      <!-- fine sec -->

    <div class=" flex-column my_card ">

      <div class="my_icon text-center ">
        <i class="fa-solid fa-graduation-cap"></i>
      </div>

      <div class=" text-center text-white ">
        <h5>education</h5>
      </div>

      <div class=" text-center  text-white">
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Velit aliquam har</p>
      </div>

       <div class=" text-center text-white ">
        <button type="button" class="btn btn-outline-warning">OUR MISSION</button>
       </div>

        </div>
        <!-- fine terzo -->

        <!-- fine primo -->
    <div class=" flex-column my_card ">

      <div class="my_icon text-center ">
        <i class="fa-solid fa-wheat-awn"></i>
      </div>

      <div class=" text-center text-white ">
        <h5>farming</h5>
      </div>

      <div class=" text-center  text-white">
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Velit aliquam har</p>
      </div>

       <div class=" text-center text-white ">
        <button type="button" class="btn btn-outline-warning">OUR MISSION</button>
       </div>

        </div>
        <!-- fine primo -->
            


  </div>

</section>

</template>


<style scoped>
section{
  min-height: 600px;
  background-image: url(../assets/img/home-content-bg-2.jpg);
  background-size: cover;
  width: 100%;
}
.my_icon{
  color: #FCD66C;
  font-size: 1.3rem;
  padding: 3px;
}
.my_margin{
  margin-top: 50px;
}
.my_card{
  width: 300px;
  height: 200px;
}
.my_cont{
  border-bottom: 2px solid #FCD66C;
  width: 120px;
  margin-left: 46%;
}
.my_title{
  margin-top: 90px;
  color: white;
  font-size: 1.3rem;
}
i{
  font-size: 4rem;
}


</style>
