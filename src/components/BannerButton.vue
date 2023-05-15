<script>

export default {
    name: "BannerButton",
    data(){
        return{
            menuButton: [
                {
                    nome:`Photos`,
                    url: `#`,
                    current: false
                },
                {
                    nome:`Gadgets`,
                    url: `#`,
                    current: true
                },
                {
                    nome:`Lifestyle`,
                    url: `#`,
                    current: false
                },
                {
                    nome:`Fashion`,
                    url: `#`,
                    current: false
                },
                {
                    nome:`Recipes`,
                    url: `#`,
                    current: false
                },
                {
                    nome:`Travel`,
                    url: `#`,
                    current: false
                },

            ]
        }
    },
    methods: {
        next(){
            console.log(`next`)

            this.currentButton++

            if( this.currentButton > this.currentButton.length - 1) {
                this.currentButton = 0
            }
        },
        prev(){
            console.log(`prev`)

            this.currentButton--

            if( this.currentButton < 0) {
                this.currentButton = this.currentButton.length - 1
            }
        }
    }

}
</script>

<template>
    <div class="banner-sfondo">
        <div class="container">
            <ul id="btn-centra" class="d-flex justify-content-between align-items-center">
                <div @click="prev">
                    <i class="fa-solid fa-chevron-left"></i>
                </div>
                <li class="p-5" v-for="(elem, index) in menuButton" :key="index">
                    <a href="#" class="btn p-4 text-uppercase mr-2 mb-2" 
                    :class=" currentButton ? `active` : `` " :href="elem.url"> {{ elem.nome }}</a>
                </li>
                <div @click="next">
                    <i class="fa-solid fa-chevron-right"></i>
                </div>        
            </ul>
        </div>
    </div>
</template>

<style scoped>

.banner-sfondo{
    background-color: rgb(0,136,204);
    min-height: 150px;
}

a{
    color: white;
    background-color: rgb(33,37,41);
    width: 150%;
}

a:active{
    color: rgb(33,37,41);
    background-color: white;
}

#btn-centra{
    line-height: 50px;
}

.fa-solid {
    width: 20px;
    height: 20px;
    margin: 10px 0;
    border-radius: 50%;
    position: absolute;
    cursor: pointer;
    z-index: 999;
}

.fa-chevron-left{
    left: 10%;
}

.fa-chevron-right{
    right: 10%;
}

</style>