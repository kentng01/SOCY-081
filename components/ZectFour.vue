<template>

    <section id="4" class="sect4">
        <div class="header">
            <h1>「 BTS 」<span>cont.</span></h1>
        </div>

        <div class="sect4-body">
            <div class="lyrical-analysis">
                <h1>Rise of K-Wave, and COVID</h1>
                <p class="analyze">
                    <span>DNA, Crystal Snow, Spring Day, Boy With Luv,...</span>
                    <br />
                    Today, BTS is more focused on self-love and promoting a better world. During COVID's peak, 
                    that became a really hard time for numerous peoples, especially Asians as 
                    anti-Asian hate crimes began rising. Not restricted to just their music, BTS as a group
                    became a comforting voice for many, speaking on issues like Asian diversity and
                    inclusion.

                    <br><br />

                    <span>Dynamite</span> by BTS is very notable; written to bring joy and excitement
                    amidst the critical times. BTS says "due to COVID-19, people around the world have  
                    been going through tough times and we wanted to share some positive energy with our fans."
                </p>
            </div>
            <div class="bts">
                <img src="@/assets/images/kpop/bts3.png" alt="bts">
            </div>
        </div>

        <div class="outer-blurb">
            <p>However, mental health even affects groups and the idols themselves, such as Suga and Jin.</p>
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

.header span {
    font-style: italic;
}

.sect4-body {
    padding-top: 4rem;
    display: flex;
    justify-content: center;
    align-items: center;
}

.bts img {
    border-radius: 50%;
    padding-left: 1rem;
}

.lyrical-analysis {
    padding-right: 2rem;
    width: 66.6%;
}

.lyrical-analysis h1 {
    font-family: 'Playfair Display', serif;
    font-size: 2.25rem;
}

.analyze {
    padding-top: 0.75rem;
    font-size: 1.375rem;
}

.analyze span {
    font-style: italic;
}

.outer-blurb {
    padding-top: 4rem;
    display: flex;
    justify-content: center;
}

.outer-blurb p {
    font-size: 1.375rem;
    font-style: italic;
}

</style>