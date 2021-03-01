<template>
  <div>
    {{num}}
    <button @click="num++">Кнопка</button>
    <Navigation/>
  </div>

</template>

<script>
export default {
  name: "categories",
data: function (){
    return {
      num: 1234
    }
}
}
</script>

<style scoped>

</style>
