<script>

export default {
    name: "MainBottom",

}
</script>

<template>
    <div id="nero-opaco">
        <div class="container pt-3">
            <div class="row py-5">
                <div class="col-md-6 col-lg-3 mb-5 mb-lg-0">
                    <h4 class="text-uppercase mb-5">About the blog</h4>
                    <p>Lorem ipsum door sit amet, consectetur adipiscing elit. Donec eu pulvinar magna semper scelerisque.</p>
                    <p class="mb-0">Praesent venenatis turpis vitae purus semper, eget sagittis velit venenatis ptent taciti sociosqu ad litora...</p>
                    <p class="mt-3"><a href="#" class="btn-flat btn-xs p-relative"><strong class="text-2 text-uppercase">View More</strong><i class="fas fa-angle-right p-relative top-1 p-2"></i></a></p>
                </div>
                <div class="col-md-6 col-lg-4 mb-5 mb-lg-0">
                    <h4 class="text-uppercase mb-5">Recent Post</h4>
                    <ul class="list-unstyled mb-0">
                        <li class="media mb-3 pb-1">
                            <div class="d-flex">
                                <a href="#">
                                    <img class="mr-3 rounded-circle" src="public\images\our-office-4-square.jpg" alt="#">
                                </a>
                                <div class="media-body p-2">
                                    <a href="#">
                                        <h4 class="line-height-6 text-3 opacity-8 ls-0 mb-1">Lorem ipsum dolor sit, consectetur adipiscing elit.</h4>
                                        <p class="text-2 mb-0">12:53 AM Dec 19th</p>
                                    </a>
                                </div>
                            </div>
                        </li>
                        <li class="media">
                            <div class="d-flex">
                                <a href="#">
                                    <img class="mr-3 rounded-circle" src="public\images\our-office-5-square.jpg" alt="#">
                                </a>
                                <div class="media-body p-2">
                                    <a href="#">
                                        <h4 class="line-height-6 text-3 opacity-8 ls-0 mb-1">Lorem ipsum dolor sit, consectetur adipiscing elit.</h4>
                                        <p class="text-2 mb-0">12:53 AM Dec 19th</p>
                                    </a>
                                </div>
                            </div>
                        </li>
                    </ul>
                </div>
                <div class="col-md-6 col-lg-3 mb-5 mb-md-0">
                    <h4 class="text-uppercase mb-5">Recent Comments</h4>
                    <ul class="list-unstyled mb-0">
                        <li class="mb-3 pb-1">
                            <a href="#">
                                <p class="text-3 opacity-8 mb-1"><i class="fas fa-angle-right text-color-blue pe-2"></i><strong class="ml-2 text-color-white">John Doe</strong> commented on <strong class="text-color-blue">lorem ipsum dolor sit amet.</strong></p>
                                <p class="text-2 mb-0">12:55 AM Dec 19th</p>
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                <p class="text-3 opacity-8 mb-1"><i class="fas fa-angle-right text-color-blue pe-2"></i><strong class="ml-2 text-color-white">John Doe</strong> commented on <strong class="text-color-blue">lorem ipsum dolor sit amet.</strong></p>
                                <p class="text-2 mb-0">12:55 AM Dec 19th</p>
                            </a>
                        </li>
                    </ul>
                </div>
                <div class="col-md-6 col-lg-2">
                    <h4 class="text-uppercase mb-5">Categories</h4>
                    <p>

                        <span class="badge badge-dark bg-color-primary badge-sm py-2 mr-1 mb-2 text-uppercase" data-v-5992cfb4="">Gadgets</span>

                        <span class="badge badge-dark bg-color-primary badge-sm py-2 mr-1 mb-2 text-uppercase" data-v-5992cfb4="">Photography</span>

                        <span class="badge badge-dark bg-color-primary badge-sm py-2 mr-1 mb-2 text-uppercase" data-v-5992cfb4="">Lifestyle</span>

                        <span class="badge badge-dark bg-color-primary badge-sm py-2 mr-1 mb-2 text-uppercase" data-v-5992cfb4="">Fashion</span>

                        <span class="badge badge-dark bg-color-primary badge-sm py-2 mr-1 mb-2 text-uppercase" data-v-5992cfb4="">Recipes</span>

                        <span class="badge badge-dark bg-color-primary badge-sm py-2 mr-1 mb-2 text-uppercase" data-v-5992cfb4="">Travel</span>

                        <span class="badge badge-dark bg-color-primary badge-sm py-2 mr-1 mb-2 text-uppercase" data-v-5992cfb4="">Business</span>

                        <span class="badge badge-dark bg-color-primary badge-sm py-2 mr-1 mb-2 text-uppercase" data-v-5992cfb4="">Architecture</span>

                        <span class="badge badge-dark bg-color-primary badge-sm py-2 mr-1 mb-2 text-uppercase" data-v-5992cfb4="">Reviews</span>

                        <span class="badge badge-dark bg-color-primary badge-sm py-2 mr-1 mb-2 text-uppercase" data-v-5992cfb4="">Sports</span>

                        <span class="badge badge-dark bg-color-primary badge-sm py-2 mr-1 mb-2 text-uppercase" data-v-5992cfb4="">Videos</span>

                        <span class="badge badge-dark bg-color-primary badge-sm py-2 mr-1 mb-2 text-uppercase" data-v-5992cfb4="">Technology</span>

                        <span class="badge badge-dark bg-color-primary badge-sm py-2 mr-1 mb-2 text-uppercase" data-v-5992cfb4="">Design</span>

                    </p>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>

#nero-opaco{
    background-color: rgb(33,37,41);
}

h4{
    color: white;
    font-size: 14px;
}

p{
    color: rgb(111,102,96);
}

.text-color-blue{
    color: rgb(11,102,147);
}

.text-color-white{
    color: white;
}

</style>