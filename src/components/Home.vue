<template>
  <div id="app">
    <b-switch v-model="switchState">{{ switchState }}</b-switch>
    <hr>

    <b-checkbox v-model="checkboxState">{{ checkboxState }}</b-checkbox>
    <hr>

    <button class="button is-primary" @click="$toast.open('This is a Toast')">
      Show Toast
    </button>
    <button class="button is-primary" @click="$snackbar.open('This is a Snackbar')">
      Show Snackbar
    </button>
    <hr>

    <b-field>
      <b-input maxlength="25" placeholder="Your name"></b-input>
    </b-field>
  </div>
</template>

<script>
export default {
  name: 'home',
  data () {
    return {
      switchState: true,
      checkboxState: true
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
