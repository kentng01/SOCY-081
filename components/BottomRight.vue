<template>

    <div class="nav-label">
        <img src="@/assets/images/anya.png">
         <p>Copyright &copy; KT,<span>kenNeRu</span>. December 2022.</p>
    </div>
  
</template>

<script>
export default {

}
</script>

<style>

.nav-label {
    position: fixed;
    bottom: 3.5rem;
    right: 3.5rem;
}

.nav-label img {
    width: 275px;
    transform: scaleX(-1);
    position: fixed;
    bottom: 5rem;
    right: 0.75rem;
    opacity: 0.8;
}

.nav-label p {
    font-size: 0.75rem;
    font-weight: 700;
    display: flex;
    justify-content: flex-end;
}

.nav-label p span {
    color: #eff322;
    padding-left: 0.25rem;
}

</style>