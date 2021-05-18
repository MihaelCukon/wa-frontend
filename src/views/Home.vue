<template>
  <div class="row">
    <p class="naslov">P o n u d a - p o s l o v a</p>
    <div class="col-3"></div>
    <div class="col-6">
      <div class="card text-white bg-dark mb-3" style="max-width: 50rem;">
        <div class="card-header">GLOBALNA HRANA I PICE D.O.O</div>
        <div class="card-body">
          <h5 class="card-title">Radnik/ca u restoranu</h5>
          <div class="row">
            <div class="col-4">
              <img class="clock" src="@/assets/clock.png" />
              <p>18.05.2021</p>
            </div>
            <div class="col-4">
              <img class="clock" src="@/assets/location.jpg" />
              <p>Ulica grada Pule</p>
            </div>
            <div class="col-4">
              <img class="clock" src="@/assets/kasica.jpg" />
              <p>30kn/h</p>
            </div>
          </div>
        </div>
        <b-button
          pill
          variant="dark"
          class="btn btn-secondary"
          style="height=50px"
          data-bs-toggle="button"
          autocomplete="off"
          @click="GoToNext1"
          >Vidi više informacija</b-button
        >
      </div>
      <div class="card text-white bg-dark mb-3" style="max-width: 50rem;">
        <div class="card-header">4 C D.O.O.</div>
        <div class="card-body">
          <h5 class="card-title">Konobar/ica</h5>
          <div class="row">
            <div class="col-4">
              <img class="clock" src="@/assets/clock.png" />
              <p>21.05.2021</p>
            </div>
            <div class="col-4">
              <img class="clock" src="@/assets/location.jpg" />
              <p>Vukovarska ulica</p>
            </div>
            <div class="col-4">
              <img class="clock" src="@/assets/kasica.jpg" />
              <p>28kn/h</p>
            </div>
          </div>
        </div>
        <b-button
          pill
          variant="dark"
          class="btn btn-secondary"
          style="height=50px"
          data-bs-toggle="button"
          autocomplete="off"
          @click="GoToNext2"
          >Vidi više informacija</b-button
        >
      </div>
      <div class="card text-white bg-dark mb-3" style="max-width: 50rem;">
        <div class="card-header">NAVIGAR J.D.O.O</div>
        <div class="card-body">
          <h5 class="card-title">Prodajni agent /-ica</h5>
          <div class="row">
            <div class="col-4">
              <img class="clock" src="@/assets/clock.png" />
              <p>22.05.2021</p>
            </div>
            <div class="col-4">
              <img class="clock" src="@/assets/location.jpg" />
              <p>Zagrebačka ulica</p>
            </div>
            <div class="col-4">
              <img class="clock" src="@/assets/kasica.jpg" />
              <p>50kn/h</p>
            </div>
          </div>
        </div>
        <b-button
          pill
          variant="dark"
          class="btn btn-secondary"
          style="height=50px"
          data-bs-toggle="button"
          autocomplete="off"
          @click="GoToNext3"
          >Vidi više informacija</b-button
        >
      </div>
    </div>
    <div class="col-3"></div>
  </div>
</template>

<script>
export default {
  methods: {
    GoToNext1() {
      this.$router.push("/GlobalnaHrana");
    },
    GoToNext2() {
      this.$router.push("/Konobar");
    },
    GoToNext3() {
      this.$router.push("/ProdajniAgent");
    },
  },
};
</script>

<style scoped>
.clock {
  height: 20px;
  width: 20px;
}
.naslov {
  font-size: 45px;
}
.btn:hover {
  box-shadow: 0px 4px 4px rgba(49, 49, 49, 0.5);
}
.card-body {
  padding-bottom: 0px;
}
</style>
