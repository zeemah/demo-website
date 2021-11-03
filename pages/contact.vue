<template>
    <Contact  id="contact"/>
</template>
<script>
    export default {
        data(){
            title: 'Contact us page'
        },
        head() {
        return {
            title: this.title,
            meta: [
            {
                hid: 'contact-us',
                name: 'Techy Inc. Contact us page',
                content: 'Contact us page'
            }
            ]
        }
        }
    }
</script>