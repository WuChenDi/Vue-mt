<template>
  <div class="search-panel">
    <el-row class="m-header-searchbar">
      <el-col
        :span="3"
        class="left"
      >
        <img
          src="//s0.meituan.net/bs/fe-web-meituan/e5eeaef/img/logo.png"
          alt="美团"
        >
      </el-col>
      <el-col
        :span="15"
        class="center"
      >
        2
      </el-col>
      <el-col
        :span="6"
        class="right"
      >
        <ul class="security">
          <li><i class="refund" />
            <p class="txt">随时退</p>
          </li>
          <li><i class="single" />
            <p class="txt">不满意免单</p>
          </li>
          <li><i class="overdue" />
            <p class="txt">过期退</p>
          </li>
        </ul>
      </el-col>
    </el-row>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
</style>
