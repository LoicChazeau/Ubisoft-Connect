<template>
  <div class="flex flex-row justify-between py-1" style="background-color: #121419">
    <p class="text-neutral-400 ml-2"><span class="font-bold">UBISOFT</span> CONNECT</p>
    <div class="flex space-x-7 mr-3.5">
      <img class="w-3 cursor-pointer" src="../assets/reduce.svg">
      <img class="w-3 cursor-pointer" src="../assets/lower.svg">
      <img class="w-3 cursor-pointer" src="../assets/close.svg">
    </div>
  </div>
  <div class="flex flex-row justify-between" style="background-color: #161a1f">
    <div class="flex items-center space-x-8 ml-10 font-semibold text-blue text-lg">
      <img class="w-4 mr-2 cursor-pointer" src="../assets/burger.svg">
      <p class="titleHeader cursor-pointer">Actualités</p>
      <p class="text-gray-100 cursor-pointer">Mes jeux</p>
      <p class="titleHeader cursor-pointer">Store</p>
      <p class="titleHeader cursor-pointer">Ubisoft+</p>
      <p class="titleHeader cursor-pointer">Promo du Nouvel An Lunaire !</p>
    </div>
    <div class="flex">
      <div class="flex">
        <img class="w-3" src="../assets/close.svg">
        <img class="w-3" src="../assets/close.svg">
        <img class="w-3" src="../assets/close.svg">
        <img class="w-3" src="../assets/close.svg">
      </div>
      <div class="flex">
        <div>
          <img class="w-3" src="../assets/close.svg">
        </div>
        <div>
          <p>Codyx73</p>
          <p>Niveau 22</p>
        </div>
        <div></div>
        <div>
          <div class="flex flex-row">
            <img class="w-3" src="../assets/close.svg">
            <p>0.00</p>
          </div>
          <div class="flex flex-row">
            <img class="w-3" src="../assets/close.svg">
            <p>330</p>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class=""></div>
</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: 'home',
}
</script>

<style>
img:hover {
  filter: brightness(0) invert(1);
}
.text-blue {
  color: #55aaff;
}
.titleHeader:hover {
  color: #b7d8f9;
}
</style>
