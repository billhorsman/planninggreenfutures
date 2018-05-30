<template>
  <div>
    <header>
      <nav class="navbar navbar-default">
        <a class="navbar-brand" href="/">
          <abbr>pgf</abbr>
          <span>Planning Green Futures</span>
          <sub>Sierra Leone</sub>
        </a>
      </nav>
    </header>
    <div class="container">
      <nuxt/>
    </div>
    <footer>
      Planning Green Futures Ltd &mdash;
      37, Brook Street, Freetown, Sierra Leone
    </footer>
  </div>
</template>

<script>
export default {
  head: {
    title: "Planning Green Futures - Sierra Leone"
  }
}
</script>


<style lang="scss">
  @import '@/assets/stylesheets/main.scss';
  header {
    @include gradient($green, #86A24D);
    margin-bottom: 2rem;
  }
  .navbar-brand {
    position: relative;
    abbr {
      color: $yellow;
      font-size: 2rem;
      font-style: italic;
      line-height: 1rem;
    }
    span {
      color: white;
      font-size: 1.1rem;
      margin-left: .5rem;
      text-transform: uppercase;
    }
    sub {
      bottom: 3px;
      color: $yellow;
      font-weight: 100;
      position: absolute;
      right: 0;
    }
    &:hover {
      abbr, span, sub {
        color: lighten($yellow, 20%);
      }
    }
  }
  html {
    position: relative;
    min-height: 100%;
  }
  body {
    margin-bottom: 100px; /* Margin bottom by footer height */
  }
  footer {
    bottom: 0;
    background: #f0f0f0;
    padding: 1rem;
    position: absolute;
    text-align: center;
    width: 100%;
  }
</style>
