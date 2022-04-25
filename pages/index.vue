<script setup>
  const version = 2 + 1
</script>

<template>
<div id="page">
  <NuxtLayout name="custom">
  <div class="hello">
    <h1>Hello Nuxt {{ version }}!</h1>
  </div>
  </NuxtLayout>
</div>
</template>

<style>
html, body {
    margin: 0;
}
.hello { 
  display:flex;
  align-items:center;
  min-height: 300px;
	background-color: MintCream; 
	} 
.hello h1 {
  text-transform: uppercase;
  letter-spacing: .2rem;
  margin: auto;
}

</style>


