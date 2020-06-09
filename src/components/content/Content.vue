<template>
  <div>
    <div class="row mx-0">
      <div class="col-md-12">
        <Breadcrumb />
      </div>
    </div>
    <div class="row mx-0 pl-15">
      <div class="col-md-4 pr-45"><SideBar /></div>
      <div class="col-md-8 pl-45"><ContentBar /></div>
    </div>
  </div>
</template>
<script>
import Breadcrumb from './component/Breadcrumb'
import SideBar from './component/SideBar'
import ContentBar from './component/ContentBar'
export default {
  name: 'Content',
  components: {
    Breadcrumb,
    SideBar,
    ContentBar
  }
}
</script>
<style scoped>
.pl-15 {
  padding-left: 15px;
}
.pr-45 {
  padding-right: 45px;
}
.pl-45 {
  padding-left: 45px;
}
</style>
