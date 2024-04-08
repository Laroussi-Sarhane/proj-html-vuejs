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
        {
          title: 'DONATE',
          link: '#'
        }
      ]
    }
  }

}
</script>
<template>

  <header>

    <div class=" container d-flex justify-content-between  ">
   
     <div class=" pt-2">
       logo
     </div>
   
     <div>
       <ul class=" d-flex list-unstyled">
         <li v-for="(item, index) in Menu " :key="index" class=" p-2 ">
          <a :href="item.link">{{ item.title }}</a>
        </li>
       </ul>
     </div>
   
    </div>
  </header>


</template>


<style scoped>
header{
  min-height: 550px;
  background-color: grey;
}
a{
  color: white;
  padding-top: 10px;
}

</style>