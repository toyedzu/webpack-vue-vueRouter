<!--App.vue是项目入口文件。-->
<template>
    <div id="app">
        <router-view></router-view>
        <footer-tab></footer-tab>
    </div>
</template>

<script>
import FooterTab from './components/footer.vue';
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  components:{
    FooterTab
  }
}
</script>
<style lang='less'>
  #app{
    width:100%;
    height:100%;
  }
</style>