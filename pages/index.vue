<template>
<div>
  <div>
  <my-header/>
  <my-navbare/>
  </div>
  <my-icons/>
</div>
</template>

<script>
import myHeader from '~/components/myHeader.vue'
import myNavbare from '~/components/myNavbare.vue'
import MyIcons from '~/components/myIcons.vue'
export default {
  components: { myHeader, MyIcons,myNavbare },}
</script>
