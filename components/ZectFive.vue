<template>

    <section id="5" class="sect5">
        <div class="header">
            <h1>「 Abstract(s) 」</h1>
        </div>

        <div class="sect5-body">
            <div class="summary">
                <h3>
                    The relationship between K-Pop and Mental Health is vast, but the two intertwine by their
                    natures. K-Pop songs are written with care and complexity, whilst embedding themes and 
                    meaningful messages to share with their audiences. 
                    <br><br />
                    <span>But to what extent has K-Pop and K-Wave shaped and impacted mental health?</span>
                    <br><br />
                    We have already seen how groups as impactful and influential ("soft power") as BTS utilize
                    their platform to project their voices to spread awareness. However, mental health affects
                    all, including K-Pop groups and the idols themselves. The K-Pop industry is competitive and
                    extremely difficult, coming with lots of pressures; and even idols have come forth with their 
                    own battles against mental health. 
                    <br><br />
                    In essence, K-Pop, as a whole, is an outlet that can 
                    be used to share general positivity or impactful messages. 
                </h3>
            </div>
            <div class="abstract-ideas">
                <img class="izone" src="../assets/images/kpop/izone1.png" alt="izone">
                <ul>
                    <li v-for="(abstract, i) in abstracts" :key="i">
                        {{ abstract.idea }}
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
            abstracts: [
                {
                    idea: "How has K-Pop music influenced mental health in Youth?"
                },
                {
                    idea: "How are idols leading the discussions of mental health?"
                },
                {
                    idea: "How do fandoms and idols play a role in bring together peoples?"
                },
                {
                    idea: "How are idols personally affected by the pressures of the K-Pop industry?"
                },
                {
                    idea: "How do songs present their themes?"
                },
            ]
        }
    }
}
</script>

<style scoped>

.sect5 {
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

.sect5-body {
    padding-top: 1rem;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}

.summary {
    padding-top: 0.5rem;
    display: flex;
    justify-content: center;
}

.summary span {
    font-style: italic;
    padding-right: 0.25rem;
}

.summary h3 {
    font-weight: 400;
    font-size: 1.375rem;
}

.abstract-ideas {
    padding-top: 2rem;
    display: flex;
    justify-content: center;
    flex-direction: column;
}

.izone {
    padding: 0rem 0 1rem 0;
}

.abstract-ideas ul {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}

.abstract-ideas ul li {
    font-family: 'Playfair Display', serif;
    font-size: 1.375rem;
    padding: 0.125rem 0;
    text-align: center;
}

</style>