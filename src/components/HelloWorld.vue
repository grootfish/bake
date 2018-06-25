<template>
  <div class="hello">
    <el-container>
      <el-aside width="200px">Aside</el-aside>
      <el-container>
        <el-header>Header</el-header>
        <el-main>Main</el-main>
      </el-container>
    </el-container>
  </div>
</template>

<script>
import Vue from 'vue';
import { Button, Select, Container, Aside, Header, Main } from 'element-ui';


Vue.use(Button);
Vue.use(Select);
Vue.use(Container);
Vue.use(Aside);
Vue.use(Header);
Vue.use(Main);


export default {
  name: 'HelloWorld',
  data() {
    return {
      msg: 'This is our Life',
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>


</style>
