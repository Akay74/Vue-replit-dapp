<template>
  <div>
    <div>
      <div>
        Hello There!!!
      </div>
      <div>My name is Akay and I've built my first blockchain app. Connect your ethereum wallet</div>
      <button class="cta-button connect-wallet-button"  @click="connect">
        Connect Wallet To Get Started
      </button>
    </div>
  </div>
</template>

<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>