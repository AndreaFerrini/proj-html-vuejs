<script>

export default {
    name: "MainComp",

}

</script>

<template>
    <main>
        <div class="container">
            <ul class="cards p-5">
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
                <li>
                    <a href="" class="card">
                    <img src="public\images\blog-47.jpg" class="card_image" alt="#" />
                    <div class="card_overlay">        
                        <div class="card_header">                
                        <div class="card_header-text">
                            <button class="text-uppercase">Gadgets</button>
                            <h3 class="card_title">Author: John Doe</h3>
                        </div>
                        </div>
                        <p class="card_description">Gadgets That Make Your Smartphone Even Smarter</p>
                    </div>
                    </a>
                </li>
                <li>
                    <a href="" class="card">
                    <img src="public\images\blog-48.jpg" class="card_image" alt="#" />
                    <div class="card_overlay">        
                        <div class="card_header">                
                        <div class="card_header-text">
                            <button class="text-uppercase">Travel</button>
                            <h3 class="card_title">Author: John Doe</h3>
                        </div>
                        </div>
                        <p class="card_description">20 Top-Rated tourist Attractions in Manhattan</p>
                    </div>
                    </a>
                </li>
                <li>
                    <a href="" class="card">
                    <img src="public\images\blog-49.jpg" class="card_image" alt="#" />
                    <div class="card_overlay">        
                        <div class="card_header">                
                        <div class="card_header-text">
                            <button class="text-uppercase">Lifestyle</button>
                            <h3 class="card_title">Author: John Doe</h3>
                        </div>
                        </div>
                        <p class="card_description">The Best Way to Ride a Motorcycle</p>
                    </div>
                    </a>
                </li>
                <li>
                    <a href="" class="card">
                    <img src="public\images\blog-50.jpg" class="card_image" alt="#" />
                    <div class="card_overlay">        
                        <div class="card_header">                
                        <div class="card_header-text">
                            <button class="text-uppercase">Travel</button>
                            <h3 class="card_title">Author: John Doe</h3>
                        </div>
                        </div>
                        <p class="card_description">5 Fun Things to Do at the Beach</p>
                    </div>
                    </a>
                </li>
                <li>
                    <a href="" class="card">
                    <img src="public\images\blog-51.jpg" class="card_image" alt="#" />
                    <div class="card_overlay">        
                        <div class="card_header">                
                        <div class="card_header-text">
                            <button class="text-uppercase">Recipes</button>
                            <h3 class="card_title">Author: John Doe</h3>
                        </div>
                        </div>
                        <p class="card_description">Amazingly Fresh Fruit And Herb Drinks For Summer</p>
                    </div>
                    </a>
                </li>
            </ul>
        </div>
    </main>
</template>

<style scoped>

main {
    background-color: rgb(247,247,247);
}

body {
  background-color: #fef8f8;
}

.cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(310px, 1fr));
  gap: 2rem;
  margin: 4rem 5vw;
  padding: 0;
  list-style-type: none;
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