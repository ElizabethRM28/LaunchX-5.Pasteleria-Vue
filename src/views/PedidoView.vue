<template>
  <div class="pedido">
    <pedidosCom/>
    <footerCom/>
  </div>
</template>

<script>

import pedidosCom from "@/components/pedidos.vue";
import footerCom from "@/components/footer.vue";

export default {
  name: 'MenuView',
  components: {
    pedidosCom,
    footerCom
  }
}
</script>