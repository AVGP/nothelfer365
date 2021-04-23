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

[[config]]
  type = "js"
  html = """
  <!-- Global site tag (gtag.js) - Google Analytics -->
  <script async src="https://www.googletagmanager.com/gtag/js?id=G-7X9FW3MCHK"></script>
  <script>
    window.dataLayer = window.dataLayer || [];
    function gtag(){dataLayer.push(arguments);}
    gtag('js', new Date());

    gtag('config', 'G-7X9FW3MCHK');
  </script>
  """
+++