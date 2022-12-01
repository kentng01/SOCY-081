<template>
  <div class="nav-time">
    <h1>SOCY081</h1>
    <time>
        {{ time }}
    </time>
  </div>
</template>

<script>

export default {
    data() {
        return {
            t: true,
            time: "",
        }
    },

    mounted() {
      this.liveTime();
    //   this.musicToggle();

    },

    created() {
      setInterval(() => {
        this.liveTime();
      }, 0);
    },

    methods: {
      liveTime() {
        this.time = new Date().toLocaleString([], {
          // year: "numeric",
          // month: "numeric",
          // day: "numeric",
          hour: "2-digit",
          minute: "2-digit",
          second: "2-digit"
        });
      },

    },
      
}

</script>

<style scoped>

.nav-time {
    position: fixed;
    right: 3.5rem;
}

.nav-time h1 {
    font-size: 2rem;
}

.nav-time time {
    font-size: 1.25rem;
    display: flex;
    justify-content: flex-end;
}

</style>