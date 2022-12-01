<template>

<nav class="nav-overlay">   
    <TopLeft />
    <TopRight />
    <BottomLeft />
    <BottomRight />
</nav>
  
</template>

<script>
export default {

}
</script>

<style>

@media screen and (max-width: 767px) {
    .nav-overlay {
        display: none;
    }
}

</style>