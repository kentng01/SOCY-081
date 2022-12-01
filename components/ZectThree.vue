<template>

    <section id="3" class="sect3">
        <div class="header">
            <h1>「 BTS 」</h1>
        </div>

        <div class="sect3-body">
            <div class="lyrical-analysis">
                <div class="bts">
                    <img src="@/assets/images/kpop/bts2.png">
                </div>
                <h1>Old BTS</h1>
                <ul>
                    <li v-for="(song, i) in songs" :key="i">
                        {{ song.title }}
                    </li>
                </ul>
            </div>
        </div>

    </section>
  
</template>

<script>
export default {
    data() {
        return {
            songs: [
                {
                    title: "I NEED U"
                },
                {
                    title: "FIRE"
                },
                {
                    title: "BLOOD SWEAT & TEARS"
                },
                {
                    title: "NO MORE DREAM"
                },
                {
                    title: "WE ARE BULLETPROOF"
                },
            ]
        }
    }
}
</script>

<style scoped>

.sect3 {
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

.sect3-body {
    padding-top: 3rem;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.lyrical-analysis h1 {
    font-family: 'Playfair Display', serif;
    font-size: 1.875rem;
}

.bts img {
    border-radius: 30%;
}

</style>