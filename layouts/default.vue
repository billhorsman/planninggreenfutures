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

<style lang="scss">
  @import '@/assets/stylesheets/main.scss';
  $stop: 60%;
  $angle: 80deg;
  $bg-1: $green;
  $bg-2: $green;
  $bg-3: #86A24D;
  header {
    background: $green; /* Old browsers */
    background: -moz-linear-gradient(-45deg, $bg-1 0%, $bg-2 $stop, $bg-3 100%); /* FF3.6-15 */
    background: -webkit-linear-gradient(-45deg, $bg-1 0%,$bg-2 $stop,$bg-3 100%); /* Chrome10-25,Safari5.1-6 */
    background: linear-gradient(135deg, $bg-1 0%,$bg-2 $stop,$bg-3 100%); /* W3C, IE10+, FF16+, Chrome26+, Opera12+, Safari7+ */
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
</style>
