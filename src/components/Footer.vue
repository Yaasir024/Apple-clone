<template>
  <footer>
    <div class="footer-content">
      <section class="footnotes">
        <p>
          Features are subject to change. Some features, applications and
          services may not be available in all regions or languages.
        </p>
      </section>
      <nav class="footer-nav">
        <div class="nav-section">
          <ul class="section-list">
            <li class="section-item">
              <a href="#">Shop</a>
            </li>
            <li class="section-item">
              <a href="#">Mac</a>
            </li>
            <li class="section-item">
              <a href="#">iPad</a>
            </li>
            <li class="section-item">
              <a href="#">iPhone</a>
            </li>
            <li class="section-item">
              <a href="#">Watch</a>
            </li>
            <li class="section-item">
              <a href="#">AirPods</a>
            </li>
            <li class="section-item">
              <a href="#">TV & Home</a>
            </li>
            <li class="section-item">
              <a href="#">AirTag</a>
            </li>
            <li class="section-item">
              <a href="#">Accessories</a>
            </li>
            <li class="section-item">
              <a href="#">Gift Cards</a>
            </li>
          </ul>
        </div>
      </nav>
      <section class="footer-extra">
        <div class="footer-shop">
          <p class="footer-shop-details">
            More ways to shop:
            <a href="/uk/retail/" data-analytics-title="find an apple store"
              >find an Apple Store</a
            >
            or
            <a
              href="https://locate.apple.com/uk/en/"
              data-analytics-title="other retailers or resellers"
              data-analytics-exit-link=""
              >other retailer</a
            >
            near you. <span class="nowrap">Or call 0800 048 0408.</span>
          </p>
        </div>
        <div class="footer-legal">
          <div class="footer-copyright">
            <p>Copyright © 2022 Apple Inc. All rights reserved.</p>
          </div>
          <div class="footer-legal-links">
            <a class="footer-legal-link" href="#">Privacy Policy</a>
            <a class="footer-legal-link" href="#">Use of Cookies</a>
            <a class="footer-legal-link" href="#">Terms of Use</a>
            <a class="footer-legal-link" href="#">Sales and Refunds</a>
            <a class="footer-legal-link" href="#">Legal</a>
            <a class="footer-legal-link" href="#">Site Map</a>
          </div>
        </div>
      </section>
    </div>
  </footer>
</template>

<style scoped>
footer {
  font-size: 12px;
  line-height: 1.33337;
  font-weight: 400;
  letter-spacing: -0.01em;
  background: #1d1d1f;
  color: #6e6e73;
  min-width: 1024px;
  overflow: hidden;
  position: relative;
  z-index: 1;
}
.footer-content {
  margin: 0 auto;
  max-width: 980px;
  padding: 0 22px;
}
.footnotes {
  border-bottom: 1px solid var(--footer-border-color);
  padding: 17px 0 11px;
}
.footer-nav {
  font-size: 12px;
  line-height: 1.33337;
  font-weight: 400;
  letter-spacing: -0.01em;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -ms-flex-wrap: nowrap;
  flex-wrap: nowrap;
  padding-top: 20px;
}
.footer-nav {
  -ms-flex-preferred-size: 25%;
  flex-basis: 25%;
}
.footer-nav .section-list {
  margin-right: 20px;
  list-style: none;
  padding: 0;
}
.section-item {
  display: block;
  margin-bottom: 0.8em;
}
.section-item a {
  color: var(--footer-link-color);
  text-decoration: none;
}
.footer-extra {
  margin-top: 35px;
}
.footer-shop {
  border-bottom: 1px solid var(--footer-border-color);
  margin-bottom: 7px;
  padding-bottom: 8px;
}
.footer-legal {
  margin-bottom: 50px;
}
.footer-copyright {
  display: inline-block;
  margin-right: 30px;
}
.footer-legal-links {
  display: inline-block;
}
.footer-legal-link {
  border-right: 1px solid var(--footer-border-color);
  color: var(--footer-link-color);
  text-decoration: none;
  margin-right: 7px;
  padding-right: 10px;
  display: inline-block;
  margin-top: 5px;
  white-space: nowrap;
}

@media only screen and (max-width: 1044px) {
  footer {
    min-width: 320px;
  }
}
</style>
