<template>
    <div class="pastelero">
        <pasteleroCom/>
        <footerCom/>
    </div>
</template>

<script>
// import infInicio  from "../src/components/infInicio.vue";
import pasteleroCom from "@/components/pastelero.vue";
import footerCom from "@/components/footer.vue";

export default {
  name: 'PasteleroView',
  components: {
    pasteleroCom,
    footerCom
  }
}
</script>