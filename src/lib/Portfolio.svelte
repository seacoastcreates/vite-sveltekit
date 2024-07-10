<script>
</script>

<div class="flexbox">
  <div class="flex-card">
    <img src="../src/assets/WordPress-logotype-wmark.png" alt="" />
  </div>
  <div class="flex-card"><img src="../src/assets/jam.webp" alt="" /></div>
  <div class="flex-card"><img src="../src/assets/aws-logo.svg" alt="" /></div>
</div>

<style>
  .flexbox {
    display: flex;
    align-items: center;
    flex-direction: column;
  }
  .flex-card {
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 0.2em;
    height: 300px;
    width: 280px;
  }
  .flex-card img {
    max-width: 220px;
  }
  @media (min-width: 900px) {
    .flexbox {
      display: flex;
      justify-content: space-evenly;
      flex-direction: row;
    }
    .flex-card {
      display: flex;
      align-items: center;
      justify-content: center;
      flex-basis: 30%;
      padding: 0.2em;
      height: 300px;
      width: 280px;
      background: transparent;
      /* box-shadow: 33px 26px 42px 6px rgba(127, 127, 127, 0.5); */
    }
    .flex-card img {
      display: flex;
      align-items: center;
      justify-content: center;
      max-width: 220px;
      /* box-shadow: 10px 10px 10px 6px rgba(127, 127, 127, 0.5); */
    }
  }
</style>
