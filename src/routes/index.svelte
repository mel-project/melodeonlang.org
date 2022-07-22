<script lang="ts">
  import Playground from "../components/Playground.svelte";
</script>

<template>
  <!-- some sort of header here -->
  <div class="container">
    <div class="row section section-invert">
      <div class="col">
        <h1 class="hero-text">
          A user-friendly functional programming language for Themelio covenant
          logic.
        </h1>
        <button class="btn btn-lg btn-outline-primary">Get started</button>
      </div>
    </div>
    <div class="row section">
      <div class="col">
        <h2>Try Melodeon</h2>
        <Playground />
      </div>
    </div>
    <div class="row section">
      <div class="col">
        <h2>Melodeon is in early alpha and changing rapidly</h2>
        <p>
          As a newly released language, Melodeon is still growing and evolving.
          While the core language is stable, more advanced details such as
          generic types and modules are subject to breaking change.
        </p>
        <p>The documentation describes the current</p>
        <p>
          You can follow the list of issues and planned changes on the <a
            href="https://github.com/themeliolabs/melodeon/issues"
            >GitHub issue tracker</a
          >
        </p>
      </div>
    </div>
  </div>
</template>

<style>
  .container {
    max-width: 1024px;
  }

  .section {
    margin-top: 3rem;
    margin-bottom: 3rem;
  }
  .hero-text {
    font-size: 3rem;
    font-weight: 300;
    margin-bottom: 2rem;
  }

  p {
    font-size: 110%;
  }
</style>
