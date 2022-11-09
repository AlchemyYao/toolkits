<template>
    <el-container>
        <el-container>
            <el-aside style="background-color:yellow" id="layout-aside">Aside</el-aside>
            <el-aside style="background-color:gray">A</el-aside>
            <el-main style="background-color:blue">Main</el-main>
        </el-container>
        <el-footer style="background-color:green"></el-footer>
    </el-container>
</template>

<script setup lang="ts">
import { RouterView } from 'vue-router'
</script>
<style scoped lang="scss">
.el-container {
    height: 100%;
}
.el-footer {
    background-color: rgb(77, 77, 75);
    height: 20px;
}
#layout-aside {
    width: 55px;
}
</style>