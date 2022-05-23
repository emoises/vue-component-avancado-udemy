<template>
  <div id="app">
   <PostAtom>
      
   </PostAtom>
  </div>
</template>

<script>
import PostAtom from "./components/molecules/PostAtom.vue"
export default {
  name: 'App',
  data() {
    return{
      title: "Eduardo Moisés da Silva"
    }
  },
  components: {
    PostAtom
  },
}
</script>