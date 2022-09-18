<template>
    <main class="overflow-hidden ">
        <!--Start Login Page-->
        <section class="login-page pt-120 pb-120">
            <div class="container">
                <div class="row justify-content-center">
                    <div class="col-xl-6 col-lg-8 col-md-9 wow fadeInUp animated">
                        <div class="login-register-form"
                             style="background-image: url('assets/images/inner-pages/login-bg.png');">
                            <div class="top-title text-center ">
                                <h2>Register</h2>
                                <p>Already have an account? <a href="login.html">Log in</a></p>
                            </div>
                            <form class="common-form">
                                <div class="form-group"> <input type="text" class="form-control"
                                                                placeholder="Your Name"> </div>
                                <div class="form-group"> <input type="text" class="form-control" placeholder="Username">
                                </div>
                                <div class="form-group"> <input type="email" class="form-control"
                                                                placeholder="Your Email"> </div>
                                <div class="form-group eye">
                                    <div class="icon icon-1"> <i class="flaticon-hidden"></i></div> <input
                                    type="password" id="password-field" class="form-control" placeholder="Password">
                                    <div class="icon icon-2 "><i class="flaticon-visibility"></i> </div>
                                </div>
                                <div class="checkk ">
                                    <div class="form-check p-0 m-0"> <input type="checkbox" id="remember"> <label
                                        class="p-0" for="remember"> Accept the Terms and Privacy Policy </label>
                                    </div>
                                </div> <button type="submit" class="btn--primary style2">Register </button>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <!--End Login Page-->
    </main>
</template>

<script>
export default {
    name: "App"
}
</script>

<style scoped>

</style>
