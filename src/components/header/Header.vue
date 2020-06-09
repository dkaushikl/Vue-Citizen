<template>
  <div class="row mx-0">
    <div
      class="header col-md-12 d-flex align-items-center justify-content-between"
    >
      <div class="d-flex header-content">
        <img src="./../../assets/logo.png" alt="Ciitizen" class="logo" />
        <p class="mb-0 font-size-20 site-title">Ciitizen</p>
      </div>
      <div class="search-wrapper  pl-4">
        <div class="search">
          <img
            src="./../../assets/search.png"
            alt="search"
            class="search-icon"
          />
          <input
            type="search"
            placeholder="Search"
            class="search-textbox pl-3"
          />
        </div>
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
.search-wrapper {
  width: 301px;
  height: 44px;
  margin-right: 192px;
  border-radius: 24px;
  background-color: #eeeeee;
}
.search {
  height: 100%;
  flex-direction: row;
  box-sizing: border-box;
  display: flex;
  place-content: center flex-start;
  align-items: center;
  flex: 1 1 0%;
}
.search-icon {
  height: 15px;
  width: 15px;
}
.search-textbox {
  font-size: 16px;
  border: none;
  background-color: #eeeeee;
  color: #6d6d6d;
  height: 14px;
  width: 100%;
  padding-right: 8px;
}
.search-textbox:focus {
  outline-width: 0px;
}
</style>
