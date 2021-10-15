<template>
    <section class="section section-lg section-nucleo-icons pb-250">
        <div class="container" @mouseleave="showIconsAnimation = false">
            <div class="row justify-content-center" @mouseover="showIconsAnimation = true">
                <div class="col-lg-8 text-center">
                    <h2 class="display-3">Utility Concept of Exchange</h2>
                    <p class="lead">
                        Utility is what motivates people to engage in a marketing exchange. In theory, both parties must receive more than what they give. 
                        For instance, the man buying the cup of coffee is more motivated to drink coffee than he is to hold on to his money, so he receives utility from the exchange. 
                    </p>
                    <div class="btn-wrapper">
                        <base-button type="primary" icon="ni ni-bag-17">With Exchange</base-button>
                        <base-button type="default">Restricted</base-button>
                    </div>
                </div>
            </div>
            <div class=" ">
                <a href=" ">
                    <div class="icons-container blur-item mt-5" :class="{'on-screen': showIconsAnimation}">
                        <!-- Center -->
                        <i class="icon ni ni-diamond"></i>
                        <!-- Right 1 -->
                        <i class="icon icon-sm ni ni-album-2"></i>
                        <i class="icon icon-sm ni ni-app"></i>
                        <i class="icon icon-sm ni ni-atom"></i>
                        <!-- Right 2 -->
                        <i class="icon ni ni-bag-17"></i>
                        <i class="icon ni ni-bell-55"></i>
                        <i class="icon ni ni-credit-card"></i>
                        <!-- Left 1 -->
                        <i class="icon icon-sm ni ni-briefcase-24"></i>
                        <i class="icon icon-sm ni ni-building"></i>
                        <i class="icon icon-sm ni ni-button-play"></i>
                        <!-- Left 2 -->
                        <i class="icon ni ni-calendar-grid-58"></i>
                        <i class="icon ni ni-camera-compact"></i>
                        <i class="icon ni ni-chart-bar-32"></i>
                    </div>
                </a>
            </div>
        </div>
    </section>
</template>
<script>
export default {
  data() {
    return {
      showIconsAnimation: false
    };
  },
  methods: {
    onScroll(evt) {
      ;
    }
  }
};
</script>
<style>
</style>
