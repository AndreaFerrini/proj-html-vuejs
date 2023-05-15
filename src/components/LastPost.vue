<script>

export default {
    name: "LastPost",

}
</script>

<template>
    <div class="container">
        <div class="row py-5 my-4">
            <div class="col-md-12 col-lg-8 mb-5 mb-lg-0">
                <!-- primo post -->
                <div class="mt-4">
                    <div class="">
                        <img src="public\images\blog-55.jpg" alt="">
                    </div>
                    <div class="p-2 mt-3 d-flex justify-content-start">
                        <div class="">
                        <p class="calendar">12<em>Jan</em></p>
                        </div>
                        <div class="">
                        <h3>How to Make Friends as a Grown-up</h3>
                        <p>Euismod atras vulputate iltricies etri elit. Class aptent taciti sociosque ad litora torquent per conubia nostra, per inceptos himenaeos. Nulla nunc dui, tristique in semper vel, congue sed ligua. Nam dolor ligula, faucibus id sodales in, auctor fringilla libero. Pellentesque pellentesque tempor tellus eget hendreit. Morbi id alinquam ligula. Aliquam id dui sem. Proin rhoncus consequat nisl, eu ornare mauris tincidunt vitae. [...]</p>
                        </div>
                    </div>
                    <div class="bottom-post">
                        <span class="p-3">
                            <i class="far fa-user me-2"></i>
                            By
                            <a href="#">John Doe</a>
                        </span>
                        <span class="p-3">
                            <i class="far fa-folder me-2"></i>
                            <a href="#">Lifestyle, </a>
                            
                            <a href="#">Travel</a>
                        </span>
                        <span class="p-3">
                            <i class="far fa-comments me-2"></i>
                            <a href="#">12 Comments</a>
                        </span>
                        <span class="d-block mt-2 d-flex justify-content-end">
                            <a href="#" class="btn btn-xs btn-light text-1 text-uppercase mb-3">Read More</a>
                        </span>
                    </div>
                    <hr>
                </div>
                <!-- secondo post -->
                <div class="mt-4">
                    <div class="">
                        <img src="public\images\blog-56.jpg" alt="">
                    </div>
                    <div class="p-2 mt-3 d-flex justify-content-start">
                        <div class="">
                        <p class="calendar">12<em>Jan</em></p>
                        </div>
                        <div class="">
                        <h3>Ranking the greatest players in basketball</h3>
                        <p>Euismod atras vulputate iltricies etri elit. Class aptent taciti sociosque ad litora torquent per conubia nostra, per inceptos himenaeos. Nulla nunc dui, tristique in semper vel, congue sed ligua. Nam dolor ligula, faucibus id sodales in, auctor fringilla libero. Pellentesque pellentesque tempor tellus eget hendreit. Morbi id alinquam ligula. Aliquam id dui sem. Proin rhoncus consequat nisl, eu ornare mauris tincidunt vitae. [...]</p>
                        </div>
                    </div>
                    <div class="bottom-post">
                        <span class="p-3">
                            <i class="far fa-user me-2"></i>
                            By
                            <a href="#">Tizio Caio</a>
                        </span>
                        <span class="p-3">
                            <i class="far fa-folder me-2"></i>
                            <a href="#">Sports, </a>
                            
                            <a href="#">Business</a>
                        </span>
                        <span class="p-3">
                            <i class="far fa-comments me-2"></i>
                            <a href="#">12 Comments</a>
                        </span>
                        <span class="d-block mt-2 d-flex justify-content-end">
                            <a href="#" class="btn btn-xs btn-light text-1 text-uppercase mb-3">Read More</a>
                        </span>
                    </div>
                    <hr>
                </div>
                <!-- terzo post -->
                <div class="mt-4">
                    <div class="">
                        <img src="public\images\blog-58.jpg" alt="">
                    </div>
                    <div class="p-2 mt-3 d-flex justify-content-start">
                        <div class="">
                        <p class="calendar">12<em>Jan</em></p>
                        </div>
                        <div class="">
                        <h3>Top Camper Trailer Towing Tips</h3>
                        <p>Euismod atras vulputate iltricies etri elit. Class aptent taciti sociosque ad litora torquent per conubia nostra, per inceptos himenaeos. Nulla nunc dui, tristique in semper vel, congue sed ligua. Nam dolor ligula, faucibus id sodales in, auctor fringilla libero. Pellentesque pellentesque tempor tellus eget hendreit. Morbi id alinquam ligula. Aliquam id dui sem. Proin rhoncus consequat nisl, eu ornare mauris tincidunt vitae. [...]</p>
                        </div>
                    </div>
                    <div class="bottom-post">
                        <span class="p-3">
                            <i class="far fa-user me-2"></i>
                            By
                            <a href="#">John Doe</a>
                        </span>
                        <span class="p-3">
                            <i class="far fa-folder me-2"></i>
                            <a href="#">Lifestyle, </a>
                            
                            <a href="#">Travel</a>
                        </span>
                        <span class="p-3">
                            <i class="far fa-comments me-2"></i>
                            <a href="#">12 Comments</a>
                        </span>
                        <span class="d-block mt-2 d-flex justify-content-end">
                            <a href="#" class="btn btn-xs btn-light text-1 text-uppercase mb-3">Read More</a>
                        </span>
                    </div>
                </div>
                <hr>
                <!-- cambio pagina -->
                <ul class="pagination d-flex justify-content-end mt-3">
				<li class="page-item">
                    <a class="page-link" href="#">
                        <i class="fas fa-angle-left"></i>
                    </a>
                </li>
				<li class="page-item active">
                    <a class="page-link" href="#">1</a>
                </li>
				<li class="page-item">
                    <a class="page-link" href="#">2</a>
                </li>
				<li class="page-item">
                    <a class="page-link" href="#">3</a>
                </li>
				<li class="page-item">
                    <a class="page-link" href="#">
                        <i class="fas fa-angle-right"></i>
                    </a>
                </li>
			</ul>
            </div>
            <div class="col-md-8 col-lg-4 mb-5 mb-lg-0">
                <!-- colonna 1 -->
                <div class="d-flex flex-column">
                    <h4 class="text-uppercase mb-3 text-dark">Latest from Twitter</h4>
                    <div class="d-flex justify-content-between">
                        <i class="fa-brands fa-twitter"></i>
                        <span class="ps-4">If you have any suggestions for the next updates, let us know.</span>
                    </div>
                    <div>
                        <h6 class="pt-3">01:05 Sep 18th</h6>
                    </div>
                </div>
                <!-- colonna 2 -->
                <div class="d-flex flex-column mt-5">
                    <h4 class="text-uppercase mb-3 text-dark">Latest from Twitter</h4>
                    <div class="d-flex justify-content-between">
                        <i class="fa-brands fa-twitter"></i>
                        <span class="ps-4">If you have any suggestions for the next updates, let us know.</span>
                    </div>
                    <div>
                        <h6 class="pt-3">01:05 Sep 18th</h6>
                    </div>
                </div>
                <!-- colonna 3 -->
                <div class="mt-5">
                    <h4 class="text-uppercase mb-3 text-dark">Photos from Instagram</h4>
                    <div class="gallery">
                        <div class="gallery__item gallery__item--1 d-flex">
                            <img src="public\images\29739607_2020680068220520_4509928046932787200_n.jpg" class="gallery__img" alt="#">
                        </div>
                        <div class="gallery__item gallery__item--2 d-flex">
                            <img src="public\images\30087804_253872848488989_8792603541668626432_n.jpg" class="gallery__img" alt="">
                        </div>
                        <div class="gallery__item gallery__item--3 d-flex">
                            <img src="public\images\29415620_196477127626244_3250318472361541632_n.jpg" class="gallery__img" alt="#">
                        </div>
                        <div class="gallery__item gallery__item--4 d-flex">
                            <img src="public\images\30078414_1274410412703843_8290935809419247616_n.jpg" class="gallery__img" alt="#">
                        </div>
                        <div class="gallery__item gallery__item--5 d-flex">
                            <img src="public\images\30077195_2066750973610181_3733150062893596672_n.jpg" class="gallery__img" alt="#">
                        </div>
                        <div class="gallery__item gallery__item--6 d-flex">
                            <img src="public\images\29415304_166583630713703_1032667922171953152_n.jpg" class="gallery__img" alt="#">
                        </div>
                    </div>
                </div>
                <!-- colonna 4 -->
                <div class="mt-5">
                    <h4 class="text-uppercase mb-3 text-dark">Tags</h4>
                    <span class="badge badge-dark bg-color-primary badge-sm py-2 mr-1 mb-2 text-uppercase">Gadgets</span>
                    <span class="badge badge-dark bg-color-primary badge-sm py-2 mr-1 mb-2 text-uppercase">Brands</span>
                    <span class="badge badge-dark bg-color-primary badge-sm py-2 mr-1 mb-2 text-uppercase">Video</span>
                    <span class="badge badge-dark bg-color-primary badge-sm py-2 mr-1 mb-2 text-uppercase">Business</span>
                    <span class="badge badge-dark bg-color-primary badge-sm py-2 mr-1 mb-2 text-uppercase">Travel</span>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>

.calendar{
  margin:.25em 10px 10px 0;
  padding-top:5px;
  float:left;
  width:80px;
  background:#ededef;
  background: -moz-linear-gradient(top,  #ededef,  #ccc); 
  font:bold 30px/60px Arial Black, Arial, Helvetica, sans-serif;
  text-align:center;
  color:#000;
  text-shadow:#fff 0 1px 0; 
  border-radius:3px;  
  position:relative;
  box-shadow:0 2px 2px #888;
  }

/* Em element is also styled, it contains the month’s name. */
.calendar em{
  display:block;
  font:normal bold 11px/30px Arial, Helvetica, sans-serif;
  color:#fff;
  text-shadow:#00365a 0 -1px 0; 
  background:#04599a; 
  background:-moz-linear-gradient(top,  #04599a,  #00365a); 
  border-bottom-right-radius:3px;
  border-bottom-left-radius:3px;  
  border-top:1px solid #00365a;
  }

  a{
    color: rgb(0,136,204);
  }

  h6{
    color: rgb(129,196,230);
    padding-left: 2.5rem;
  }

  .gallery {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: repeat(2, 5vw);
    width: 20%;
}

.gallery__img {
    width: calc( 100% / 3 -1px);
    object-fit: cover;
}

.badge{
    color: white;
    background-color: #000;
    margin: 5px;
}


</style>