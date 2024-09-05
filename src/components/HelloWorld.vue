<template>
  <div class="hello">
    <u-button :ripple="true">十年</u-button>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
	/* 注意要写在第一行，同时给style标签加入lang="scss"属性 */
	@import "~uview-ui/theme.scss";
</style>
