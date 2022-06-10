<template>
  <main>
    <section class="section-hero">
      <div class="section-content">
        <picture class="overview-hero">
          <img src="../assets/hero1pic.png" alt="" />
        </picture>
        <div class="detail-container">
          <picture class="overview-hero-logo">
            <img src="../assets/hero-logo.png" alt="" />
          </picture>
        </div>
        <p class="subhead">
          Introducing the all-new MacBook&nbsp;Air and 13-inch MacBook&nbsp;Pro,
          now supercharged with the Apple&nbsp;M2&nbsp;chip. And preview
          exciting updates to iOS, iPadOS, macOS and watchOS — packed with
          all-new features and capabilities.
        </p>
        <a
          href="/uk/apple-events/"
          class="button"
          aria-label="Watch the keynote"
          data-analytics-title="watch the keynote"
          >Watch the keynote</a
        >
      </div>
    </section>
    <section class="section-macbook-air">
      <div class="section-content section-padding">
        <h2 class="headline">MacBook&nbsp;Air</h2>
        <picture class="overview-macbook">
          <img src="../assets/macbookair.jpg" alt="" />
        </picture>
        <p class="subhead">
          All-new strikingly thin design and next-generation M2&nbsp;chip.
          Featuring a beautiful Liquid&nbsp;Retina&nbsp;display, 1080p
          FaceTime&nbsp;HD camera, four-speaker sound system and up to
          18&nbsp;hours of battery life.
        </p>
      </div>
    </section>
  </main>
</template>

<style scoped>
.section-macbook-air {
  background: #fff;
}
.section-macbook-air .headline {
  margin-bottom: 50px;
}
.overview-macbook {
  display: block;
  width: 688px;
  height: 688px;
}
.section-macbook-air .subhead {
  margin-top: 70px;
  max-width: 565px;
}

/*  */
.section-padding {
  padding: 167px 0 180px;
}
.headline {
  font-size: 72px;
  line-height: 1;
  font-weight: 600;
  letter-spacing: -0.012em;
}
.subhead {
  font-size: 24px;
  line-height: 1.3334133333;
  font-weight: 400;
  letter-spacing: 0.009em;
  margin-bottom: 18px;
}

/* Hero-section */
.section-hero {
  background: linear-gradient(#020d1f 16%, black 35%);
  min-height: 1160px;
  color: #f5f5f7;
}
.section-hero .section-content {
  height: 100%;
}
.section-content {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  overflow: hidden;
  text-align: center;
}
.overview-hero {
  display: block;
  width: 944px;
  height: 725px;
  margin-top: -125px;
}
.section-content .detail-container {
  margin-top: -110px;
}
picture img {
  width: 100%;
}
.section-hero .overview-hero-logo {
  margin-left: auto;
  margin-right: auto;
  margin-bottom: 25px;
}
.overview-hero-logo {
  display: block;
  width: 425px;
  height: 79px;
}
.section-hero .subhead {
  font-weight: 600;
  color: #c6e2e6;
  max-width: 630px;
}
.section-content .button {
  font-size: 17px;
  line-height: 1.1764805882;
  font-weight: 600;
  background: none;
  color: #c6e2e6;
  border: 2px solid;
  border-radius: 980px;
  border-color: #c6e2e6;
  transition: background-color 0.4s ease-in-out, color 0.4s ease-in-out;
  min-width: 26px;
  padding: 12px 22px;
  cursor: pointer;
  display: inline-block;
  text-align: center;
}
.section-hero .button:hover {
  background-color: #c6e2e6;
  color: #000;
}

@media only screen and (max-width: 734px) {
  .overview-hero {
    width: 366px;
    height: 289px;
    margin-top: -46px;
  }
  .section-content .detail-container {
    margin-top: -47px !important;
  }
  .overview-hero-logo {
    width: 238px;
    height: 44px;
  }
  .subhead {
    max-width: 360px;
  }
  .section-hero {
    min-height: 100vh;
  }
  .overview-macbook {
    width: 278px;
    height: 278px;
  }
}
/* @media only screen and (max-width: 1068px) {
  .overview-macbook {
    width: 688px;
    height: 688px;
  }
} */
</style>
