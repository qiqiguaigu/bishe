<template>
  <div id="app" class="background-image">
    <h1></h1>
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'

//export default {
//  name: 'App',
//  components: {
 //   HelloWorld
//  }
//}
</script>

<style>
body, html {
    margin: 0;
    padding: 0;
    height: 100%;
    font-family: Arial, sans-serif;
}
.background-image {
  background-image: url('./assets/zhu.jpg')!important;
  background-size: cover;
  background-position: center; /*让图片居中*/
  background-repeat: no-repeat; /*不让图片重复*/
  height: 100vh;/*图片占全部界面*/
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  color: white; /*文字颜色*/
  filter: blur(-1px);/*主页背景清晰度*/
}
.overlay {
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 100%;
}


.ghost {
    background-color: transparent;
    border: none;
    color: rgb(0, 0, 0);
    font-size: 1.5rem;
    cursor: pointer;
    padding: 10px 20px;
    outline: none;
}
.header {
          text-align: center; /* 文字居中显示 */
          padding: 20px; /* 根据需要添加内边距 */
          font-size: 20px; /* 放大字体大小，可根据需要调整 */
          color: black; /* 字体颜色为黑 */
      }
 h1 {
    color: black;
    text-align: center;
    margin: 0;
    padding: 20px;
    font-size: 3em;
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    box-sizing: border-box;
}
</style>
