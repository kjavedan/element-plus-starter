<template>
  <div>
    <el-button type="primary" @click="toggleDark()">switch</el-button>
  </div>
</template>

<script setup>
import { toggleDark } from "~/composables";
</script>

<style lang="scss" scoped></style>
