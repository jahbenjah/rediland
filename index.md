---
---

<!DOCTYPE html>
<html lang="en">

<head>
  {% include head.html %}
</head>

<body>


{% include busqueda.html %}
{% include nav.html %}
{% include intro.html %}
  <main id="main">

{% include agentes.html %}
{% include propiedades.html %}
{% include noticias.html %}
{% include testimonios.html %}

  </main><!-- End #main -->

  {% include footer.html %}

  <a href="#" class="back-to-top"><i class="fa fa-chevron-up"></i></a>
  <div id="preloader"></div>

  <!-- Vendor JS Files -->
  <script src="assets/vendor/jquery/jquery.min.js"></script>
  <script src="assets/vendor/bootstrap/js/bootstrap.bundle.min.js"></script>
  <script src="assets/vendor/jquery.easing/jquery.easing.min.js"></script>
  <script src="assets/vendor/php-email-form/validate.js"></script>
  <script src="assets/vendor/owl.carousel/owl.carousel.min.js"></script>
  <script src="assets/vendor/scrollreveal/scrollreveal.min.js"></script>

  <!-- Template Main JS File -->
  <script src="assets/js/main.js"></script>

</body>

</html>