<template>
    <Newsletter id="newsletter"/>
</template>

<script>
    export default {
        data(){
            title: 'Newsletter page'
        },
        head() {
        return {
            title: this.title,
            meta: [
            {
                hid: 'newsletter',
                name: 'Techy Inc. Newsletter page',
                content: 'Newsletter page'
            }
            ]
        }
        }
    }
</script>