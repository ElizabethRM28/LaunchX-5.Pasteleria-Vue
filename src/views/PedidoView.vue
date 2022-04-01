<template>
  <div class="pedido">
    <h1>Pedido</h1>
    <h3>...</h3>
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