<template>

    <div class="nav-title">
        <a href="https://kenneru.netlify.app/" target="_blank">
            <img src="@/assets/images/dazai.png" />
        </a>
        <a href="#">
            <h1>KENNY</h1>
            <h2>z Z Z...</h2>
        </a>
    </div>
  
</template>

<script>
export default {

}
</script>

<style scoped>

.nav-title {
    position: fixed;
    display: flex;
}

.nav-title img {
    width: 75px;
    border-radius: 50%;
    border: 0.125rem solid #fff;
    margin-right: 0.75rem;
    transition: 200ms;
}

.nav-title img:hover {
    transform: scale(1.1) rotate(5deg);
}

.nav-title img:active {
    transform: scale(0.9);
}

.nav-title a h1 {
    font-size: 2rem;
    color: #fff;
}


.nav-title a h2 {
    font-size: 1.375rem;
    font-style: italic;
    font-weight: 400;
    color: #fff;
}


</style>