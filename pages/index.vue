<template>
  <div>
    <section id="section-1" class="default">
      <header>
        <div class="logo"></div>
        <nav></nav>
      </header>
      <div class="logo"></div>
    </section>
    <section id="section-2" class="default colored">
      <article>
        <p class="main-title">
          "L’unica regola è non essere noiosi e vestire bene ovunque si vada.
        </p>
        <p class="main-title">
          La vita è troppo breve per passare inosservati."
        </p>
      </article>
    </section>
    <section class="default">
      <article class="h2-block">
        <h2>LE NOSTRE CERTIFICAZIONI</h2>
        <div class="subtext">unici in Trentino Alto-Adige</div>
      </article>
      <article class="swimlane">
        <div class="card">
          <img src="~/assets/images/card1.png" alt="card 1" />
          <div class="card-text">
            <div class="card-title">3M</div>
            <div class="card-description">text</div>
          </div>
        </div>
        <div class="card">
          <img src="~/assets/images/card2.png" alt="card 2" />
          <div class="card-text">
            <div class="card-title">3M</div>
            <div class="card-description">text</div>
          </div>
        </div>
        <div class="card">
          <img src="~/assets/images/card3.png" alt="card 3" />
          <div class="card-text">
            <div class="card-title">3M</div>
            <div class="card-description">text</div>
          </div>
        </div>
      </article>
    </section>
    <section>
      <div id="car-animation">
        <img src="~/assets/images/delorean_no_fx.png" width="1200px" />
      </div>
      <div id="car-animation-text">
        <h2>CAR WRAPPING</h2>
        <div class="subtext">identity &amp; Protection</div>
      </div>
    </section>
    <section class="default colored">
      <article>
        <h2>I NOSTRI CLIENTI</h2>
        <div class="links-section">
          <h3>HOTELLERIE</h3>
          <div class="links-list">
            <a href="#">Gruppo Starhotel</a>
            <a href="#">Atahotel</a>
            <a href="#">Audi</a>
            <a href="#">Allianz</a>
          </div>
        </div>
        <div class="links-section">
          <h3>CLIENTI LOCALI</h3>
          <div class="links-list">
            <a href="#">HGV</a>
            <a href="#">Sudtiroler Bauerbund</a>
            <a href="#">Loacker</a>
            <a href="#">Forst</a>
          </div>
        </div>
        <div class="links-section">
          <h3>NAUTICA</h3>
          <div class="links-list">
            <a href="#">Gruppo Ferretti</a>
            <a href="#">Molteni</a>
            <a href="#">San Lorenzo Yacht</a>
            <a href="#">Fincantieri</a>
          </div>
        </div>
        <div class="links-section">
          <h3>MODA</h3>
          <div class="links-list">
            <a href="#">Gucci</a>
            <a href="#">Patrizia Pepe</a>
            <a href="#">Armani</a>
          </div>
        </div>
      </article>
      <article>
        <h2>I NOSTRI PARTNER</h2>
        <div class="links-section">
          <a href="#"><img /></a>
        </div>
        <div class="links-section">
          <a href="#"><img /></a>
        </div>
        <div class="links-section">
          <a href="#"><img /></a>
        </div>
      </article>
      <article>
        <h2>EVENTI</h2>
        <div class="links-section">
          <div class="links-list">
            <a href="#">Viscom</a>
            <a href="#">Made</a>
            <a href="#">Eventi 3M</a>
            <a href="#">Sicam</a>
          </div>
        </div>
      </article>
    </section>
    <section class="default">
      <article>
        <img />
      </article>
      <article>
        <a href="#">info@schriftart.it</a>
        <div class="bold">SchriftArt s.r.l.</div>
        <div class="address-group">
          <div class="address-title bold">Corporate Design</div>
          <div class="address">
            Via Rosmini 20,<br />
            39100 Bolzano Italia<br />
            T 0471 324 953
          </div>
        </div>
        <div class="address-group">
          <div class="address-title bold">Wrapping Division</div>
          <div class="address">
            Via Buozzi 9c,<br />
            39100 Bolzano Italia<br />
            T 0471 324 953
          </div>
        </div>
      </article>
    </section>
  </div>
</template>
<script>
import '~/assets/images/card1.png'
import '~/assets/images/card2.png'
import '~/assets/images/card3.png'
export default {
  components: {},
}
</script>
<style scoped>
h2 {
  font-size: 24px;
}

.main-title {
  font-size: 36px;
  margin-bottom: 48px;
}

.subtext {
  font-size: 16px;
  color: #646464;
}

.default {
  padding: 36px 18px 58px;
}

.colored {
  background-color: #dc0b31;
  color: white;
  padding: 50px 36px 100px;
}

.h2-block {
  width: 210px;
}

.swimlane {
  display: grid;
  grid-template-columns: repeat(3, 210px);
}

.card {
  width: 220px;
  margin-right: 10px;
}

.links-section {
  margin-top: 30px;
  opacity: 60%;
}

.links-list {
  display: flex;
  flex-direction: column;
  margin-top: 30px;
}

#section-1 {
  background-image: url('assets/images/section-1-background.png');
  background-position: 20%;
  background-size: cover;
  height: 667px;
}

#section-1 header {
  height: 78px;
  background: black;
}

#car-animation {
  position: relative;
  height: 370px;
}

#car-animation img {
  display: block;
  position: absolute;
  width: 1000px;
  left: -480px;
  top: -160px;
  max-width: 1000px;
}

#car-animation-text {
  width: 160px;
  margin-left: 36px;
  margin-bottom: 28px;
}
</style>
