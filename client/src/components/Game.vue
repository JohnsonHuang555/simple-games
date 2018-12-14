<template>
  <div class="elevation-5">
    <img width="100%" src="https://images.pexels.com/photos/209728/pexels-photo-209728.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" alt="game">
    <h2>終極密碼</h2>
    <p>每個人隨便猜一個數字</p>
    <v-btn @click="play">Play</v-btn>
  </div>
</template>

<script>
export default {
  data() {
    return {
      game: {
        id: 1
      }
    }
  },
  methods: {
    play() {
      this.$router.push('/games/' + this.game.id)
    }
  }
}
</script>

<style>

</style>
