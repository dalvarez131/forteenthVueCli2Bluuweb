<template>
  <div  class="text-center mt-3">
    <button class="btn btn-outline-danger btn-lg" @click="reset()">Reset</button>
  </div>
</template>

<script>
import { mapState, mapMutations } from 'vuex';

export default {
  name: 'ResetButton',
  computed: {
    ...mapState(['frutas'])
  },
  methods: {
    ...mapMutations(['reset'])
  }
}
</script>
