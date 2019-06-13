<template>
    <div class="container mx-auto max-w-md justify-center">
  <form class="bg-light-white opacity-75 shadow-xl rounded px-12 py-10 pt-6 pb-8 mb-4">
      <h1 class="text-default-teal font-pacifico -mb-3">
            chatter.io
        </h1>
        <p class="text-lg font-roboto mb-6 text-default-teal flex justify-center">
            where every conversation is a party
            <span class="font-roboto text-xxs mt-1 ml-1 text-default-teal">TM</span>
        </p>
         
    <div class="mb-4">
      <input class="appearance-none bg-fog-gray text-lg font-roboto rounded w-full py-3 px-5 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="email" type="email" placeholder="e-mail address">
    </div>
    <div class="mb-2">
      <input class="appearance-none bg-fog-gray text-lg font-roboto rounded w-full py-3 px-5 text-gray-700 mb-1 leading-tight focus:outline-none focus:shadow-outline" id="password" type="password" placeholder="***********">
    </div>
    <div class="flex flex-col justify-center">
     <a class="inline-block font-helvetica align-baseline text-bright-purple text-md mb-2 underline" href="#">
        Forgot your password?
    </a>
      <button class="bg-gradient hover:bg-blue-700 text-white py-3 px-4 font-medium rounded-full mb-4" type="button">
        LOGIN
      </button>
      <button class="bg-transparent border-2 border-dark-purple font-medium text-dark-purple py-3 px-4 rounded-full focus:outline-none focus:shadow-outline mb-2">
        JOIN THE PARTY!
      </button>
    </div>
  </form>
  <div class="text-center text-gray-500 text-sm">
    <a href="#" class="underline mb-2" target="_blank" alt="Terms of Service">
        terms of service
    </a>
    //
    <a href="#" class="underline mb-2" target="_blank" alt="Privacy Policy">
        privacy policy
    </a>
  </div>
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