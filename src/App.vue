<script setup>
import MyNev from './components/MyNev.vue'
import MyCard from './components/MyCard.vue'
import MyFooter from './components/MyFooter.vue'
import items from './cat.json'
</script>

<template>
  <header>
    <MyNev />
  </header>

  <main>
    <h1>12 สายพันธ์ุแมวยอดนิยม</h1>
    <div className="grid-container">
      <MyCard v-bind="items[0]" />
      <MyCard v-bind="items[1]" />
      <MyCard v-bind="items[2]" />
      <MyCard v-bind="items[3]" />
      <MyCard v-bind="items[4]" />
      <MyCard v-bind="items[5]" />
      <MyCard v-bind="items[6]" />
      <MyCard v-bind="items[7]" />
      <MyCard v-bind="items[8]" />
      <MyCard v-bind="items[9]" />
      <MyCard v-bind="items[10]" />
      <MyCard v-bind="items[11]" />
    </div>
   
  </main>
  <MyFooter /> 
</template>

<style scoped>
main{
  /* background-color: ; */
}
.grid-container {
  display: grid ;
  grid-column-gap: 0.5rem;
  grid-row-gap: 0.5rem;
}
@media (min-width: 576px) {
  .grid-container { grid-template-columns: repeat(1, 1fr); }
}
@media (min-width: 992px) {
  .grid-container { grid-template-columns: repeat(3, 1fr); }
}
h1 {
  margin-top: 10px;
  margin-bottom: 10px ;
  color: #000;
  text-align: center;
}

</style>
