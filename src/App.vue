<template>
  <div id="app">
    <Home />
  </div>
</template>

<script>
import Home from './components/Home'
export default {
  name: 'App',
  components: {
    Home
  }
}
</script>

<style>
#app {
  /* font-family: Roboto; */
  /* -webkit-font-smoothing: antialiased; */
  /* -moz-osx-font-smoothing: grayscale; */
}
.font-size-20 {
  font-size: 20px;
}
.pl-30 {
  padding-left: 30px;
}
.modal-dialog .modal-content .modal-header .close:focus {
  outline-width: 0px;
}
.modal-dialog .modal-content .modal-header {
  display: flex;
  align-items: center;
  height: 30px;
  padding-left: 30px;
  padding-bottom: 0px;
  padding-top: 0px;
  background-color: #ecf5ff !important;
  border: none;
}
.modal-dialog .modal-content .modal-header .close {
  padding: 0px;
  margin: 0px;
}
.modal-dialog .modal-content .modal-footer {
  display: none;
}
.modal-header h5 {
  font-size: 16px;
}
.modal-dialog .modal-content .modal-body {
  padding-left: 0px;
}
</style>
