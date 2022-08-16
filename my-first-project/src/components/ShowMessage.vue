<template>
   <div>
        <h1>Dynamic Message:{{msg}} </h1>
        <button @click="showConsole">console</button>
   </div> 
</template>

<script>
import { ref, defineComponent } from "vue";
export default {
    name:"ShowMessage",
    setup: () => {
    const msg = ref("initial message");
 
    const showConsole = () => {
      console.log("Hello World");
    }
 
    return { msg, showConsole };

}
}
</script>

<style>

</style>