<template>
  <div>
    <p>ssssss</p>
    <top>
      <!-- <template slot-scope="user">
        {{user}}
        <p v-for="(item,index) in user.data" :key="index">
          {{item}}
        </p>
      </template> -->
      <template slot-scope="app">
        {{app}}
        <p v-for="(item,index) in app.data" :key="index">
          {{item}}
        </p>
      </template>

    </top>

  </div>
</template>

<script>
import top from "./coomit/top.vue";
export default {
  components: {
    top
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
