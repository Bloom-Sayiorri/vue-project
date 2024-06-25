<template>
  <div class="about">
    <h1>This is an about page</h1>
    <p>The about page inludes some information about my current project.</p>
  </div>

  <div class="container">
    <p>Second paragraph.</p>
  </div>
</template>

<style>
.about, .container {
  color: bisque;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  line-height: 4em;
  margin-top: .7rem;
}

@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
