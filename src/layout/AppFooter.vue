<template>
    <footer class="footer has-cards">
        <div class="container container-lg">
            <div class="row">
                <div class="col-md-6 mb-5 mb-md-0">
                    <div class="card card-lift--hover shadow border-0">
                          
                    </div>
                </div>
                <div class="col-md-6 mb-5 mb-lg-0">
                    <div class="card card-lift--hover shadow border-0">                      
                           
                    </div>
                </div>
            </div>
        </div>
        <div class="container">
            <div class="row row-grid align-items-center my-md">
                <div class="col-lg-6">
                    <h3 class="text-primary font-weight-light mb-2">Thank you for supporting us!</h3>
                    <h4 class="mb-0 font-weight-light">Let's get in touch on any of these platforms.</h4>
                </div>
                <div class="col-lg-6 text-lg-center btn-wrapper"></div>
            </div>
            <hr>
            <div class="row align-items-center justify-content-start">
                <div class="col-md-6">
                    <ul class="nav nav-footer justify-content-start">
                        <li class="nav-item1">
                            <a href="" class="nav-link" target="_blank" rel="noopener">Copyright © 2021 www.DNBExchange.com All right reserved</a>
                        </li>
                    </ul>                  
                </div>
                <div class="col-md-6">
                    <ul class="nav nav-footer justify-content-end">
                        <li class="nav-item">
                            <span class="nav-link" target="_blank" rel="noopener">DNB Exchange Company limited</span>
                            <span class="nav-link" target="_blank" rel="noopener">The Offices at Central World,</span>
                            <span  class="nav-link" target="_blank" rel="noopener">999/9 Rama I Rd., Patumwan</span>
                            <span  class="nav-link" target="_blank" rel="noopener">Bangkok 10330</span>
                        </li>
                    </ul>
                                       
                </div>
            </div>
        </div>
    </footer>
</template>
<script>
export default {
  name: 'app-footer',
  data() {
    return {
      year: new Date().getFullYear()
    }
  }
};
</script>
<style>
</style>
