<template>
    <Team  id="team"/>
</template>

<script>
    export default {
        data(){
            title: 'Team page'
        },
        head() {
        return {
            title: this.title,
            meta: [
            {
                hid: 'team',
                name: 'Techy Inc. Team page',
                content: 'Team page'
            }
            ]
        }
        }
    }
</script>