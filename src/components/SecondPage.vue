<template>
    <div>
      <h1> Second Page </h1>
    </div>
  </template>
  
  <script>
  export default {
    name: 'SecondPage',
    mounted() { 
    this.emitter.on("toggle-sidebar", () => {
      console.log('triggered');
    });
  }

  }
  </script>
  
  