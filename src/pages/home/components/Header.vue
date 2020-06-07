<template>
  <div class="header">
    <van-nav-bar
      title=""
      left-arrow
    >
    <template #title>
      <div>
        <van-search placeholder="请输入搜索关键词" />
      </div>
    </template>
    <template #right>
      <div>
        天津
      <van-icon name="arrow-down" />
      </div>
    </template>
    </van-nav-bar>
  </div>
</template>

<script>
export default {
}
</script>

<style lang="stylus" scoped>
</style>