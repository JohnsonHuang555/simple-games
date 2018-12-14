<template>
  <v-container grid-list-lg>
    <v-layout wrap row>
      <v-flex xs3>
        <game />
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
import Game from '@/components/Game'

export default {
  components: {
    Game
  }
}
</script>

<style lang="scss" scoped>
* {
  border: 1px solid;
}
</style>
