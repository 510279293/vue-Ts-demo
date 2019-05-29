<template>
    <div class="app">
       {{msg}}
    </div>
</template>
<script lang="ts">
import {Vue, Component } from 'vue-property-decorator'
// import {Getter, Mutation } from 'vuex-class'
@Component
export default class App extends Vue{
   msg: string = 'zyy, i love you' 
}
</script>
<style lang="less" scoped>
   .app{
       color:pink;
   }
</style>
