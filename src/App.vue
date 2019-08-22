<script>
  import Clock from "@/components/Clock"

  export default {
    components: {
      Clock
    },
  }
</script>

<template>
  <div>
    <Clock class="clock" location="TOKYO" v-bind:diff="0"/>
    <Clock class="clock" location="NY" v-bind:diff="-14"/>
    <Clock class="clock" location="LA" v-bind:diff="-17"/>
    <Clock class="clock" location="UK" v-bind:diff="-9"/>
    <Clock class="clock" location="BRAZIL" v-bind:diff="-12"/>
    <Clock class="clock" location="DUBAI" v-bind:diff="-5"/>
    <Clock class="clock" location="JOHANNESBURG" v-bind:diff="-7"/>
  </div>
</template>


<style scoped>
  .clock {
    width: 80%;
    max-width: 500px;
    margin: 30px auto;
  }
</style>

<style>
  html {
    font-size: 62.5%;
  }

  body {
    margin: 0;
  }

  p {
    margin: 0;
  }
</style>
