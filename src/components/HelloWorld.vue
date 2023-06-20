<template>
  <div>
    <h1>First Page </h1>
    <button @click="triggerEvent">Event</button>  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  methods: {
    triggerEvent(){
      this.emitter.emit("toggle-sidebar", this.sidebarOpen);
    }
  }
}
</script>

