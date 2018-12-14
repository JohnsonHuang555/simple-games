<template>
  <v-container>
    <v-layout>
      <v-flex xs3>
        <v-text-field
        v-model="answer"
        placeholder="Your answer">
        </v-text-field>
        <v-btn color="primary" @click="guess">Guess</v-btn>
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
export default {
  data() {
    return {
      answer: ''
    }
  },
  methods: {
    guess() {
      
    }
  }
}
</script>

<style>

</style>
