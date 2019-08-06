<template>
	<div>
		<ul>
			<li>这是logo</li>
			<li><i>搜索</i><input type="text"></li>
		</ul>
		<ul>
			<li><router-link :to="{name:'home'}">首页</router-link></li>
			<li><router-link :to="{name:'home'}">新手入门</router-link></li>
			<li><router-link :to="{name:'home'}">API</router-link></li>
			<li><router-link :to="{name:'home'}">关于</router-link></li>
			<li><router-link :to="{name:'home'}">注册</router-link></li>
			<li><router-link :to="{name:'home'}">登录</router-link></li>
		</ul>
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
	
</style>