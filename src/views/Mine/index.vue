<template>
    <div id="main">
        <Header title="我的神影"></Header>
        <div id="content">
            <Login></Login>
        </div>
        <TabBar></TabBar>
    </div>
</template>
<script>
    import Header from '../../components/Header';
    import TabBar from '../../components/TabBar';
    import Login from '../../components/Login';
    export default {
        name:'Mine',
        components:{
            Header,
            TabBar,
            Login
        }
    }
</script>
<style scoped></style>