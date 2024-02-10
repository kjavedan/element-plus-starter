<template>
  <div>
    <el-button type="primary" @click="toggleDark()">
      <div
        class="i-twemoji-grinning-face-with-smiling-eyes mr-1 hover:i-twemoji-face-with-tears-of-joy"
      />

      click
    </el-button>
  </div>
</template>

<script setup lang="ts">
import { toggleDark } from "~/composables";
</script>

<style lang="scss" scoped></style>
