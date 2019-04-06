<template>
  <section class="container">
    <SearchAndBarcode />
    <div class="logo-and-text">
      <img class="logo" src="https://placehold.jp/200x50.png?text=ロゴ" />
      <div class="alert">XXX-ご利用の前にご確認ください</div>
      <div class="order-time">ご注文は来園日の23:30までです</div>
    </div>
    <SpecialBanners />
    <Pickup />
  </section>
</template>

<script>
import SearchAndBarcode from '~/components/SearchAndBarcode.vue'
import SpecialBanners from '~/components/SpecialBanners.vue'
import Pickup from '~/components/Pickup.vue'
export default {
  components: {
    SearchAndBarcode,
    SpecialBanners,
    Pickup
  }
}
</script>

<style scoped lang="scss">
.container {
  position: relative;
  width: 100%;
  display: flex;
  justify-content: top;
  align-items: center;
  flex-direction: column;
  padding-bottom: 300px;
}

.logo-and-text {
  display: flex;
  justify-content: top;
  align-items: center;
  flex-direction: column;

  .logo {
    margin: 20px 0 10px;
  }

  .alert {
    margin: 10px 0 10px;
    font-weight: bold;
    color: rgb(206, 105, 105);
  }

  .order-time {
    margin: 10px 0 20px;
    font-weight: bold;
  }
}
</style>
