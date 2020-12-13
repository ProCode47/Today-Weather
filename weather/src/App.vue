<template>
<div>
  <Header/>
  <Search/>
  <Content/>
</div>
</template>

<script>
import Header from "./components/Header"
import "./components/styles/main.css"
import Content from "./components/Content"
import Search from "./components/Search"
export default {
  name: 'App',
  components: {
    Header,
    Content,
    Search
  }
}
</script>


