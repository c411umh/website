<script>
  import Footer from "./Footer.svelte";
</script>

<main>
  <h1>
    <span>👋</span>
    Hello
  </h1>
  <p>💡 I'm a software engineer working in technology innovation.</p>
  <p>📍 London, UK</p>
  <a href="mailto:hello@callumhyland.com">📧 hello@callumhyland.com</a>

  <!-- Experience -->
  <h1>👨‍💻 Experience</h1>

  <i>SEP 2017 - ONGOING</i>
  <h2>Digital Catapult</h2>
  <h4>Senior Software Engineer, Advanced Digital Technologies</h4>
  <p>
    DC strives to enable Industry 4.0 in the UK by helping SME adopt advanced
    technologies. Engineering works to demonstrate these technologies, rapidly
    building prototypes for research and commercial clients covering IoT, AI,
    Blockchain, and Immersive technologies.
  </p>
  <p><a href="https://www.digicatapult.org.uk/">digicatapult.org.uk</a></p>

  <i>SEP 2015 - SEP 2017</i>
  <h2>Accenture</h2>
  <h4>Lead Developer</h4>
  <p>
    After university I joined the Innovation Programme and quickly earned the
    Lead Developer title for my work in Mobile before diving into Blockchain
    where I built prototypes and won a patent covering HSM integration.
  </p>
  <p><a href="https://www.accenture.com/">accenture.com</a></p>

  <!-- Skillz -->
  <h1>🧙‍♂️ Skills</h1>

  <h2>Languages</h2>
  <img src="images/typescript.svg" alt="TypeScript" />
  <img src="images/javascript.svg" alt="JavaScript" />
  <img src="images/python.svg" alt="Python" />

  <h2>Frameworks</h2>
  <img src="images/react.svg" alt="React" />
  <img src="images/svelte.svg" alt="Svelte" />

  <img src="images/graphql.png" alt="GraphQL" />
  <img src="images/nodejs.svg" alt="NodeJS" />
  <img src="images/lambda.svg" alt="Lambda" />

  <h2>Technologies</h2>
  <img src="images/docker.png" alt="Docker" />
  <img src="images/android.svg" alt="Android" />
  <img src="images/ios.svg" alt="iOS" />
  <img src="images/ethereum.png" alt="Ethereum" />
  <img src="images/unity.png" alt="Unity" />

  <!-- Education -->
  <h1>🎓 Education</h1>

  <i>SEP 2011 - SEP 2015</i>
  <h2>University of St Andrews</h2>
  <h4>B.Sc Computer Science (2:1)</h4>
  <p>
    My dissertation was a health app to aid smoking cessation using ML to
    predict the time/place a user would experience cravings, then use nudge
    theory to aid their resistance.
  </p>
  <p>
    The app was surprisingly effective, winning a £20k grant for NHS research.
    In the summer after graduation I released an improved version to the Play
    Store for free which reached #1 in Health & Fitness, with 50k downloads.
  </p>
  <p>
    <a href="https://www.st-andrews.ac.uk/subjects/computer-science/">
      st-andrews.ac.uk
    </a>
  </p>
</main>

<Footer />

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

  img {
    height: 50px;
  }

  @media (min-width: 640px) {
    main {
      max-width: 720px;
    }
  }
</style>
