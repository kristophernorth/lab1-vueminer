<script setup>
// import { computed } from 'vue';
// import { AppState } from './AppState';

// const cheese = computed(() => AppState.cheese)

</script>

<template>
  <header>
    <h1 class="text-center">Moon Miner</h1>
  </header>
  <main>
    <section class="contain-fluid">
      <div class="row">
        <div class="col text-center">
          <img role="button" src="https://jeremy-fowler.github.io/moon_miner/assets/img/Moon.svg" alt="" title="Click to mine!">
        </div>
      </div>
    </section>
    <section class="container-fluid">
      <div class="row text-center d-flex justify-content-center border">
        <div class="col-1">+1 👆</div>
        <div class="col-3">🧀 7</div>
        <div class="col-1">⏰ +0</div>
      </div>
      <div class="row d-flex justify-content-center border">
        <div class="col-6">
          <div class="row">
            <div class="col-6">
              <h4>Click Upgrades</h4>
              <p><span>50 🧀</span><span>Knife +1</span></p>
              <p><span>250 🧀</span><span>Drill +5</span></p>
            </div>
            <div class="col-6">
              <h4>Automatic Upgrades</h4>
              <p><span>1000 🧀</span><span> Mousetronaut +10/3s</span></p>
              <p><span>50000 🧀</span><span> Space Station +1--/3s</span></p>
            </div>
          </div>
        </div>
        <div class="col-6">
          <div class="row">
            <div class="col-6">
              <h4>Click Stats</h4>
              <p><span>0</span><span> Knife → </span><span>0</span></p>
              <p><span>0</span><span> Drill → </span><span>0</span></p>
            </div>
            <div class="col-6">
              <h4>Automatic Stats</h4>
              <p><span>0</span><span> Mousetronaut ⏰ </span><span>0</span></p>
              <p><span>0</span><span> Space Station ⏰ </span><span>0</span></p>
            </div>
          </div>
        </div>
      </div>
    </section>
  </main>
  <footer>
  </footer>
</template>

<style lang="scss">
@import '@/assets/scss/main.scss';
:root {
  --main-height: calc(100vh - 32px - 64px);
}

footer {
  display: grid;
  place-content: center;
  height: 32px;
}
</style>
