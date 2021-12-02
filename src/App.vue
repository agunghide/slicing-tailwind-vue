<template>
  <div id="app" class="bg-gray-300">
    <div class="container mx-auto py-8 grid grid-cols-1 gap-4 p-5 sm:grid-cols-1 sm:gap-6 md:grid-cols-2 md:gap-8 md:px-0 lg:grid-cols-3 lg:gap-12 lg:px-0 transition-all duration-200 ease-linear">
      <Card v-for="n in 10" :key="`card-${n}`" />
    </div>
  </div>
</template>

<script>
import Card from "./components/Card.vue";
import "./tailwind.css";

export default {
  name: 'App',
  components:{
      Card,
  }
}
</script>
