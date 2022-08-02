<template>
  <div class="Error">
    <img alt="xqcL" src="../assets/xqc.gif">
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'HomeView',
  created(){
        document.title = "Error"
    }
});
</script>