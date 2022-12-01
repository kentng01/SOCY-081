<template>
  <div>    
    <div class="mq-msg">
        <p>"Hey there! This site is currently not supported by your screen size."</p>
    </div>
    <main class="socy-main">
      <section class="title-sect">
        <h1>「 Final Paper Presentation 」</h1>
        <h2>K-Pop<font-awesome-icon class="x" icon="fa-solid fa-xmark" />Mental Health</h2>
        <h3>
          <a href="#2">
            <font-awesome-icon class="down" icon="fa-solid fa-angle-down" />
          </a>
        </h3>
      </section>

      <ZectTwo />
      <ZectThree />
      <ZectFour />
      <ZectFive />

    </main>
  </div>
</template>

<script>

export default {
  name: 'IndexPage',
}

</script>

<style scoped>

.socy-main {
  display: flex;
  justify-content: center;
  flex-direction: column;
  padding: 0 10rem;
}

.mq-msg{
  display: none;
}

.title-sect {
  height: calc(100vh - 3.5rem);
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.title-sect h1 {
  font-size: 4.5rem;
  font-family: 'Playfair Display', serif;
  text-align: center;
}

.title-sect h2 {
  font-size: 2.25rem;
  font-weight: 400;
  font-style: italic;
}

.x {
  font-size: 1.625rem;
  padding: 0 0.75rem 0 1rem
}

.down {
  margin-top: 7.5rem;
  font-size: 2.5rem;
  color: #fff;
  transition: 250ms;
}

.down:hover {
  transform: translateY(5px);
}

@media screen and (max-width: 767px) {
  .socy-main {
    display: none;
  }
  .mq-msg {
    display: block;
  }
  .mq-msg p {
    font-size: 2rem;
    font-weight: 600;
    font-family: 'Playfair Display', serif;
    font-style: italic;
    text-align: center;
  }
}

</style>



