<template>
  <div id="app">
<!--    <div id="nav">-->
<!--      <router-link to="/">Home</router-link> |-->
<!--      <router-link to="/about">About</router-link>-->
<!--    </div>-->
    <router-view/>
  </div>
</template>

<style lang="scss">
//#app {
//  font-family: Avenir, Helvetica, Arial, sans-serif;
//  -webkit-font-smoothing: antialiased;
//  -moz-osx-font-smoothing: grayscale;
//  text-align: center;
//  color: #2c3e50;
$main-color: #42b983;
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  -webkit-tap-highlight-color: rgba(0,0,0,0);
  -webkit-tap-highlight-color: transparent;
}
html {
  font-size: 62.5%;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;

}
li {
  list-style: none;
}
body {
  font-size: 1.4rem;
  font-family: "Microsoft YaHei UI", 微软雅黑， STXihei, 华文细黑， STHeiti, serif;
  display: block;
  width: 100vw;
  height: 100vh;
  position: relative;
  overflow: hidden;
}
a {
  text-decoration: none;
}
input {
   -webkit-appearance: none;
   outline: none;
 }

input[type="submit"] {
  cursor: pointer;
}

input::-moz-focus-inner {
  border: 0;
  padding: 0;
}

input {
  border: 0;
  vertical-align: middle;
  font-family: inherit;
  font-size: inherit;
  font-style: inherit;
  font-weight: inherit;
}

button {
  cursor: pointer;
}

.clr {
  clear: both;
  height: 0;
  line-height: 0;
  font-size: 0
}

.nowrap {
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
}

.btns {
  text-align: center;
  padding-top: 40px;
  button {
    width: 45%;
    height: 45px;
    line-height: 45px;
    text-align: center;
    color: $main-color;
    border: 1px solid $main-color;
    background: #fff;
    border-radius: 6px;
    font-size: 16px;
    &:first-child {
      background: $main-color;
      color: #fff;
      margin-right: 10px;
    }
  }
}

.form-wrapper {
  padding: 10px;
  font-size: 16px;
  .form-input {
    width: 100%;
    line-height: 40px;
    padding: 5px;
    label {
      width: 20%;
      text-align: right;
      display: inline-block;
      padding-right: 8px;
    }
    input {
      width: 80%;
      border: 1px solid #dcdcdc;
      border-radius: 6px;
      line-height: 40px;
      padding-left: 6px;
    }
  }
}
</style>
