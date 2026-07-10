<!-- <template>
  <h1>Counter: {{ counter }} </h1>
  <button @click="OnIncrement">+</button>
  <button @click="OnDecrement">-</button>
</template> -->
<template>
  <div class="page">
    <div class="card">
      <div class="border">
      </div>
      <div class="logo" data-aos="zoom-out" data-aos-duration="1000">A<span class="gulasal">G</span></div>

      <div class="names" data-aos="zoom-in" data-aos-duration="1000">Azamatjon va Gulasalxon</div>
      <div class="img-box">
        <img class="img-top" src="./images/top-img.svg" alt="">
      </div>

      <div class="text-box" data-aos="fade-up" data-aos-duration="500">
        <p class="text">
          <u>

            Hurmatli mehmonimiz!<br/>
          </u>
        Hayotimizning eng baxtli kunini biz bilan birga nishonlashga samimiy taklif etamiz. Tashrifingiz biz uchun katta sharaf.
        </p>
        
      </div>


      
      <div class="city">
        <img src="./images/ChatGPT Image 9 июл. 2026 г., 17_39_42.png" alt="">
      </div>
      <div class="next">
        <div class="date" data-aos="fade-up" data-aos-duration="500">Sana: 17/07/26</div>
      </div>
      <div class="hall" data-aos="fade-up" data-aos-duration="500">Juma kuni</div>
      
      <div class="info" data-aos="fade-up" data-aos-duration="500">
      <u>
 Mehmonlar yig‘ilishi <br />
      </u>  
        Farg'ona viloyati, Bag'dod tumani, <br>Cho'rindi qishlog'i, Navro'z ko'chasi, 2-uy
      </div>
      <div class="time" data-aos="fade-up" data-aos-duration="500">Vaqt :10:00</div>
      <div class="city">
        <iframe class="map" src="https://www.google.com/maps/embed?pb=!1m14!1m12!1m3!1d1054.1316989383529!2d71.18221400211446!3d40.45150447302654!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!5e0!3m2!1sru!2s!4v1783682771598!5m2!1sru!2s" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="strict-origin-when-cross-origin"></iframe>
      </div>
      <div class="img-box city">
        <img class="img" src="./images/ChatGPT Image 9 июл. 2026 г., 17_42_03.png" alt="">
      </div>
      <p class="next_text">Kechki bazm dasturxoni vaqti : <b>16:00</b> </p>
      <div class="map-title">To'yxona manzili</div>
      
      <p class="address" data-aos="fade-up" data-aos-duration="500">
        Farg'ona viloyati, Bag'dod tumani,<br> Qahramon ko'chasi, 619-uy
      </p>
      
      <a
        href="https://maps.app.goo.gl/cjNHUFFcdpV8R4Yr6"
        target="blank"
        class="button"
      >
      Google Lokatsiya 
      </a>
      <a
        href="https://yandex.uz/maps/-/CTBAqL8x"
        target="blank"
        class="button"
      >
        Yandex Lokatsiya
      </a>

      <p class="address" data-aos="fade-up" data-aos-duration="500">
        Sizni kutamiz😊!
      </p>

      <!-- <div class="map-box">
        <div class="pin"></div>
        <div class="map-text">"Nuru-Dur" To‘yxonasi</div>
      </div> -->
    </div>
  </div>
</template>

<script setup>

</script>

<style scoped>

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: cursive;
}

.page {
  background: #f8f4ec;
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
  padding: 20px;
}

.card {
  width: 100%;
  max-width: 450px;
  background: #fffdf9;
  border: 2px solid #e5c97b;
  border-radius: 30px;
  padding: 40px 25px;
  text-align: center;
  position: relative;
  overflow: hidden;
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
}

.border {
  position: absolute;
  inset: 10px;
  border: 1px solid #e5c97b;
  border-radius: 24px;
  pointer-events: none;
}
.img-box{
  width: 100%;
  max-width: 440px;
  padding-bottom: 20px;
  display: flex;
  align-items: center;
  border-bottom: 2px dashed #c89b2d;
}

.img-top{
  width: 100%;
  background-color:  #e5c97b;
}

.next{
  padding-top: 20px;
}

.next_text{
  /* position: relative; */
  font-size: 40px;
  padding-top: 40px;

}


.logo {
  padding-bottom: 10px;
  font-size: 60px;
  color: #c89b2d;
  font-family: 'Georgia', sans-serif !important;
  letter-spacing: 5px;
}
.logo span{
  font-family: 'Georgia', sans-serif;
}

.names {
   font-family: "Tangerine", cursive;
  font-size: 46px !important;
  font-style: normal;
  margin-top: 10px;
  /* padding-bottom: 350px; */
  color: #111;
  position: relative;
  
}
.gulasal{
  position: absolute;
  top: 20px;
  left: 47%;
}

.text {
  margin-top: 50px;
  font-size: 24px;
  line-height: 1.5;
  font-family: "Rancho", cursive;
  font-optical-sizing: auto;
  text-transform: uppercase;
  color: #333;
}

.date {
  position: relative;
  margin-top: 30px;
  margin-bottom: 30px;
  font-size: 60px;
  color: #000;
}

.hall {
  margin-top: 20px;
  margin-bottom: 30px;
  padding-bottom: 30px;
  border-bottom: 2px solid #c89b2d;
  /* border-bottom: 5px; */
  font-size: 28px;
  text-transform: uppercase;
  color: #444;
}

.city {
  width: 100%;
  max-width: 450px;
  margin-top: 10px;
  font-size: 50px;
  font-style: italic;
  color: #c89b2d;
}

.city img{
  width: 100%;
}

.time {
  margin-top: 20px;
  font-size: 60px;
  color: #000;
}

.info {
  margin-top: 20px;
  font-size: 24px;
  line-height: 1.7;
  color: #444;
}

.address {
  margin-top: 25px;
  font-size: 28px;
  line-height: 1.6;
  color: #000;
}
.map{
  width: 100%;
  height: 220px;
}

.button {
  display: inline-block;
  margin-top: 35px;
  padding: 16px 35px;
  border: 2px solid #d4af37;
  border-radius: 50px;
  text-decoration: none;
  color: #333;
  font-size: 22px;
  transition: 0.3s;
}

.button:hover {
  background: #f6e7b4;
}

.map-title {
  margin-top: 40px;
  font-size: 50px;
  font-style: italic;
  color: #c89b2d;
}

.map-box {
  margin-top: 30px;
  border: 2px dashed #e5c97b;
  border-radius: 30px;
  padding: 50px 20px;
}

.pin {
  width: 18px;
  height: 18px;
  background: #d4af37;
  border-radius: 50%;
  margin: auto;
  animation: bounce 1s infinite;
}

.map-text {
  margin-top: 20px;
  font-size: 24px;
  color: #555;
}

@keyframes bounce {
  0%,
  100% {
    transform: translateY(0);
  }
  50% {
    transform: translateY(-10px);
  }
}

@media (max-width: 500px) {
  .logo {
    font-size: 50px;
  }

  .names {
    font-size: 34px;
  }

  .text {
    font-size: 24px;
  }

  .date {
    font-size: 55px;
  }

  .hall {
    font-size: 22px;
  }

  .city {
    font-size: 40px;
  }

  .time {
    font-size: 50px;
  }

  .info {
    font-size: 20px;
  }

  .address {
    font-size: 18px;
  }
}
</style>

<script>
export default {
  data() {
    return{
      counter: 0,
    }
  },
  methods: {
    OnIncrement() {
      this.counter+=1
    },
    OnDecrement() {
      this.counter -=1
    },
  }
}
</script>

<style></style>