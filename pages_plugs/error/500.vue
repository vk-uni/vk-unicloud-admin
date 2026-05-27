<template>
  <div class="page-body">
    <image src="../../static/icon/icon-500.svg"></image>
    <div class="title">
      <span class="code">500</span>
      <span class="tips">抱歉，服务器出错了</span>
      <span class="tips">{{ errMsg }}</span>
      <span class="btn" @tap="toHome">返回首页</span>
    </div>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        errMsg: '',
      };
    },
    onLoad(query) {
      this.errMsg = query.errMsg || '';
    },
    methods: {
      toHome() {
        uni.vk.navigateToHome();
      },
    },
  };
</script>

<style lang="scss" scoped>
  page {
    width: 100%;
    height: 100%;
    background-color: #f5f7f9;
  }
  .page-body {
    display: flex;
    padding-top: 250rpx;
    justify-content: center;

    .title {
      display: flex;
      flex-direction: column;
      padding-top: 120rpx;
      margin-left: 200rpx;
    }
    .code {
      margin-bottom: 24px;
      color: #515a6e;
      font-weight: 600;
      font-size: 72px;
      line-height: 72px;
    }
    .tips {
      margin-bottom: 16px;
      color: #808695;
      font-size: 20px;
      line-height: 28px;
    }
    .btn {
      display: inline-block;
      color: #fff;
      background-color: #2d8cf0;
      border-color: #2d8cf0;
      width: 200rpx;
      height: 85rpx;
      border-radius: 6rpx;
      text-align: center;
      line-height: 85rpx;
    }
    .btn:hover {
      cursor: pointer;
      background-color: #57a3f3 !important;
    }
  }
</style>
