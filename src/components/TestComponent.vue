<template>
    <div id="product">
        {{ testmsg }}
        <ul>
            <li></li>
            <li></li>
            <li></li>
        </ul>
    </div>
</template>

<script>
export default {
    name: "TestComponent",
    props:{
        testmsg: String
    }
}
</script>

<style>

</style>

