<template>
  <div class="container">
      <button>about</button>
      <img src="@/assets/codeinthewoodslogo.png"/>
      <button>patreon</button>
  </div>
</template>

<script>
export default {
  name: 'Navigation'
}
</script>

<style scoped>
  .container {
    display: flex;
    gap: 12%;
    justify-content: center;
    align-items: center;
    align-content: center;
  }
  .link {
    object-fit: contain;
    max-height: 20%;
  }
  img {
    object-fit: contain;
    max-height: 65%;
  }
  button {
    background-color: transparent;
    color: #14110f;
    border-color: transparent;
    font: 18px Avenir, sans-serif;
    font-weight: bold;
    transition: 0.5s ease-in;
  }
  button:hover {
    color: #70A9A1;
    transform: scale(110%, 110%);
    cursor: pointer;
  }
</style>