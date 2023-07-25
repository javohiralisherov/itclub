<script>
  // import Counter from "./lib/Counter.svelte";
</script>

<main>
  <header class="header">
    <div class="container">
      <div class="header__inner">
        <div class="header_logo">Logo</div>
        <div class="header__nav">
          <ul>
            <li><a href="">Home</a></li>
            <li><a href="">Service</a></li>
            <li><a href="">Portfolio</a></li>
            <li><a href="">Blog</a></li>
          </ul>
        </div>
        <div class="btn header__btn">Contact us</div>
      </div>
    </div>
  </header>
</main>

<style>
  .header {
    padding-top: 60px;
  }
  .header__inner {
    display: flex;
    justify-content: space-evenly;
    align-items: center;
  }
  .header__nav ul {
    display: flex;
    flex-direction: row;
    list-style-type: none;
  }
  .header__nav ul li {
    margin-right: 60px;
  }
  .header__nav ul li a {
    text-decoration: none;
  }
  .header__btn {
    padding: 12px 24px;
    font-weight: 500;
  }
</style>
