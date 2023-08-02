<template>
  <div>
    <USPOPULATIONDATA />
  </div>
</template>

<script>
import USPOPULATIONDATA from './components/fetchPopulation.vue';
export default {
  components: {
    USPOPULATIONDATA
  }
};
</script>

<style>
button {
 padding: 12px 32px;
 font-size: 16px;
 border-radius: 8px;
}
.button:hover {
  background-color: green;
  transition: .4s;
}
.data ul{
  list-style-type: none;
  font-weight: bold;
  font-size: 18px;
  line-height: 30px;
  padding: 10px 0;
}
.table tr{
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 10px 10px;
}
</style>