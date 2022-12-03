<template>

    <section id="2" class="sect2">
        <div class="header">
            <h1>「 Exploring Themes In K-Pop 」</h1>
            <h2>{{ question }}</h2>
        </div>

        <div class="sect2-body">
            <div class="txt">
                <img src="@/assets/images/kpop/txt.png" alt="txt">
            </div>
            <div class="points">
                <h1>BTS, Miss A, Day6, TWICE, IU,...</h1>
                <ul>
                    <li v-for="(point, i) in points" :key="i">
                        {{ point.bpoint }}
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
            question: "To What Extent Has K-Pop Shaped And Impacted Mental Health?",
            points: [
                {
                    bpoint: "「 1 」Social anxiety, pressure, and stress in the industry"
                },
                {
                    bpoint: "「 2 」In South Korea, mental health is considered taboo"
                },
                {
                    bpoint: "「 3 」Songs with impactful themes embedded in lyrics"
                },
                {
                    bpoint: "「 4 」International outreach, timing of COVID-19"
                },
                {
                    bpoint: "「 5 」Solidarity amongst fandoms, and idols"
                },
            ],
        }
    }
}
</script>

<style scoped>

.sect2 {
    padding-top: 6rem;
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

.sect2-body {
    padding-top: 4rem;
    display: flex;
    align-items: center;
    justify-content: center;
}

.txt {
    padding-right: 1rem;
}

.txt img {
    width: 525px;
}

.points h1 {
    font-family: 'Playfair Display', serif;
    font-size: 1.875rem;
    font-weight: 600;
    padding-bottom: 0.75rem;
}

.points ul li {
    font-size: 1.375rem;
    padding: 0.25rem 0;
}


</style>