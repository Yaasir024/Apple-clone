<template>
  <nav>
    <div class="nav-content">
      <ul class="nav-links-container">
        <li class="nav-link">
          <span class="apple-icon">
            <svg
              enable-background="new 0 0 14 44"
              height="44"
              viewBox="0 0 14 44"
              width="14"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path d="m0 0h14v44h-14z" fill="none" />
              <path
                d="m13.0729 17.5214c-.093.0723-1.7248.9915-1.7248 3.0364 0 2.3651 2.0759 3.2017 2.1379 3.2223-.0103.0516-.3305 1.1464-1.0948 2.2618-.6816.9812-1.3943 1.9623-2.4787 1.9623s-1.3633-.63-2.613-.63c-1.2187 0-1.6525.6507-2.644.6507s-1.6835-.9089-2.4787-2.0243c-.9192-1.3117-1.6628-3.3463-1.6628-5.2776 0-3.0984 2.014-4.7406 3.9969-4.7406 1.0535 0 1.9313.692 2.5923.692.63 0 1.6112-.7333 2.8092-.7333.4545.0001 2.0864.0415 3.1605 1.5803zm-3.7284-2.8918c.4957-.5887.8469-1.4046.8469-2.2205 0-.1136-.0103-.2272-.031-.3202-.8056.031-1.7661.5371-2.3445 1.2084-.4544.5164-.8779 1.3323-.8779 2.1586 0 .1239.0207.2479.031.2892.0516.0103.1343.0207.2169.0207.723-.0001 1.6318-.4855 2.1586-1.1362z"
                fill="#fff"
              />
            </svg>
          </span>
        </li>
        <li class="nav-link">
          <span>Store</span>
        </li>
        <li class="nav-link">
          <span>Mac</span>
        </li>
        <li class="nav-link">
          <span>iPad</span>
        </li>
        <li class="nav-link">
          <span>iPhone</span>
        </li>
        <li class="nav-link">
          <span>Watch</span>
        </li>
        <li class="nav-link">
          <span>AirPods</span>
        </li>
        <li class="nav-link">
          <span>TV & Home</span>
        </li>
        <li class="nav-link">
          <span>Only on Apple</span>
        </li>
        <li class="nav-link">
          <span>Accessories</span>
        </li>
        <li class="nav-link">
          <span>Support</span>
        </li>
        <li class="nav-link">
          <span>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 512 512"
              width="13"
              fill="#fff"
            >
              <path
                d="M500.3 443.7l-119.7-119.7c27.22-40.41 40.65-90.9 33.46-144.7C401.8 87.79 326.8 13.32 235.2 1.723C99.01-15.51-15.51 99.01 1.724 235.2c11.6 91.64 86.08 166.7 177.6 178.9c53.8 7.189 104.3-6.236 144.7-33.46l119.7 119.7c15.62 15.62 40.95 15.62 56.57 0C515.9 484.7 515.9 459.3 500.3 443.7zM79.1 208c0-70.58 57.42-128 128-128s128 57.42 128 128c0 70.58-57.42 128-128 128S79.1 278.6 79.1 208z"
              /></svg
          ></span>
        </li>
        <li class="nav-link">
          <span class="cart-icon">
            <svg
              height="44"
              viewBox="0 0 13 44"
              width="13"
              xmlns="http://www.w3.org/2000/svg"
            >
              <g fill="none" fill-rule="evenodd">
                <path d="m0 44h13v-44h-13z" />
                <path
                  d="m12 25.9c0 .6-.5 1.1-1.1 1.1h-8.8c-.6 0-1.1-.5-1.1-1.1v-7.9c0-.5.5-1 1.1-1h8.9c.6 0 1.1.5 1.1 1.1v7.8zm-5.5-11.9c1.2 0 2.1.9 2.3 2h-4.6c.2-1.1 1.1-2 2.3-2zm4.4 2h-1.1c-.2-1.7-1.6-3-3.3-3s-3.1 1.3-3.3 3h-1.1c-1.2 0-2.1.9-2.1 2.1v7.9c0 1.1.9 2 2.1 2h8.9c1.1 0 2.1-.9 2.1-2.1v-7.9c-.1-1.1-1-2-2.2-2z"
                  fill="#fff"
                />
              </g></svg
          ></span>
        </li>
      </ul>
    </div>
  </nav>
</template>

<style scoped>
nav {
  background: rgba(0, 0, 0, 0.92);
  height: 48px;
  color: rgb(245, 245, 247);
}
.nav-content {
  max-width: 980px;
  margin: 0 auto;
  padding: 0 22px;
}
.nav-links-container {
  cursor: default;
  margin: 0 -8px;
  padding-left: 0;
  width: auto;
  height: 44px;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: justify;
  align-items: center;
  -ms-flex-pack: justify;
  justify-content: space-between;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  list-style: none;
}
.nav-link {
  cursor: pointer;
}
.nav-link:hover {
    color: #fff;
}
.nav-link span {
  font-size: 12px;
  font-weight: 400;
}
.nav-link .apple-icon {
  opacity: 0.8;
  margin-top: 10px;
}
.nav-link .apple-icon svg {
  margin-top: 10px;
}
.nav-link .cart-icon svg {
  margin-top: 10px;
}
</style>
