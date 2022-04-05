<template>
  <div class="menu">
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