<template>
  <div class="nav-links">
    <ul>
        <li v-for="(link, i) in links" :key="i" class="link">
            <a :href="link.section">
                <h1>
                    <font-awesome-icon class="arrow" icon="fa-solid fa-arrow-up-right-from-square" />
                    {{ link.value }}
                </h1>
            </a>
        </li>
    </ul>
  </div>
</template>

<script>

export default {
    data () {
        return {
            links: [
                {
                    section: "#",
                    value: "1"
                },
                {
                    section: "#",
                    value: "2"
                },
                {
                    section: "#",
                    value: "3"
                },
                {
                    section: "#",
                    value: "4"
                },
                {
                    section: "#",
                    value: "5"
                },
                {
                    section: "#",
                    value: "6"
                },
                {
                    section: "#",
                    value: "7"
                },
                
            ]
        }
    }
}

</script>

<style scoped>

.nav-links {
    position: fixed;
    bottom: 3.5rem;
}
.nav-links ul li {
    padding: 0.25rem 0;
}

.arrow {
    font-size: 1rem;
    padding-right: 0.25rem;
    padding-bottom: 0.125rem;
}

.link {
    transition: 250ms;
}

.link:hover {
    transform: translate(5px, -5px);
}

.link a h1 {
    color: #fff;
    font-size: 1.75rem;
    font-weight: 600;
}

</style>