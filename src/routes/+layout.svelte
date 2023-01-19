<script>
  import "prism-themes/themes/prism-one-dark.css";
</script>

<svelte:head>
  <link rel="stylesheet" href="/pico.min.css" />

  <style>
    nav {
      margin-left: 50%;
      margin-right: 50%;
    }
    .container-fluid {
      background-size: cover;
      background-image: url("https://media4.giphy.com/media/4jyU0IuAH6a1q/giphy.gif?cid=790b76116e6c74780283ba1f7c5af23fcd2d89c1a9e8f9d3&rid=giphy.gif&ct=g");

}
  </style>
</svelte:head>

<nav>
  <ul>
    <li><a href="/">Hem</a></li>
    <li><a href="/devblog">Blog</a></li>
  </ul>
</nav>

<main class="container-fluid">
  <hr />

  <main class="container">
    <slot />
  </main>
</main>
