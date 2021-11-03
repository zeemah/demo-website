<template>
    <About id="about"/>
</template>

<script>
    export default {
        data(){
            title: 'About us page'
        },
        head() {
        return {
            title: this.title,
            meta: [
            {
                hid: 'about-us',
                name: 'Techy Inc. About us page',
                content: 'About us page'
            }
            ]
        }
        }
    }
</script>