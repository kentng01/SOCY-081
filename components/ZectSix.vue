<template>

    <section id="6" class="sect6">
        <div class="header">
            <h1>「 Prospective Sources 」<font-awesome-icon class="bmark" icon="fa-solid fa-bookmark" /></h1>
        </div>

        <div class="sect6-body">
            <div clas="twice">
                <img src="../assets/images/kpop/twice.png" alt="twice">
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

.sect6 {
    padding-top: 4.5rem;
    height: 150vh;
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

.sect6-body {
    padding-top: 2rem;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}

.bmark {
    transition: 250ms;
    font-size: 2.125rem;
}

.bmark:hover {
    color: #eff322;
}

</style>