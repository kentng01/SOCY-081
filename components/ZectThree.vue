<template>

    <section id="3" class="sect3">
        <div class="header">
            <h1>「 BTS 」</h1>
        </div>

        <div class="sect3-body">
            <div class="bts">
                <img src="@/assets/images/kpop/bts2.png" alt="bts">
            </div>
            <div class="lyrical-analysis">
                <div class="songs">
                    <h1>INTRO: BTS</h1>
                    <ul>
                        <li v-for="(song, i) in songs" :key="i">
                            {{ song.title }}
                        </li>
                    </ul>
                </div>
                <div class="analyze">
                    <h3>
                        "their lyrics often discuss mental health, <br /><span>the troubles 
                        of school-age youth and coming of age, loss, the journey 
                        towards self-love, and individualism.</span>"
                    </h3> 
                    <br><br />
                    <p>
                        First albums and songs spoke on the idea of not feeling forced or 
                        expected to follow social expectations or pressures. Criticizes society
                        for its prejudices and tendencies to ruin dreams. Shares uplifting
                        messages of motivation and determination. <br/>
                    </p>
                </div>
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
                    title: "FIRE"
                },
                {
                    title: "I NEED U"
                },
                {
                    title: "NO MORE DREAM"
                },
                {
                    title: "WE ARE BULLETPROOF"
                },
                {
                    title: "BLOOD SWEAT & TEARS"
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

.sect3-body {
    padding-top: 1rem;
}

.bts {
    display: flex;
    justify-content: center;
}

.lyrical-analysis {
    padding: 2rem 5rem 0 5rem;
    display: flex;
    justify-content: center;
}

.songs {
    padding-right: 2rem;
}

.songs h1 {
    font-family: 'Playfair Display', serif;
    font-size: 1.875rem;
}

.songs ul li {
    font-size: 1.5rem;
    font-style: italic;
}

.analyze {
    width: 66.6%;
}

.analyze h3 {
    font-size: 1.25rem;
    font-style: italic;
    font-weight: 600;
}

.analyze h3 span {
    color: #eff322;
}

.analyze p {
    font-size: 1.25rem;
}

</style>