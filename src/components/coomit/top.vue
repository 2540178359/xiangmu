<template>
  <div>
    <div>这是头部</div>
    <slot ></slot>
  </div>
</template>
<script>
export default {
  data: function() {
    return {
      data: ["zhangsan", "lisi", "wanwu", "zhaoliu", "tianqi", "xiaoba"]
    };
  }
};
</script>