<template>
  <div id="app">
    <div class="head">
      <div class="banxin">
        <div class="fl-l">
          <a href="" class="big">Bootstrap中文网</a>
          <a href="">Bootstrap2中文文档</a>
          <a href="">Bootstrap3中文文档</a>
          <a href="">Bootstrap4中文文档</a>
          <a href="">Less 教程</a>
          <a href="">jQuery API</a>
          <a href="">网站实例<sup class="ab"></sup></a>
        </div>
        <div class="fl-r">
          <a href="">关于</a>
        </div>
      </div>
    </div>
    <div class="banner">
      <h1>Bootstrap</h1>
      <h2>简洁、直观、强悍的前端开发框架，让web开发更迅速、简单。</h2>
      <button><a href="">Bootstrap3中文文档(v3.3.7)</a></button>
      <p><a href="">Bootstrap2中文文档(v2.3.2)</a></p>
    </div>
    <div class="banner-bottom">
      <span>
        <a href="" class="el-icon-edit">Bootstrap问答社区</a>
        <i></i>
        <a href="" class="el-icon-share red"> 新浪微博：@Bootstrap中文网</a>
      </span>
    </div>
    <div class="nav">
      <h1>Bootstrap相关优质项目推荐</h1>
      <p>这些项目或者是对Bootstrap进行了有益的补充，或者是基于Bootstrap开发的</p>
    </div>
    <div class="box">
      <div class="banxin">
        <div class="item">
          <img src="./assets/expo.png" alt="">
          <h2>优站精选</h2>
          <p class="p1">Bootstrap 网站实例</p>
          <p>Bootstrap 优站精选频道收集了众多基于 Bootstrap 构建、设计精美的、有创意的网站。</p>
        </div>
         <div class="item">
          <img src="./assets/expo.png" alt="">
          <h2>优站精选</h2>
          <p class="p1">Bootstrap 网站实例</p>
          <p>Bootstrap 优站精选频道收集了众多基于 Bootstrap 构建、设计精美的、有创意的网站。</p>
        </div>
         <div class="item">
          <img src="./assets/expo.png" alt="">
          <h2>优站精选</h2>
          <p class="p1">Bootstrap 网站实例</p>
          <p>Bootstrap 优站精选频道收集了众多基于 Bootstrap 构建、设计精美的、有创意的网站。</p>
        </div>
         <div class="item">
          <img src="./assets/expo.png" alt="">
          <h2>优站精选</h2>
          <p class="p1">Bootstrap 网站实例</p>
          <p>Bootstrap 优站精选频道收集了众多基于 Bootstrap 构建、设计精美的、有创意的网站。</p>
        </div>
         <div class="item">
          <img src="./assets/expo.png" alt="">
          <h2>优站精选</h2>
          <p class="p1">Bootstrap 网站实例</p>
          <p>Bootstrap 优站精选频道收集了众多基于 Bootstrap 构建、设计精美的、有创意的网站。</p>
        </div>
         <div class="item">
          <img src="./assets/expo.png" alt="">
          <h2>优站精选</h2>
          <p class="p1">Bootstrap 网站实例</p>
          <p>Bootstrap 优站精选频道收集了众多基于 Bootstrap 构建、设计精美的、有创意的网站。</p>
        </div>
        <div class="item">
          <img src="./assets/expo.png" alt="">
          <h2>优站精选</h2>
          <p class="p1">Bootstrap 网站实例</p>
          <p>Bootstrap 优站精选频道收集了众多基于 Bootstrap 构建、设计精美的、有创意的网站。</p>
        </div>
        <div class="item">
          <img src="./assets/expo.png" alt="">
          <h2>优站精选</h2>
          <p class="p1">Bootstrap 网站实例</p>
          <p>Bootstrap 优站精选频道收集了众多基于 Bootstrap 构建、设计精美的、有创意的网站。</p>
        </div>
        <div class="item">
          <img src="./assets/expo.png" alt="">
          <h2>优站精选</h2>
          <p class="p1">Bootstrap 网站实例</p>
          <p>Bootstrap 优站精选频道收集了众多基于 Bootstrap 构建、设计精美的、有创意的网站。</p>
        </div>
        <div class="item">
          <img src="./assets/expo.png" alt="">
          <h2>优站精选</h2>
          <p class="p1">Bootstrap 网站实例</p>
          <p>Bootstrap 优站精选频道收集了众多基于 Bootstrap 构建、设计精美的、有创意的网站。</p>
        </div>
        <div class="item">
          <img src="./assets/expo.png" alt="">
          <h2>优站精选</h2>
          <p class="p1">Bootstrap 网站实例</p>
          <p>Bootstrap 优站精选频道收集了众多基于 Bootstrap 构建、设计精美的、有创意的网站。</p>
        </div>
        <div class="item">
          <img src="./assets/expo.png" alt="">
          <h2>优站精选</h2>
          <p class="p1">Bootstrap 网站实例</p>
          <p>Bootstrap 优站精选频道收集了众多基于 Bootstrap 构建、设计精美的、有创意的网站。</p>
        </div>
      </div>
    </div>
    <footer0></footer0>
  </div>
</template>

<script>
import Footer from './components/footer'
export default {
  name: 'App'
  ,
  data(){
      return{}
  },
  components:{
    "footer0":Footer
  }
}
</script>

<style scoped>
#app {
  width: 100%;
  position:absolute;
  right:0;
  left: 0;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
*{
  margin: 0;
  padding: 0;
}
li{
  list-style: none;
}
a{
  color: #fff;
  text-decoration: none;
}
html body .big{
  font-size:16px;
}
.banxin{
  width: 1170px;
  margin: 0 auto;
  overflow: hidden;
}
.fl-l{
  float:left;
}
.fl-r{
  float:right;
}
.re{
  position: relative;
}
.ab{
  position: absolute;
}
.head{
  position: fixed;
  top:0;
  left: 0;
  right: 0;
  border-bottom:1px solid #000; 
  height: 42px;
  line-height: 42px;
  background-color: #222;
  border-color: #080808;
}
.head a{
  font-size: 14px;
  color: #9d9d9d;
  float:left;
  display:inline-block; 
}
.head a:hover{
   color:#fff;
}
.head .fl-l a+a{
  margin-left:30px
}
.head sup{
  width: 8px;
  height: 8px;
  border-radius: 50%;
  background-color: #d9534f;
  top:9px;
}
.banner{
  padding: 90px 0 110px;
  color:#fff;
  text-align: center;
  background:linear-gradient(45deg,#020031 0,#6d3353 100%);
  background-image: linear-gradient(45deg, rgb(2, 0, 49) 0px, rgb(109, 51, 83) 100%);
}
.banner h1{
  font-size: 100px;
  font-weight: 700;
}
.banner h2{
  font-size: 30px;
  font-weight:normal;
}
.banner button{
  box-shadow: inset 0 -4px 0 #2a6496; 
  margin:20px 0;
  font-size: 18px;
  border-radius: 6px;
  padding: 13px 35px 17px;
  background-color: #337ab7;
  border:none;
}
.banner-bottom{
  height: 54px;
  line-height: 54px;
  text-align: center;
  background-color: #f5f5f5;
  border-top: 1px solid #fff;
  border-bottom: 1px solid #ddd;
}
.banner-bottom a{
  color: #000;
  content: "|";

}
.banner-bottom a:hover{
  text-decoration: underline;
}
.banner-bottom .red:hover
{
  color: #d9534f;
}
.banner-bottom i{
  display:inline-block;
  width:1px;
  height:15px;
  margin:0 10px;
  position: relative;
  top:3px;
  background-color:#ccc;
}
.nav{
  width: 684px;
  border-bottom:1px solid #eee; 
  margin:50px auto 40px auto; 
}
.nav h1{
  font-size:42px;
  font-weight: normal;
  margin-bottom: 10px;
}
.nav p{
  margin: 0 0 20px;
}
.box .item{
  margin-bottom:40px; 
  height: 336px;
  margin-right:3.33%;
  width: 22.5%;
  box-sizing: border-box;
  padding: 4px;
  border:1px solid #ddd; 
  float: left;
}
.box .item img{
  width: 100%;
}
.box .item h2{
  margin-top:20px;
  color: red;
  font-weight:normal;
}
.box .item .p1{
  margin:7px 0 10px 0; 
}
.box .item p{
  color: #777;
}
.box .item:nth-child(4n){
 margin-right:0;
}
</style>
