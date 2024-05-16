<template>
	<!-- 首页顶部搜索 -->
	<div ref="container">
		<!-- 这里是导航列表 -->
		<div id="nav-container">
			<IndexNavGroup v-for="(nav, i) in navList" :idx="i" :groupData="nav"></IndexNavGroup>
		</div>
	</div>
</template>
<script setup lang="ts">
import navList from '../config/nav.json'
</script>
<script>
var _hmt = _hmt || [];
(function() {
  var hm = document.createElement("script");
  hm.src = "https://hm.baidu.com/hm.js?0e7521c50c178f15b6dff7dae949b84a";
  var s = document.getElementsByTagName("script")[0];
  s.parentNode.insertBefore(hm, s);
})();
</script>

<style></style>
