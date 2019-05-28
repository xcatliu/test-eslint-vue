<!-- bad 语法错误的 v-bind -->
<template>
  <div>
    <div v-bind />
    <div :aaa />
    <div :aaa.bbb="foo" />
  </div>
</template>
