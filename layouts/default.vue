<template>
  <el-container class="layout-default">
    <el-header height="197px">
      <my-header/>
    </el-header>
    <el-main>
      <nuxt/>
    </el-main>
    <!-- height='100%' 去掉默认 60px -->
    <el-footer height="100%">
      <my-footer/>
    </el-footer>
  </el-container>
</template>

<script>
import MyHeader from '@/components/public/header/index'
import MyFooter from '@/components/public/footer/index'
export default {
	components: {
		MyHeader,
		MyFooter
	}
}
</script>

<style lang='scss'>
</style>
