<template>
  <div class="container">
    <div>
      <Logo />
      <h1 class="title">
        tailwind-playgrnd
      </h1>
      <div>
          <ul class="flex justify-center">
            <a href="" class="bg-gray-300 text-sm py-1 px-3 rounded-full">Music Player</a>
          </ul>
      </div>
    </div>
  </div>
</template>

<script>
  export default {}

</script>

<style>
  /* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
  .container {
    margin: 0 auto;
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
  }

  .title {
    font-family:
      'Quicksand',
      'Source Sans Pro',
      -apple-system,
      BlinkMacSystemFont,
      'Segoe UI',
      Roboto,
      'Helvetica Neue',
      Arial,
      sans-serif;
    display: block;
    font-weight: 300;
    font-size: 42px;
    color: #35495e;
    letter-spacing: 1px;
  }

  .subtitle {
    font-weight: 300;
    font-size: 24px;
    color: #526488;
    word-spacing: 5px;
    padding-bottom: 15px;
  }

  .links {
    padding-top: 15px;
  }

</style>
