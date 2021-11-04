<template>
    <!-- HTML 코드 -->
    
    <div>
        {{ page_string }}
        <v-link href="/welcome">Go Welcome Page</v-link>
    </div>
</template>


<script>
import VLink from './VLink.vue'


// javascript 코드
export default {
    components: { VLink },
    name: 'About',
        data() {
        return {
            page_string: '현재 About page 입니다.'
        }
    },
    method: {
        
    }
}

</script>

<style scoped>
/* style 코드 */
    div {
        color: red;
    }
</style>
