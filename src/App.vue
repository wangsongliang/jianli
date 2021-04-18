<template>
  <div id="app">
    <div id="nav">
        <div class="bao">
          <router-link to="/"><img alt="头像" class="touxiang" src="./assets/wang.jpg" /></router-link>
          
        </div>
        <div class="baoa">
            <div class="toxianga"><router-link to="/about">我的技能</router-link></div>
            <div class="toxianga"><router-link to="/jingli">我的经历</router-link></div>
            <div class="toxianga"><router-link to="/jingyan">我的经验</router-link></div>
            <div class="toxianga"><router-link to="/aihao">我的爱好</router-link></div>
        </div>
        <div class="baob">
            个人简历
        </div>
    </div>
    <router-view/>
  </div>
</template>

<style>

body,ul,ol,dl,li,dt,dd,p,h1,h2,h3,h4,h5,h6{
	margin: 0px auto;
	padding: 0px;
	color: #333333;
	font-family: "微软雅黑";
	list-style: none;
}
a,span,label{
	display: inline-block;
}
a{
	color:#333333;
	text-decoration: none;
}
a:hover{
	color: antiquewhite;
}
div{
	margin: auto 50px;
}
#app{
    width: 100%;
    background-color: antiquewhite;
}
#nav{
    margin: auto 50px;
    background-color: #b4cffe;
	overflow: hidden;
}
.bao{
    float: left;
}
.touxiang{
    width: 60px;
    height: 60px;
     border-radius: 30px;
     margin: auto 30px;
}
.toxianga{
    margin-left: 10px;
	float: left;
	line-height: 60px;
}
.baoa{
    overflow: hidden;
}
.baob{
    float: right;
	margin-top: -45px;
    color: antiquewhite;
    font-size: 25px;
    cursor: default;
}
</style>
