<template>
  <section class="holdAll">
    <div class="holdAll2">
      <div class="holdPage">
        <h1>Shape</h1>
        <p class="logout" @click="test">Logout</p>
      </div>
      <div>
        <h1>Filters</h1>
        <p class="shape">Shapes</p>
        <div>
          <button class="filterButin">Oval</button>
          <button class="filterButin">Rounds</button>
          <button class="filterButin">Triangle</button>
          <button class="filterButin">Square</button>
          <button class="filterButin">Rectangle</button>
        </div>
        <p class="colors">Colors</p>
        <div class="holdColor">
          <div class="colorRed"></div>
          <div class="colorBlue"></div>
          <div class="colorGreen"></div>
          <div class="colorYellow"></div>
          <div class="colorLightBlue"></div>
          <div class="colorGray"></div>
        </div>
        <div>
          <p><span>All oval items: (6)</span></p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "LandPage",
  methods: {
    test() {
      alert("Login screen is available");
    },
  },
};
</script>

<style scoped>
* {
  font-family: Arial, Helvetica, sans-serif;
}
.holdPage {
  width: 100%;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logout {
  color: tomato;
  font-family: 15px;
  font-weight: 600;
  cursor: pointer;
  transition: 0.5s;
}

.logout:hover {
  background-color: tomato;
  color: white;
  padding: 5px 15px;
  font-family: 15px;
  border-radius: 4px;
}

.holdAll {
  width: 100%;
  display: flex;
  justify-content: center;
}
.holdAll2 {
  width: 50%;
  display: flex;
  justify-content: center;
  flex-direction: column;
}

.shape {
  color: #3acfff;
  font-size: 18px;
  font-weight: bold;
}

.filterButin {
  font-size: 16px;
  padding: 5px 20px;
  border-radius: 50px;
}

.colors {
  color: #3acfff;
  font-size: 15px;
  margin-top: 30px;
}

.colorRed {
  width: 50px;
  height: 50px;
  background-color: red;
  border-radius: 50px;
}
.colorBlue {
  width: 50px;
  height: 50px;
  background-color: blue;
  border-radius: 50px;
}
.colorGreen {
  width: 50px;
  height: 50px;
  background-color: green;
  border-radius: 50px;
}
.colorYellow {
  width: 50px;
  height: 50px;
  background-color: yellow;
  border-radius: 50px;
}
.colorLightBlue {
  width: 50px;
  height: 50px;
  background-color: lightblue;
  border-radius: 50px;
}
.colorGray {
  width: 50px;
  height: 50px;
  background-color: gray;
  border-radius: 50px;
}

.holdColor {
  display: flex;
  justify-content: space-between;
  width: 50%;
}
</style>
