<template>
    <div id="app">
        <img alt="Vue logo" src="./assets/logo.png">
        <a-button type="primary">这是一个按钮</a-button>
        <!--    使用组件-->
        <HelloWorld msg="犯我中华者虽远必诛" country="中国"/>
    </div>
</template>

<script>
    import HelloWorld from './components/HelloWorld.vue'

    export default {
        name: 'App',
        components: {  // 引入组件
            HelloWorld
        }
    }
</script>

<style>
    #app {
        font-family: Avenir, Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
        margin-top: 60px;
    }
</style>
