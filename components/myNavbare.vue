<template>
  <div class="bg-yellow-700">
      <ul class="text-white flex justify-start my-4 mx-32 p-5 " style="">
        <div v-for="ttl in titles" :key=ttl.id>
          <li class="px-4 font-semibold text-sm border-b border-opacity-0 hover:border-opacity-100 hover:border-white"><a href="#">{{ttl.title}}</a></li>
        </div>
      </ul>
  </div>
</template>
<script>
export default {
  data (){
    return{
      titles:[
        {id:'1', title:'HOME'},
        {id:'2', title:'FEATURED'},
        {id:'3', title:'CATEGORY'},
        {id:'4', title:'ABOUT US'},
        {id:'5', title:'BLOG'},
        ]
    }
  }
}
</script>
<style>
</style>
