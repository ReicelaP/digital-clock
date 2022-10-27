<template>
  <DigitalClock />
</template>

<script>
import DigitalClock from "./components/DigitalClock.vue";
export default {
  name: "App",
  components: {
    DigitalClock: DigitalClock,
  },
};
</script>

<style>
#app {
  width: 100vw;
  height: 100vh;
  padding-top: 5px;
  background-image: url("https://images.pexels.com/photos/4367584/pexels-photo-4367584.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2");
}

.time-date {
  font-family: Lucida Console, Arial;
  text-align: center;
  margin-top: 200px;
  color:rgb(199, 236, 236);
  font-weight: bold;
  font-size: 60px;
}
</style>