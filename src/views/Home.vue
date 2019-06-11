<template>
  <div class="home">
    <Header></Header>
    <Login></Login>
  </div>
</template>

<script>
// @ is an alias to /src
import Login from "@/components/Login.vue";
import Header from "@/components/shared/Header.vue"

export default {
  name: "home",
  components: {
    Login,
    Header
  },
  data() {
    return {
      isCreatingAcct: false
    }
  },
};
</script>
