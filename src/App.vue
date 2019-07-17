<template>
  <div id="app">
    <eHeader>
    </eHeader>
    <Timer></Timer>
    <eBody>
      
    </eBody>
    <eFooter></eFooter>

  </div>
</template>

<script>
import eHeader from './components/eHeader.vue'
import eBody from './components/eBody.vue'
import eFooter from './components/eFooter.vue'
import Timer from './components/Timer.vue'

export default {
  
  components: {
    'eHeader': eHeader,
    'eBody': eBody,
    'eFooter': eFooter,
    'Timer': Timer
  },
  
}

</script>

<style>
body {
  text-align: center;
}



</style>
