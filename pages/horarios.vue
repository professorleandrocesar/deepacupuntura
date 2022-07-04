<template>
<div id='app'>
  <NavTop/>
  
  <NavBottom/>
    <Agenda/>
</div>  


</template>

<script>
export default {
  scrollToTop: true,
    head: {
    title: 'Horários | Deep Acupuntura',
    meta: [
      {
        hid: 'description',
        name: 'description',
        content: ''
      },
      {
        hid: 'keywords',
        name: 'keywords',
        content: 'Acupuntura'
      }
    ]
  }
}
</script>
<style scoped>
 th, td, tr{
  white-space: nowrap;
}
</style>