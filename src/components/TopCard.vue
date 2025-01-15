<template>
    <div class="card">
      <slot></slot>
    </div>
  </template>
  
  <script>
  export default {
    name: 'TopCard',
  };
  </script>
  
  <style scoped>
  .card {
    background-color: #011F35;
    border-radius: 16px;
    padding: 20px 24px;
  }
  </style>
  