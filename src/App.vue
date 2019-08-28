<template>
  <div id="app">
    <Home/>
    <Payment/>
    <AccountDetails/>
  </div>
</template>

<script>
import Home from './components/Home.vue'
import AccountDetails from './components/AccountDetails.vue'
import Payment from './components/Payment.vue'

export default {
  name: 'app',
  components: {
    Home,
    Payment,
    AccountDetails
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
