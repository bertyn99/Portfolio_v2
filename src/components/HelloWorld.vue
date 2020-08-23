<template>
    <!-- slider_area_start -->
    <div class="slider_area">
        <div class="single_slider  d-flex align-items-center slider_bg_1">
            <div class="shap_pattern d-none d-lg-block">
                <img src="img/about/grid.png" alt="">
            </div>
            <div class="social_links">
                <ul>
                    <li><a href="#"> <i class="fa fa-facebook"></i> </a></li>
                    <li><a href="#"> <i class="fa fa-twitter"></i> </a></li>
                    <li><a href="#"> <i class="fa fa-instagram"></i> </a></li>
                </ul>
            </div>
            <div class="container">
                <div class="row align-items-center">
                    <div class="col-xl-12">
                        <div class="slider_text text-center">
                            <h3>
                                Bonjour c'est Bertyn
                            </h3>
                            <span>Etudiant en web developpement</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- slider_area_end -->
   
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
