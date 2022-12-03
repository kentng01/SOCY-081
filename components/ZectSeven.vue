<template>

    <section id="7" class="sect7">
        <div class="header">
            <h1>「 Closing 」</h1>
            <p>
                In South Korea (and most East Asian countries), mental health is often a taboo
                topic; however, K-Pop provides a way to express those feelings. Many idols haves come
                out with their own battles, including 
                <span>RM (BTS), Suga (BTS), Jeongyeon (TWICE), S.Coups (SEVENTEEN), IU, HyunA, and more</span>.
                Yet, as they grapple with the pressures of the K-Pop industry, they are also
                providing a comforting voice of solace for millions of fans around the world.
            </p>
        </div>

        <div class="sect7-body">
            <div class="gallery">
                <img class="nct" src="../assets/images/kpop/nct.png" alt="nct">
            </div>

            <div class="final-remarks">
                <h1>Thank you 
                    <font-awesome-icon class="wand" icon="fa-solid fa-wand-magic-sparkles" /> 
                    <span>Any Questions?</span>
                </h1>
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

.sect7 {
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

.header p {
    font-size: 1.375rem;
    padding-top: 2rem;
    text-align: center;
}

.header p span {
    font-style: italic;
}

.sect7-body {
    padding-top: 2rem;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}

.nct {
    border-bottom-left-radius: 50%;
    border-bottom-right-radius: 50%;
}

.bmark {
    transition: 250ms;
    font-size: 2.125rem;
}

.final-remarks {
    font-size: 1.625rem;
    font-family: 'Playfair Display', serif;
    padding-top: 2rem;
}

.final-remarks .wand {
    font-size: 1.875rem;
    padding: 0 0.125rem;
}

.final-remarks span {
    font-style: italic;
}

</style>