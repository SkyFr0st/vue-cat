<template lang="">
    <div class="card">
        <img :src="image" alt="name" style="width:100%">
        <div class="container">
          <h2><b>{{ name }}</b></h2>
          <p>ลักษณะนิสัย : {{ habbit }}</p>
        </div>
    </div>
</template>

<script>
export default {
    props: ['name', 'habbit', 'image']
}
</script>

<style scoped>
h2 {
    color: #000;
    font-size: 20px;
}

p{
    font-size: 17px;
    margin-top: 10px ;
    color: #914F1E;
}

.card {
  background-color: #F7DCB9;
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.6);
  transition: 0.3s;
  width: 95%;
  padding: 25px;
  margin-left: auto;
  margin-right: auto;
  
}

.card:hover {
  box-shadow: 0 8px 16px 0 rgba(0,0,0,0.9);
}

.container {
  padding: 2px 16px;
}
</style>