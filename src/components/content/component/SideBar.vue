<template>
  <div class="sidebar">
    <div class="title pl-20 d-flex align-items-center font-size-16">
      <span>
        TABLE OF CONTENTS
      </span>
    </div>
    <div class="content p-20">
      <p class="pb-3 mb-0 color-blue">Demoghraphics</p>
      <p class="mb-0 pb-3 color-silver">Major Medical Journeys</p>
      <div class="pl-12">
        <p class="mb-0 pb-2 color-blue">Other (xxxx-xxxx)</p>
        <p class="mb-0 pb-2 color-blue">Other (xxxx-xxxx)</p>
        <p class="mb-0 pb-2 color-silver">Major Medical Journeys</p>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'SideBar'
}
</script>
<style scoped>
.pl-20 {
  padding-left: 20px;
}
.p-20 {
  padding: 20px;
}
.pl-12 {
  padding-left: 12px;
}
.sidebar {
  width: 270px;
  height: 567px;
  border-radius: 3px;
  border: solid 1px #ebf5ff;
  background-color: #ffffff;
}
.sidebar .title {
  width: 100%;
  height: 40px;
  border-radius: 3px;
  background-color: #daebff;
}
.sidebar .title span {
  font-size: 16px;
  font-weight: 500;
  color: #4a4a4a;
}

.content p {
  font-size: 16px;
}
.color-blue {
  color: #1976d2;
}
.color-silver {
  color: #616161;
}
</style>
