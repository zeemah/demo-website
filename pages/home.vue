<template>
    <Home id="home"/>
</template>
<script>

export default {
    data(){
        title: 'Home page'
    },
      head() {
      return {
        title: this.title,
        meta: [
          {
            hid: 'home',
            name: 'Techy Inc. Home page',
            content: 'Home page'
          }
        ]
      }
    }
}
</script>