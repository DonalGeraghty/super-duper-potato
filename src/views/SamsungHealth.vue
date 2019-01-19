<template>
    <div>
        <div v-for="data in myJson" :key="data.start_time">{{data}}</div>
    </div>
</template>

<script>
import json from '../json/data.json'

export default{
    data(){
        return{
            myJson: json
        }
    }
}
</script>

<style>

</style>
