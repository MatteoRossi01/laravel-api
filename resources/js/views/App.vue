<template>
    <div class="app">

        <Header/>
        <Main/>

    </div>
</template>


<script>
import Header from '../components/MyHeader.vue';
import Main from '../components/MyMain.vue';

export default{
    name: 'App',
    components: {
    Header,
    Main
  },
}
</script>

<style lang="scss" scoped>

</style>


