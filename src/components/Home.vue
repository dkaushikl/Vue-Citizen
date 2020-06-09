<template>
  <div class="container1">
    <Header />
    <Content />
  </div>
</template>
<script>
import Header from './header/Header'
import Content from './content/Content'
export default {
  name: 'Home',
  components: {
    Header,
    Content
  }
}
</script>
