<script>

export default {
    name: "HeaderComp",

}
</script>

<template>
    <header>
        <div class="container d-flex align-items-center">
            <h5>Everything about lifestyle, travel and gadgets!</h5>
            <ul class="text-uppercase d-flex  aling-items-center">
                <li class="p-3 text-uppercase">
                    <a href="#">Sign up</a>
                </li>
                <li class="p-3 text-uppercase">
                    <a href="#">About us</a>
                </li>
                <li class="p-3 text-uppercase">
                    <a href="#">Contact us</a>
                </li>
                <li class="p-3 text-uppercase">
                    <a href="#">Buy now</a>
                </li>
            </ul>
        </div>
    </header>
</template>

<style>
header{
    font-family: 'Cabin', sans-serif;
    font-size: 14px;
    color: white;
    background-color: rgb(0,136,204);
}

h5{
    color: rgb(189,224,242);
    font-size: 15px;
}

ul {
    list-style-type: none;
}

a{
    text-decoration: none;
    color: white;
    cursor: pointer;
}
</style>