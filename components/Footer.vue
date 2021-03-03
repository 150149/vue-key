<template>
  <div>
    <footer class="site-footer">
      <div class="site-footer__upper">
        <div class="container">
          <div class="row">
            <div class="col-lg-6">
              <div class="footer-widget footer-widget__about">
                <img src="/assets/images/resources/logo-dark.png" width="119" alt="" class="footer-widget__logo">

                <!-- /.footer-widget__contact -->


              </div><!-- /.footer-widget -->
            </div><!-- /.col-lg-2 -->
            <div class="col-lg-3 d-flex justify-content-between footer-widget__links-wrap">
              <div class="footer-widget footer-widget__about">
                <!-- /.footer-widget__contact -->
                <p class="footer-widget__contact"><a>耀世中洲</a></p>

              </div><!-- /.footer-widget -->

            </div><!-- /.col-lg-6 -->
            <div class="col-lg-3">
              <p class="footer-widget__contact">QQ群：1054842957</p><!-- /.footer-widget__contact -->
            </div><!-- /.col-lg-4 -->
          </div><!-- /.row -->
        </div><!-- /.container -->
      </div><!-- /.site-footer__upper -->
      <div class="site-footer__bottom">
        <div class="container">
          <div class="inner-container text-center">
            <p class="site-footer__copy">&copy; copyright 2020 by <a >150149</a></p>
            <!-- /.site-footer__copy -->
          </div><!-- /.inner-container -->
        </div><!-- /.container -->
      </div><!-- /.site-footer__bottom -->
    </footer>



  </div>
</template>

<script>
    export default {
      name: "Footer",
      mounted() {

        $(window).on('scroll', function () {
          if ($('.scroll-to-top').length) {
            var strickyScrollPos = 100;
            if ($(window).scrollTop() > strickyScrollPos) {
              $('.scroll-to-top').fadeIn(500);
            } else if ($(this).scrollTop() <= strickyScrollPos) {
              $('.scroll-to-top').fadeOut(500);
            }
          }
        })
      }
    }
</script>

<style scoped>

</style>
