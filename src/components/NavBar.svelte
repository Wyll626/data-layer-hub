<!-- NavBar.svelte -->
<script>
  // JavaScript for NavBar, if needed
</script>

<style>
  .navbar {
    background-color: #333;
    overflow: hidden;
    height: 50px;
    line-height: 50px;
  }

  .navbar a {
    float: left;
    display: block;
    color: white;
    text-align: center;
    padding: 0 20px;
    text-decoration: none;
  }

  .navbar a:hover {
    background-color: #ddd;
    color: black;
  }
</style>

<div class="navbar">
  <a href="#home">Home</a>
  <a href="#about">About</a>
  <a href="#services">Services</a>
  <a href="#contact">Contact</a>
</div>
