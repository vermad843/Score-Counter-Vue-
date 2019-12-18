<template>
  <div id="app" class = "container">
     <h1 class = "text-center">Player Score Counter </h1>
    <div class="card" >
      <div class="card-body text-center">
        <h3>Player 1</h3>
        <button type= "button" class = "btn btn-danger">Down</button>
        <span class = "player-score">0</span>
        <button type= "button" class = "btn btn-success">Up</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {

    }
  }
}
</script>

<style>
  .player-score {
    font-size : 4em;
  }
</style>
