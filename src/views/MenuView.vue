<template>
  <div class="menu">
    <h1>Menu</h1>
    <h3>...</h3>
    <menupastCom/>
    <footerCom/>
  </div>
</template>

<script>

import menupastCom from "@/components/menupast.vue";
import footerCom from "@/components/footer.vue";

export default {
  name: 'MenuView',
  components: {
    menupastCom,
    footerCom
  }
}
</script>