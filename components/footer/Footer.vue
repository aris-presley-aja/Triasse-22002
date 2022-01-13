<template>

  <div class="footer">
    <div class="columns container">
      <div class="column">
        <p>Berlangganan newsletter spesial promo dan penawaran</p>
      </div>
    <div class="column has-text-right">
      <p>Vuemmerce | Made with ❤ By Aris Priyanto</p>
    </div>
    </div>
  </div>


</template>

<script>
export default {
  name: 'VmFooter',
}
</script>

<style lang="scss" scoped>
 .footer {
   height: 200px;
     width: 100vw;
      display:flex;
    justify-content: stretch;
    align-items: stretch;
    flex-grow: 1;
    flex-shrink: 0;
    flex-direction: row;
        z-index: 3;
   margin-top: 5%;
   background: #00093b;
   color: rgb(255, 255, 255);
 }
</style>
