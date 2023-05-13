<script>

export default {
    name: "NavHComp",
    data(){
        return{
            menuLinks: [
                {
                    nome:`Home`,
                    url: ``,
                    current: true
                },
                {
                    nome:`Elements`,
                    url: ``,
                    current: false
                },
                {
                    nome:`Features`,
                    url: ``,
                    current: false
                },
                {
                    nome:`Pages`,
                    url: ``,
                    current: false
                },
                {
                    nome:`Portfolio`,
                    url: ``,
                    current: false
                },
                {
                    nome:`Blog`,
                    url: ``,
                    current: false
                },
                {
                    nome:`Shop`,
                    url: ``,
                    current: false
                },

            ]
        }
    }

}
</script>

<template>
    <div class="container d-flex justify-content-between align-items-center">
        <div class="text-uppercase">
            <ul class="d-flex justify-content-start align-items-center">
                <li class="p-3" v-for="(elem, index) in menuLinks" :key="index">
                    <a :class=" elem.current ? `active` : `` " :href="elem.url"> 
                            {{ elem.nome }}
                    </a>
                </li>            
            </ul>
        </div>
        <div class="">
            <input type="search" placeholder="">
            <button class="search-button">
                <img src="public\images\lente.jpg" alt="">

            </button>
        </div>
    </div>
</template>

<style scoped>

a{
    color: rgb(68,68,68);
    font-size: large;
    font-weight: 600;
}

:hover{
    color: rgb(0,136,209);
}

.search-button {
  background: transparent;
  border: none;
  outline: none;
  margin-left: -33px;
}

.search-button img {
  width: 20px;
  height: 20px;
  object-fit: cover;
}
</style>