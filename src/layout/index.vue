<template>
    <el-container>
        <el-container>
            <el-aside>Aside</el-aside>
            <el-main>Main</el-main>
        </el-container>
        <el-footer></el-footer>
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
</style>