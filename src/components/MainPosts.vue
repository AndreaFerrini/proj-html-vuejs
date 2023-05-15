<script>

export default {
    name: "MainPosts",

}

</script>

<template>
    <div class="container pt-3">
        <div class="row py-5 my-4">
            <div class="col-md-6 col-lg-4 mb-5 mb-lg-0">
                <h4 class="text-uppercase mb-5">Popular Post</h4>
                <ul class="list-unstyled mb-0">
                    <li id="puntini" class="media mb-5 pb-4 d-flex">
                        <img class="img-post" src="public\images\blog-55.jpg" alt="#">
                        <div class="p-2">
                            <h5>Simple Ways to Have a Pretty Face</h5>
                            <h6 id="data">January 12, 2019</h6>
                        </div>
                    </li>
                    <li id="puntini" class="media mb-5 pb-4 d-flex">
                        <img class="img-post" src="public\images\blog-56.jpg" alt="#">
                        <div class="p-2">
                            <h5>Simple Ways to Have a Pretty Face</h5>
                            <h6 id="data">January 12, 2019</h6>
                        </div>
                    </li>
                    <li id="puntini" class="media mb-5 pb-4 d-flex">
                        <img class="img-post" src="public\images\blog-57.jpg" alt="#">
                        <div class="p-2">
                            <h5>Simple Ways to Have a Pretty Face</h5>
                            <h6 id="data">January 12, 2019</h6>
                        </div>
                    </li>
                    <li id="puntini" class="media mb-5 pb-4 d-flex">
                        <img class="img-post" src="public\images\blog-58.jpg" alt="#">
                        <div class="p-2">
                            <h5>Simple Ways to Have a Pretty Face</h5>
                            <h6 id="data">January 12, 2019</h6>
                        </div>
                    </li>
                    <li id="puntini" class="media mb-5 pb-4 d-flex">
                        <img class="img-post" src="public\images\blog-59.jpg" alt="#">
                        <div class="p-2">
                            <h5>Simple Ways to Have a Pretty Face</h5>
                            <h6 id="data">January 12, 2019</h6>
                        </div>
                    </li>
                </ul>
            </div>
            <div class="col-md-6 col-lg-4 mb-5 mb-lg-0">
                <h4 class="text-uppercase mb-5">Recent Post</h4>
                <ul class="list-unstyled mb-0">
                    <li id="puntini" class="media mb-5 pb-4 d-flex">
                        <img class="img-post" src="public\images\blog-65.jpg" alt="#">
                        <div class="p-2">
                            <h5>Main Reason to Stop Testing and Driving</h5>
                            <h6 id="data">January 12, 2019</h6>
                        </div>
                    </li>
                    <li id="puntini" class="media mb-5 pb-4 d-flex">
                        <img class="img-post" src="public\images\blog-66.jpg" alt="#">
                        <div class="p-2">
                            <h5>Tips to Help You Quickly Prepare Your Lunch</h5>
                            <h6 id="data">January 12, 2019</h6>
                        </div>
                    </li>
                    <li id="puntini" class="media mb-5 pb-4 d-flex">
                        <img class="img-post" src="public\images\blog-67.jpg" alt="#">
                        <div class="p-2">
                            <h5>Why Should I Buy a Smartphone</h5>
                            <h6 id="data">January 12, 2019</h6>
                        </div>
                    </li>
                    <li id="puntini" class="media mb-5 pb-4 d-flex">
                        <img class="img-post" src="public\images\blog-68.jpg" alt="#">
                        <div class="p-2">
                            <h5>The Best Augmented Reality Smartglasses</h5>
                            <h6 id="data">January 12, 2019</h6>
                        </div>
                    </li>
                    <li id="puntini" class="media mb-5 pb-4 d-flex">
                        <img class="img-post" src="public\images\blog-69.jpg" alt="#">
                        <div class="p-2">
                            <h5>12 Healtiest Foods to Eat for Breakfast</h5>
                            <h6 id="data">January 12, 2019</h6>
                        </div>
                    </li>
                </ul>
            </div>
            <div class="col-md-6 col-lg-4 mb-5 mb-lg-0">
                <h4 class="text-uppercase mb-5">Featured Post</h4>
                <ul class="list-unstyled mb-0">
                    <li>
                        <a href="" class="card">
                        <img src="public\images\blog-46.jpg" class="card_image" alt="#" />
                        <div class="card_overlay">        
                            <div class="card_header">                
                            <div class="card_header-text">
                                <button class="text-uppercase">Photography</button>
                                <h3 class="card_title">Author: John Doe</h3>
                            </div>
                            </div>
                            <p class="card_description">How To Take Better Concert Pictures in 30 Seconds</p>
                        </div>
                        </a>
                    </li>
                </ul>
                <ul class="list-unstyled mb-0">
                    <li>
                        <h4 class="text-uppercase mb-5 mt-5">Featured Author</h4>
                        <a href="" class="card">
                        <img src="public\images\John-Doe.jpg" class="card_image" alt="#" />
                        <div class="card_overlay">        
                            <div class="card_header">                
                            <div class="card_header-text">
                                <h3 class="card_title">John Doe</h3>
                            </div>
                            </div>
                            <p class="card_description">He is a serial photographer and starts his working with The Seven Wonders of the World. He earned a sense of creativity rivaling with Mr. Somerset and Mr. Mills. </p>
                        </div>
                        </a>
                    </li>
                </ul>
            </div>
        </div>
    </div>
</template>

<style scoped>

.img-post{
    width: 20%;
}

#puntini{
    border-bottom: 1px dashed grey;
}

h5{
    color: black;
}

h6{
    color: rgb(147,155,193);
}

.card {
  position: relative;
  display: block;
  height: 100%;  
  overflow: hidden;
  text-decoration: none;
}

.card_image {      
  width: 100%;
  height: auto;
}

.card_overlay {
  position: absolute;
  bottom: 0;
  left: 0;
  right: 0;
  z-index: 1;        
  transform: translateY(100%);
  transition: .2s ease-in-out;
}

.card:hover .card_overlay {
  transform: translateY(0);
}

.card_header {
  position: relative;
  display: flex;
  align-items: center;
  gap: 2em;
  padding: 2em;
  transform: translateY(-100%);
  transition: .2s ease-in-out;
}

.card:hover .card_header {
  transform: translateY(0);
}

.card_title {
  font-size: 1em;
  margin: 0 0 .3em;
  color: white;
}

.card_description {
  padding: 0 2em 2em;
  margin: 0;
  color: white; 
  display: -webkit-box;
  overflow: hidden;
  font-weight: 600;
}

button{
    color: white;
    background-color: rgb(0,136,204);
    font-size: 12px;
    font-weight: 600;
    border-style: none;
    border-radius: 5px;
}

</style>