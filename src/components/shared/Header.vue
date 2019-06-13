<template>
  <div class="flex justify-between">
    <div class="mr-3">
      <img class="w-12 h-12 mx-3 my-2" src="../../assets/logo.png" alt="chatter.io logo"/>
    </div>
    <div class="mr-4 ml-6 mt-3">
       <router-link class="mr-5 rounded-full text-white opacity-77 py-1 px-3 bg-light-teal" to="/about">why chatter.io?</router-link> 
      <router-link class="rounded-full text-white opacity-77 py-1 px-3 bg-light-purple" to="/faq">faq</router-link>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'Header'
  }
</script>

<style lang="scss" scoped>

// .header {
//   display: flex;
//   justify-content: space-between;
//   img {
//     width: 50px;
//     height: 50px;
//   }
// }
</style>