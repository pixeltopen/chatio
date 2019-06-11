<template>
    <div class="w-full max-w-xs justify-center">
  <form class="bg-light-white shadow-xl rounded px-8 pt-6 pb-8 mb-4">
    <div class="mb-4">
      <input class="appearance-none bg-fog-gray rounded w-full py-3 px-5 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="username" type="text" placeholder="username">
    </div>
    <div class="mb-6">
      <input class="appearance-none bg-fog-gray rounded w-full py-3 px-5 text-gray-700 mb-3 leading-tight focus:outline-none focus:shadow-outline" id="password" type="password" placeholder="***********">
    </div>
    <div class="flex items-center justify-between">
     <a class="inline-block align-baseline font-bold text-sm text-blue-500 hover:text-blue-800" href="#">
        Forgot Password?
    </a>
      <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded focus:outline-none focus:shadow-outline" type="button">
        Sign In
      </button>
    </div>
  </form>
  <p class="text-center text-gray-500 text-xs">
    terms of service // privacy policy
  </p>
</div>
</template>

<script>
import header from '@/components/shared/Header.vue'
    export default {
        name: 'Login',

        components: {
            header
        },

        data() {
            return {
                name: ''
            }
        },
    }
</script>

<style scoped>

</style>