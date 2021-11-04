<template>
    <div>
        {{ page_string }}
        <v-link href="/about">Go ABOUT Page</v-link>
    </div>
</template>


<script>
import VLink from './VLink.vue'


export default {
  components: { VLink },
    name: 'Welcome',
    data() {
        return {
            page_string: '현재 Welcome page 입니다.'
        }
    },
    
    methods: {

    }
}

</script>

<style scoped>
    div {
        color: green;
    }
</style>
