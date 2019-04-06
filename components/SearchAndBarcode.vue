<template>
  <div class="search-barcode">
    <div class="search">グッズを探す</div>
    <div class="barcode">バーコード</div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped lang="scss">
.search-barcode {
  position: relative;
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: row;

  div {
    height: 60px;
    display: flex;
    justify-content: center;
    align-items: center;
    border: 1px solid rgb(212, 212, 212);
  }

  .search {
    width: 70%;
  }

  .barcode {
    width: 30%;
  }
}
</style>
