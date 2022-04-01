<template>
  <div class="about">
    <h1>This is an about page</h1>
    <h3>Estamos en la pasteria</h3>
    <acercadeCom/>
    <footerCom/>
  </div>
</template>

<script>

import acercadeCom from "@/components/acercade.vue";
import footerCom from "@/components/footer.vue";

export default {
  name: 'MenuView',
  components: {
    acercadeCom,
    footerCom
  }
}
</script>
