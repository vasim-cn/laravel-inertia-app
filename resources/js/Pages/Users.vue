<template>
    Users
    <Nav/>

    <div class="" style="margin-top:800px;">
        <p>The current time is {{ time }}.</p>
    </div>
    <Link href="/users" preserve-scroll>Refresh</Link>
</template>

<script>
import Nav from "../Shared/Nav"
import {Link} from "@inertiajs/inertia-vue3"

export default {
    name: "Users",
    components: {Nav, Link},
    props: {
        time: String,
    }
}
</script>

<style scoped>

</style>
