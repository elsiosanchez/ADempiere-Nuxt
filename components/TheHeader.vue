<template>
  <div>
    {{ count }} <br>
    <el-input-number v-model="count" :min="1" :max="10" />
    <hr>
  </div>
  <!-- <h1> The_Header1 </h1> -->
   <!-- <br> -->
  <!-- <el-input-number v-model="count" :min="1" :max="10" /> -->
</template>

<script setup lang="ts">
import { ElInputNumber } from "element-plus";
const count = 0;
// import {
//   ElButton
// } from "element-plus";
const buttons = [
  { type: '', text: 'plain' },
  { type: 'primary', text: 'primary' },
  { type: 'success', text: 'success' },
  { type: 'info', text: 'info' },
  { type: 'warning', text: 'warning' },
  { type: 'danger', text: 'danger' },
];

</script>
