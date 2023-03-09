<script lang="ts"></script>

<template>
  <div id="home">
    <h1>The Colours of the Afterlife</h1>
    <div class="box-container">
      <div class="black-box blazingStar"></div>
    </div>

    <div id="story">
      <p>Why are we so compelled to record memories, moments in time...?</p>
      <p>
        We create physical and digital snapshots — pictures and screenshots — of
        these moments. Although unintended (on our part), over time, something — or
        someone — has begun what I might consider a sinister chain of events if I
        were so inclined. These images, once taken, become self-contained worlds
        sharing a common history with our world.
      </p>
      <p>
        The crucial point of this disclosure: each recorded moment becomes the
        afterlife for someone who expired at that exact juncture, and their addition
        to that point results in a divergence from the true events in the real world.
      </p>
      <p>
        I must choose a successor to carry on this dreary duty. You may choose to
        refuse, and I hope that you do, for I do not wish this upon any one else.
        You must now be the gatekeeper of these worlds, and shepherd these
        newly-dead souls. All you need to know is as follows:
      </p>
      <p>
        The color codes of the three most dominant colours in any image are
        keys that unlock access to major turning points in the afterlife of
        the human absorbed into the image. You must generate and hand them
        these keys to help them on their journey beyond.
      </p>
      <p>
        “During his lifetime, Caesar was regarded as one of the best orators
        and prose authors in Latin—even Cicero spoke highly of Caesar's
        rhetoric and style. Only Caesar's war commentaries have survived.”
        <a href="https://en.wikipedia.org/wiki/Julius_Caesar#Literary_works">
          This quote</a> is all the clue I can give you. You must find specific kinds
        of images to generate colour codes that unlock access to the lost works of
        Caesar. These codes are critical for generating the exact keys needed to
        traverse the image worlds.
      </p>
    </div>
    <section id="level-list">
      <h2>Levels</h2>
      <p><a href="">Level 1: The Lost Works of Caesar</a></p>
      <p><a href="">Level 2: The Shepherd</a></p>
    </section>
  </div>
</template>

<style scoped>

#home {
  min-height: 100vh;
  width: 100%;
  color: white;
  background-color: black;
  padding-bottom: 4em;
}

h1 {
  margin-top: 0;
  padding-top: 1.5em;
  font-family: Roboto Mono, Consolas, monospace;
}

.box-container {
  height: 20vh;
  width: 100%;
  color: white;
  display: flex;
  justify-content: center;
  flex-direction: column;
  align-items: center;
}

.black-box {
  height: 75px;
  width: 75px;
  background: linear-gradient(30deg, #2c3e50, #34495e);
  border-radius: 12px;
  box-shadow: 0px 10px 40px rgb(255 255 200 / 30%);
  text-align: center;
  vertical-align: middle;
  line-height: 150px;
  font-size: 24px;
  animation-fill-mode: both;
}

/* blazingStar animation from woah.css @ https://www.joerezendes.com/projects/Woah.css/ */
@keyframes blazingStar {
  1% {
    border-radius: none;
    box-shadow: 0px 0px 40px rgba(255, 255, 0, .6);
    transform: scale(1);
  }

  10% {
    box-shadow: 0px 0px 0px;
    /*border-radius: 50%;*/
    transform: scale(1);
  }

  20% {
    box-shadow: 0px 0px 120px rgba(255, 255, 0, .6);
    /*border-radius: 50%;*/
    transform: scale(1);
  }

  30% {
    box-shadow: 0px 0px 0px;
    /*border-radius: 50%;*/
    transform: scale(1);
  }

  40% {
    box-shadow: 0px 0px 120px rgba(255, 255, 0, .6);
    /*border-radius: 50%;*/
    transform: scale(1);
  }

  50% {
    box-shadow: 0px 0px 0px;
    /*border-radius: 50%;*/
    transform: scale(1);
  }

  60% {
    box-shadow: 0px 0px 20vh rgba(255, 255, 0, 1);
    /*border-radius: 50%;*/
    transform: scale(1);
  }

  70% {
    box-shadow: 0px 0px 0px;
    /*border-radius: 50%;*/
    transform: scale(1);
  }

  80% {
    box-shadow: 0px 0px 20vh rgba(255, 255, 0, 1);
    /*border-radius: 50%;*/
    transform: scale(1);
  }

  90% {
    box-shadow: 0px 0px 0px;
    /*border-radius: 50%;*/
    transform: scale(1);
  }

  99% {
    box-shadow: 0px 0px 20vh rgba(255, 255, 0, 1);
    /*border-radius: 50%;*/
    transform: scale(1.1);
  }
}

.blazingStar {
  animation-timing-function: ease-out;
  transform-origin: bottom center;
  animation-name: blazingStar;
  animation-duration: 5s;
  animation-iteration-count: infinite;
}

#story {
  margin-top: 6em;
}

#story p {
  width: 70%;
  margin: 0.8em auto 0.5em auto;
  font-size: 1.2em;
  font-family: Roboto Mono, Consolas, monospace;
  padding: 0.8em;
  border-radius: 10px;
}

#level-list {
  margin-top: 2.8em;
  display:flex;
  justify-content:center;
  flex-direction: column;
}

#level-list p {
  margin-bottom: 1.5em;
}

#level-list p {
  font-size: 1.2em;
  font-family: Roboto Mono, Consolas, monospace;
  border-radius: 10px;
}

a {
  color: tomato;
}

a:hover {
  color: white;
}
</style>
