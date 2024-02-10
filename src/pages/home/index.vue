<template>
  <div>
    <el-button type="primary" @click="toggleDark()">switch</el-button>
  </div>
</template>

<script setup lang="ts">
import { toggleDark } from "~/composables";
</script>

<style lang="scss" scoped></style>
