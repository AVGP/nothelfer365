+++
fragment = "config"

[[config]]
  type = "css"
  html = """
<style>
  .hero h1, .hero .hero-subtitle {
    color: white !important;
  }

  .hero .jumbotron {
    background: linear-gradient(black, transparent), url(/images/header.jpeg) !important;
    background-position: center !important;
    background-size: cover !important;
  }
</style>
"""

+++