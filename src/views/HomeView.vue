<template>
  <div class="home">
    <infInicio/>
    <footerCom/>
  </div>
</template>
<script>
// import infInicio  from "../src/components/infInicio.vue";
import infInicio from "@/components/infInicio.vue";
import footerCom from "@/components/footer.vue";

export default {
  name: 'HomeView',
  components: {
    infInicio,
    footerCom
  }
}
</script>
