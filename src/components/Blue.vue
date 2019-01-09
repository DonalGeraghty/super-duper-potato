<template>
    <div class="blue">
        <h5 class=""> {{message}} </h5>
    </div>
</template>

<script>
export default {
    name: 'Blue',
    props: {
        message: String
    }
}
</script>

<style>
h5 {
    background-color: blue;
}
</style>
