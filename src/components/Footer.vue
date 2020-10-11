<template>
  <div>
    <footer>
      <div class="container-gral">
        <div class="links-right">
          <h3>Teaching center</h3>
          <h3>Roadmap</h3>
          <h3>Support</h3>
        </div>
      </div>
      <hr class="rounded" />
      <div class="container-contact">
        <h3 class="text-copyright">
          Numm Inc. 2569 Land Park Dr, Sacramento, CA 95818
          office@nummfinance.com +1-916-555-0184
        </h3>
      </div>
      <div class="container-year-socialmedia">
        <div class="year">
          <h3>
            © 2010 — 2020 Numm Inc.
          </h3>
        </div>
        <div class="socialmedia">
          <h3>
            Twitter
          </h3>
          <h3>
            Facebok
          </h3>
          <h3>
            Youtube
          </h3>
          <h3>
            Instagram
          </h3>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.socialmedia {
  display: flex;
}

.container-year-socialmedia {
  display: flex;
  justify-content: space-between;
}

.text-copyright {
  font-family: Roboto;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 20px;
}
.container-contact {
  width: 263px;
  height: 79px;
  left: 90px;
  top: 7251px;
}

/* Rounded border */
hr.rounded {
  width: 1260px;
  height: 0px;
  left: 90px;
  top: 7211px;
  border: 1px solid #000000;
}

.links-right {
  display: flex;
}

h3 {
  font-family: Roboto;
  font-style: normal;
  font-weight: bold;
  font-size: 14px;
  line-height: 20px;
  margin: 10px;
}

.container-gral {
  display: flex;
  justify-content: flex-end;
}
footer {
  position: absolute;
  height: 410px;
  left: 0px;
  top: 7023px;
  background: #f2f2f2;
}
</style>
