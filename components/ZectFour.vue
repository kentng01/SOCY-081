<template>

    <section id="4" class="sect4">
        <div class="header">
            <h1>「 BTS 」<span>cont.</span></h1>
        </div>

        <div class="sect4-body">
            <div class="lyrical-analysis">
                ok
            </div>
            <div class="bts">
                <img src="@/assets/images/kpop/bts3.png">
            </div>
        </div>

    </section>
  
</template>

<script>
export default {
    data() {
        return {

        }
    }
}
</script>

<style scoped>

.sect4 {
    padding-top: 4.5rem;
    height: 100vh;
}

.header {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}

.header h1 {
    font-family: 'Playfair Display', serif;
    font-size: 2.25rem;
    text-align: center;
}

.header h2 {
    font-size: 1.625rem;
    font-weight: 500;
    padding-top: 0.375rem;
    text-align: center;
    font-style: italic;
}

.header span {
    font-style: italic;
}

.sect4-body {
    padding-top: 4rem;
    display: flex;
}

.bts img {
    border-radius: 50%;
    padding-left: 1rem;
}


</style>