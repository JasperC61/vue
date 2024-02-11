<script setup>
  
  let message="<u>hello Vue</u>";
  let checked=true;
  
</script>

<template>
     <nav>基本導覽列</nav>
     <main v-html="message.toUpperCase()"></main>
     <div :class="checked?'dark':'light'">操作標籤屬姓</div>
    
</template>

<style scoped>
    main{background-color:#dddddd;}
    
    .dark{color:#333333}
    .light{color:#888888}
</style>
