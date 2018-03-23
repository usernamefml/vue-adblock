<template>
<div>
<div ref="infoBox">
    <div class="adBanner">
    </div>
</div>
</div>
</template>

<script>
export default {
  data: function() {
    return {
      add: ""
    };
  },
  mounted: function() {
    var self = this;
    var vis = self.$refs.infoBox.clientHeight;

    if (vis > 0) {
    } else {
      self.add = "detected";
      self.$emit("passValue", self.add);
    }
  }
};
</script>

<style scoped>
.adBanner {
  background-color: transparent;
  height: 1px;
  width: 1px;
}
</style>
