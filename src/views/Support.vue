<template>
    <div class="content">
        <Header />
        <h1>Support</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eligendi, illo? Eligendi vel obcaecati adipisci atque, veritatis quidem beatae enim fugit.</p>
        <Test />
    </div>
</template>

<script>
import Test from '@/components/Test.vue'
import Header from '../components/Header.vue'

export default {
    name: 'support',
    components: {
        Test,
        Header
    }
}
</script>

<style lang="sass" scoped>

.content 
    h1 
        font-size: 40px
    p 
        line-height: 2rem
</style>