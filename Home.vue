<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/Delite.jpg" />
    <HelloWorld msg="Welcome to Delite software technologies" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "home",
  components: {
    HelloWorld
  }
};
</script>
