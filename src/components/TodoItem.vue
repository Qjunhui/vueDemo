<template>
  <li class="item" @click="handleClick">{{content}}</li>
</template>

<script>
export default {
  props : ["content","index"],
  methods : {
    handleClick : function(){
      this.$emit("delete",this.index);
    }
  }
}
</script>
<!-- scoped为局部样式 -->
<style scoped>
  .item {
    color : saddlebrown;
  }
</style>
