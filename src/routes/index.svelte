<script lang="ts">
  import Playground from "../components/Playground.svelte";
</script>

<svelte:head>
  <title>Melodeon</title>
</svelte:head>

<template>
  <nav class="navbar navbar-light bg-light">
    <div class="container">
      <b class="navbar-brand">Melodeon</b>
      <ul class="nav justify-content-end">
        <li class="nav-item mx-3"><a href="/">Home</a></li>
        <li class="nav-item mx-3">
          <a href="https://guide.melodeonlang.org">Guide</a>
        </li>
        <li class="nav-item mx-3">
          <a href="https://github.com/themeliolabs/melodeon">GitHub</a>
        </li>
      </ul>
    </div>
  </nav>
  <!-- some sort of header here -->
  <div class="container">
    <div class="row section section-invert">
      <div class="col">
        <h1 class="hero-text">
          A user-friendly functional programming language for Themelio covenant
          logic.
        </h1>
        <a
          href="https://guide.melodeonlang.org"
          class="btn btn-lg btn-outline-primary"
          rel="noreferrer"
          target="_blank">Get started</a
        >
      </div>
    </div>
    <div class="row section">
      <div class="col">
        <h2>Try Melodeon here.</h2>
        <p>
          Interact with and test Melodeon covenants right from your browser! You
          can also
          <a
            href="https://play.melodeonlang.org"
            rel="noreferrer"
            target="_blank"
          >
            open the playground separately.
          </a>
        </p>
        <Playground />
      </div>
    </div>
    <div class="row section">
      <div class="col">
        <h2>Melodeon is in early alpha and changing rapidly.</h2>
        <p>
          As a newly released language, Melodeon is still growing and evolving.
          While the core language is stable, more advanced details such as
          generic types and modules are subject to breaking change.
        </p>
        <p>
          The <a href="https://guide.melodeonlang.org">Melodeon Guide</a> is a best-effort
          documentation of the language as it currently exists.
        </p>
        <p>
          You can follow the list of issues and planned changes on the <a
            href="https://github.com/themeliolabs/melodeon/issues"
            >GitHub issue tracker</a
          >.
        </p>
      </div>
    </div>
    <div class="row section text-center">
      <div class="col-lg" />
      <div class="col-8">
        <h2>Join our community!</h2>
        <p>
          You can join the Melodeon chat room through <a
            href="https://discord.gg/BHhea9tVPP">Discord</a
          >
          or
          <a href="https://matrix.to/#/#melodeon:matrix.themelio.org">Matrix</a>
          to ask questions about Melodeon and connect with other devs.
        </p>
      </div>
      <div class="col-lg" />
    </div>
  </div>
  <footer>
    <div class="container">
      <img src="https://themelio.org/favicon.png" class="themelio-logo" />
      a <a href="https://themelio.org">themelio</a> project
    </div>
  </footer>
</template>

<style>
  .container {
    max-width: 1024px;
  }

  .themelio-logo {
    height: 1.5em;
    vertical-align: -6px;
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
