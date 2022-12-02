<script>
  import Card from './components/Card.svelte'
</script>

<div class="app center">
  <Card />
</div>

<style>
  .app {
    height: 100vh;
    margin: 10rem 0 10rem 0;
  }

  @media (min-width: 1440px) {
    .app {
      margin: 0;
    }
  }
</style>
