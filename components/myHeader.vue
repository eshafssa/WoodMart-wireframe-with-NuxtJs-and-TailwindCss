<template>
  <div>
    <header class="flex justify-between bg-white h-26 lg:pt-5 lg:py-2 lg:px-32 md:px-9 sm:p-4 ">
        <div class="flex items-center mt-2">
          <img src="~/assets/img/logo.png" alt="" class="w-10 h-10">
          <p class="text-yellow-800 font-semibold font-SourceSansPro  lg:text-2xl md:text-lg  sm:text-sm">woodmart</p>
        </div>
        <div class="flex items-center" >
          <div class="flex items-center bg-white border border-black lg:w-96 lg:h-10 sm:w-48 sm:h-4" >
            <input class="w-full focus:outline-none lg:m-4 md:mx-2 sm:mx-2" type="text" name="" placeholder="Search 'Rock Chair'" id="">
            <my-icons name="search" class="cursor-pointer mr-4" />
          </div>
          <div class="flex  justify-around items-center mx-4 border border-black  h-8  w-48">
            <div class="flex items-center">
              <my-icons name="accountBox" class="cursor-pointer m-2"/>
              <p class="text-base">MY ACCOUNT</p>
            </div>
            <my-icons name="dropDown" class="cursor-pointer"/>
          </div>
        </div>

    </header>
  </div>
</template>
<script>
import MyIcons from '~/components/myIcons.vue'
export default {
  name:'myHeader',
  components:{MyIcons},

  props:{}
}
</script>
