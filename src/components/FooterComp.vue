<script>

export default {
    name: "FooterComp",

}
</script>

<template>
    <footer>
        <div class="container py-2">
			<div class="row py-4">
				<div class="col-lg-1 d-flex align-items-center justify-content-center justify-content-lg-start mb-2 mb-lg-0">
					<a href="index.html" class="logo pr-0 pr-lg-3">
						<img alt="#" src="public\images\logo-footer.png">
					</a>
				</div>
				<div class="col-lg-7 d-flex align-items-center justify-content-center justify-content-lg-start mb-4 mb-lg-0">
					<p>AF© Copyright 2023. All Rights Reserved.</p>
				</div>
				<div class="col-lg-4 d-flex align-items-center justify-content-center justify-content-lg-end">
					<nav id="sub-menu">
						<ul class="d-flex">
							<li><i class="fas fa-angle-right p-1"></i><a href="page-faq.html" class="ml-1 text-decoration-none"> FAQ's</a></li>
							<li><i class="fas fa-angle-right p-1"></i><a href="sitemap.html" class="ml-1 text-decoration-none"> Sitemap</a></li>
							<li><i class="fas fa-angle-right p-1"></i><a href="contact-us.html" class="ml-1 text-decoration-none"> Contact Us</a></li>
						</ul>
					</nav>
				</div>
			</div>
		</div>
    </footer>
</template>

<style scoped>

footer{
    background-color: rgb(28,32,35);
}

img{
    height: 35px;
}

p, li, a {
    color: rgb(111,102,96);
}


li{
    padding: 10px;
}

</style>