<template>
  <div class="container" id="app">
    <div class="header">
      <h1 class="page-title">DIY electric longboard</h1>
    </div>

    <div class="section row">
      <div class="col-8">
        <img class="img-fluid" src="http://via.placeholder.com/600x250">
      </div>

      <div class="col-4">
        <h1 class="timberframing">Intro</h1>
        <p>
          This page is a combination of a journal and notes I took while building an electric longboard
        </p>
      </div>
    </div>

    <parts></parts>
    <hr/>
    <journal></journal>
    <hr/>
    <board></board>
    <hr/>
    <mount></mount>
    <hr/>
    <motor></motor>
    <hr/>
    <battery></battery>
    <hr/>
    <journalp></journalp>
  </div>
</template>

<script>
import Parts    from "./sections/Parts.vue"
import Journal  from "./sections/Journal.vue"
import Board    from "./sections/Board.vue"
import Motor    from "./sections/Motor.vue"
import Mount    from "./sections/MountPulleyBelt.vue"
import Battery  from "./sections/Battery.vue"
import JournalP from "./sections/JournalPic.vue"

export default {
  name: 'app',
  components: {
    "parts": Parts,
    "journal": Journal,
    "board": Board,
    "motor": Motor,
    "mount": Mount,
    "battery": Battery,
    "journalp": JournalP,
  },
}
</script>

<style>@import './assets/css/home.css'</style>
