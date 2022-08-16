<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <ShowMessageVue/>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
  // @ is an alias to /src
  import HelloWorld from '@/components/HelloWorld.vue';
  import ShowMessageVue from '@/components/ShowMessage.vue';

  export default {
    name: 'HomeView',
    components: {
      //HelloWorld,
      ShowMessageVue
  },
  };

</script>

