<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
  <HelloWorld msg="Echarts" />
  <EchartsSankey3 />
  <Echarts />
  <EchartsLine />
  <EchartsSankey />
  <EchartsSankey2 />
  <!-- <TreeMap /> -->
</template>

<script>
import HelloWorldVue from "./components/HelloWorld.vue";
import Echarts from "./components/Echarts.vue";
import EchartsLine from "./components/EchartsLine.vue";
import EchartsSankey from "./components/EchartsSankey.vue";
import EchartsSankey2 from "./components/EchartsSankey2.vue";
import EchartsSankey3 from "./components/EchartsSankey3.vue";
// import TreeMap from "./components/TreeMap.vue";

export default {
  name: "App",
  components: {
    HelloWorld: HelloWorldVue,
    Echarts,
    EchartsLine,
    EchartsSankey,
    EchartsSankey2,
    EchartsSankey3,
    // TreeMap,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
