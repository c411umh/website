<script>
  import Focus from './Focus.svelte'
  import Experience from './Experience.svelte'
  import Education from './Education.svelte'
  import Skills from './Skills.svelte'
  import Footer from './Footer.svelte'
</script>

<style>
  main {
    margin: 0 auto;
  }

  h1 {
    text-align: center;
    color: #ff3e00;
    font-size: 3em;
    font-weight: 100;
  }

  a {
    line-height: 150%;
  }

  @media (min-width: 640px) {
    main {
      max-width: 720px;
    }
  }
</style>

<main>
  <h1>
    <span>👋</span>
    HELLO
  </h1>
  <p>💡 I'm a futurist working in technology innovation</p>
  <p>📍 London 🇬🇧</p>
  <a href="mailto:hello@callumhyland.com">📧 hello@callumhyland.com</a>
  <Focus/>
  <Experience />
  <Education />
  <Skills />
</main>

<Footer />
