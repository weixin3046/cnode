<template>
	<div class="navbar">
		<div class="container clearfix">
			<router-link :to="{name:'home'}" class="logo"><i class="">我是logo</i></router-link>
			<form class="navbar-search"><input type="text" class="search-query" value=""></form>
			<ul class="clearfix f-r">
				<li><router-link :to="{name:'home'}">首页</router-link></li>
				<li><router-link :to="{name:'home'}">新手入门</router-link></li>
				<li><router-link :to="{name:'home'}">API</router-link></li>
				<li><router-link :to="{name:'home'}">关于</router-link></li>
				<li><router-link :to="{name:'home'}">注册</router-link></li>
				<li><router-link :to="{name:'home'}">登录</router-link></li>
			</ul>
		</div>
	</div>
</template>
<script>
export default {
  data () {
    return {
    }
  },
  methods: {

  }
}
</script>
<style scoped>
.navbar {
	background: #444;
	font-size: 13px;
	padding: 5px;
}
.navbar .logo {
	width: 120px;
    padding: 3px 20px;
    height: 34px;
    line-height: 34px;
    color: #ccc;
    font-weight: 700;
    float: left;
    margin-left: -20px;
}
.navbar .navbar-search {
	margin-top: 6px;
	float: left;
	margin-bottom: 0;
}
.navbar ul li {
	float: left;
}
.navbar ul>li>a {
	color: #ccc;
	padding: 10px 15px;
}
</style>