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
      <!-- <template slot-scope="app">
        {{app}}
        <p v-for="(item,index) in app.data" :key="index">
          {{item}}
        </p>
      </template> -->
      <!-- <kk ></kk> -->
    </top>
    <div>
      <div>图片</div>
      <div>我的</div>
      <div>
        <div>000000</div>
      </div>
    </div>
  </div>

</template>

<script>
import top from "./coomit/top.vue";
import kk from "./coomit/kk.vue";
export default {
  components: {
    top,
    kk
  },
  mounted() {
    this.show();
  },
  methods: {
    // reduce
    show() {
      var a = ["10", "11", [1, 2, 2, 2], "13", "14", "15", "16"];
      a.reduce((add, item, index) => {
        console.log("xxx", add, item, index);
        return item;
      });
    }
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
