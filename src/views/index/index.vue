<template>
  <div class="index-page">
    <canvas id="cv"></canvas>
  </div>
</template>
<script lang='ts'>
import { defineComponent } from "vue";
export default defineComponent({
  data() {
    return {};
  },
  mounted() {
    let a: string = "a";
  },
});
</script>
<style lang="less" scoped>
.index-page {
  #cv {
    width: 400px;
    height: 400px;
  }
}
</style>