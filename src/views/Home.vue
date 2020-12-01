<template>
  <div class="sample">{{ sample }}</div>
</template>
<script>
export default {
  data() {
    return {
      sample: "This is a sample",
    };
  },
};
</script>
<style lang="scss" scope>
@import "../styles/main.scss";
.sample {
  color:red;
}
</style>
