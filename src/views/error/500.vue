<template>
  <div>
    <m-header></m-header>
    <m-content>
      <div class="m-500">500</div>
    </m-content>
  </div>
</template>
<script type="text/ecmascript-6">
export default {
  name: "M500",
  methods: {
    fresh() {
      this.$router.replace({
        path: this.$route.query.redirectUrl
      });
    }
  }
};
</script>
<style lang="scss" scoped></style>
