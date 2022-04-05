<template>
  <div class="about">
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
