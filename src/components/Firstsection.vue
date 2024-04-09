<script>
export default {

}
</script>
<template>

  <section>

    <div class=" container-fluid  d-flex ">
      <div class="my_describ container">
          <h3 class="my_title">EVERY MOMENT COUNTS</h3>
          <div class="sottolineato mb-3"></div>
          <div class=" flex-column ">
  
            <div>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nisi, veniam. Facere voluptatum ex nulla aperiam. Consequatur architecto consectetura</p>
            </div>
  
            <div>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nisi, veniam. Facere voluptatum ex nulla aperiam. Consequatur architecto consectetura</p>
            </div>
  
            <div>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nisi, veniam. Facere voluptatum ex nulla aperiam. Consequatur architecto consectetur</p>
            </div>

            <div class="my_our_mision mb-1">
              <button type="button" class="btn btn-outline-warning">OUR MISSION</button>
            </div>
  
  
          </div>
  
        </div>
        <!-- inizio parte destra con icons -->
      
        <div class="my_icons flex-column  justify-content-center align-content-center   text-center  " >

          <div class=" col-12 ">
            <div class=" d-flex justify-content-center ">
              <div class="my_color">
                <i class="fa-regular fa-heart"></i>
              </div>

              <div class="my_color px-2">
                2032
              </div>
              
            </div>

            <div class="my_color">
              <p>volonteers worldwide</p>
            </div>

          </div>

          <div class=" col-12 ">
            <div class=" d-flex justify-content-center ">
              <div class="my_color">
                <i class="fa-solid fa-globe"></i>
              </div>

              <div class="my_color px-2">
                132
              </div>
              
            </div>

            <div class="my_color">
              <p>Active projects</p>
            </div>

          </div>

          <div class=" col-12 ">
            <div class=" d-flex justify-content-center ">
              <div class="my_color">
                <i class="fa-solid fa-dollar-sign"></i>
              </div>

              <div class="my_color px-2 ">
                3.8 M
              </div>
              
            </div>

            <div class="my_color">
              <p>donated</p>
            </div>

          </div>

          

          
          
        </div>
      
      </div>
        

  </section>


</template>


<style scoped>
section{
  min-height: 500px;
}
.my_describ{
  width: 67%;
  height: 400px;
  padding: 0px 70px;
}
.sottolineato{
  width: 150px;
  border: 2px solid#FCD66C;
}
.my_icons{
  width: 33%;
  height: 500px;
  background-image: url(../assets/img/home-content-bg-1.jpg);
  background-size: cover;
}
.my_title{
  margin-top: 90px;
}
.my_color{
  color: white;
  font-size: 1.4rem;
}
</style>
