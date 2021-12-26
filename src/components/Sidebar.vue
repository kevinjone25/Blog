<template>
    <div>
        <h1 class="intro">
            {{ name }}
        </h1>
    </div>
</template>

<script>
export default {
    name: "sidebar",
    props: {
        name : String,
    }
};
</script>

<style>
</style>
