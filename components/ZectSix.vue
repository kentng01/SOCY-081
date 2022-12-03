<template>

    <section id="6" class="sect6">
        <div class="header">
            <h1>「 Prospective Sources 」<font-awesome-icon class="bmark" icon="fa-solid fa-bookmark" /></h1>
        </div>

        <div class="sect6-body">
            <div class="twicexizone">
                <img src="../assets/images/kpop/twice.png" alt="twice" />
                <img src="../assets/images/kpop/izone2.png" alt="izone" />
            </div>
            <div class="srcs">
                <ul>
                    <li v-for="(src, i) in sources" :key="i">
                        <h2>{{ src.title }}</h2>
                        <p>
                            {{ src.desc }} 
                        </p>
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
            sources: [
                {
                    title: "K-Pop Stars Amber Liu & More Speak Out About The Pressure To Be Perfect After Sulli & Goo Hara's Deaths",
                    desc: "First-hand accounts into the pressures inherent to the K-pop industry and its unintentional consequences"
                },
                {
                    title: "BTS Won't Cure My Depression, But Loving Them Helps Me Cope",
                    desc: "Beyond music, BTS as a group provides comfort to many"
                },
                {
                    title: "BTS from “N.O” to “ON” and BEyond: Innovation in Effective Mental Health Messaging and Modelling",
                    desc: "How BTS and other K-Pop groups changed and led dicussions on mental health inside and outside K-Pop"
                },
                {
                    title: "Analyzing the Impact of BTS on Resolving the Problem of Youth Mental Health",
                    desc: "Explores BTS effects on the youth in regards to mental health"
                },
                {
                    title: "Mental Health, Community, Commitment, and the Growth of Individual Identity in the Participatory Fandom of the BTS ARMY",
                    desc: "The power of fandoms in creating a safe, confiding environment"
                },
                {
                    title: "Blood Sweat & Tears: A Closer Look at the K-Pop Phenomenon",
                    desc: "Evolution of K-Pop, in its music and the industry as a whole"
                },
                {
                    title: "Psychological wellbeing early adult Korean pop fangirls",
                    desc: "Examines the relationship between mental health and K-Pop in early adults (20-40)"
                },
                {
                    title: "K-Wave Content as a Source of Comfort During Coronavirus Widespread in Indonesia",
                    desc: "K-Pop and its influence on mental health during the pandemic"
                },
                {
                    title: "Social Movement and Mental Health of South Korean Women Sexual Violence Survivors, 2012-2019",
                    desc: "#MeToo movement, goes into various K-Pop scandals"
                },
            ]
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

.sect6-body {
    padding-top: 0.75rem;
    display: flex;
    justify-content: center;
    align-items: center;
}

.bmark {
    transition: 250ms;
    font-size: 2.125rem;
}

.bmark:hover {
    color: #eff322;
}

.twicexizone {
    padding-right: 1.5rem;
    width: 33.3%;
}

.srcs {
    width: 66.6%;
}

.srcs ul li {
    padding: 0.625rem 0;
}

.srcs ul li h2 {
    font-style: italic;
    font-size: 1.375rem;
    font-weight: 600;
    font-family: 'Playfair Display', serif;
}

.srcs ul li p {
    font-size: 1.25rem;
    font-weight: 500;
}

</style>