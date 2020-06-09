<template>
  <div class="row mx-0">
    <div
      class="header col-md-12 d-flex align-items-center justify-content-between"
    >
      <div class="d-flex header-content">
        <img src="./../../assets/logo.png" alt="Ciitizen" class="logo" />
        <p class="mb-0 font-size-20 site-title">Ciitizen</p>
      </div>
      <div>
        <input type="text" placeholder="serch" class="serch-box" />
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'Header'
}
</script>
<style scoped>
.header-content {
  padding: 19px 0px 19px 15px;
}
.header {
  border-bottom: solid 1px #e5e5e5;
  background-color: #ffffff;
}
.logo {
  width: 34px;
  height: 34px;
  padding-right: 12px;
}
.site-title {
  font-weight: normal;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.5;
  letter-spacing: normal;
  color: #1a98e8;
}

.serch-box {
  width: 301px;
  height: 44px;
  border-radius: 24px;
  background-color: #eeeeee;
}
</style>
