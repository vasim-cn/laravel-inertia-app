<template>
    <h1>Home</h1>
    <Nav></Nav>
</template>
<script>
import Nav from '../Shared/Nav'
export default {
    props: {
        name: String,

    },
    components:{Nav}
};
</script>
