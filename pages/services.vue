<template>
    <Services id="services"/>
</template>

<script>
    export default {
        data(){
            title: 'Service page'
        },
        head() {
        return {
            title: this.title,
            meta: [
            {
                hid: 'service',
                name: 'Techy Inc. Service page',
                content: 'Service page'
            }
            ]
        }
        }
    }
</script>