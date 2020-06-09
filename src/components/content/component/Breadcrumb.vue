<template>
  <div class="pl-15 pb-40 pt-32">
    <p class="mb-0 d-flex align-items-center">
      <img
        src="./../../../assets/home-icon@2x.png"
        alt="home"
        class="home_icon"
      />
      <span class="slash px-3">/</span>
      <span class="navigation-title">Profile</span>
    </p>
  </div>
</template>
<script>
export default {
  name: 'Breadcrumb'
}
</script>
<style scoped>
.pl-30 {
  padding-left: 30px;
}
.pl-15 {
  padding-left: 15px;
}
.pt-32 {
  padding-top: 32px;
}
.pb-40 {
  padding-bottom: 40px;
}
.home_icon {
  width: 18px;
  height: 16px;
  object-fit: contain;
}
.slash {
  width: 7px;
  height: 20px;
  font-family: Roboto;
  font-size: 18px;
  font-weight: 500;
  font-stretch: normal;
  font-style: normal;
  line-height: normal;
  letter-spacing: normal;
  color: #6d6d6d;
}
.navigation-title {
  width: 52px;
  height: 18px;
  font-family: Roboto;
  font-size: 18px;
  font-weight: normal;
  font-stretch: normal;
  font-style: normal;
  line-height: 1;
  letter-spacing: normal;
  color: #1a1a1a;
}
</style>
