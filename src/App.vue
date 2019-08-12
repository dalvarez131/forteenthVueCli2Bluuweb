<template>
  <div id="app" class="container">
    <Cabecera/>
    <Lista/>
    <ResetButton/>
  </div>
</template>

<script>
import Cabecera from './components/Cabecera'
import Lista from './components/Lista'
import ResetButton from './components/ResetButton'

export default {
  name: 'app',
  components: {
    Cabecera,
    Lista,
    ResetButton
  }
}
</script>

<style>

</style>
