<template>
  <div class="pickup-container">
    <div class="title">ピックアップ</div>
    <div class="items-container">
      <div class="item">
        <img
          class="logo"
          src="https://placehold.jp/180x100.png?text=pickupグッズ①"
        />
        <div class="description">
          <div>ハンドソープ</div>
          <div>1,200円</div>
        </div>
      </div>
      <div class="item">
        <img
          class="logo"
          src="https://placehold.jp/180x100.png?text=pickupグッズ②"
        />
        <div class="description">
          <div>小分け袋</div>
          <div>300円</div>
        </div>
      </div>
      <div class="item">
        <img
          class="logo"
          src="https://placehold.jp/180x100.png?text=pickupグッズ③"
        />
        <div class="description">
          <div>ゴミ箱</div>
          <div>4,000円</div>
        </div>
      </div>
      <div class="item">
        <img
          class="logo"
          src="https://placehold.jp/180x100.png?text=pickupグッズ④"
        />
        <div class="description">
          <div>ケース</div>
          <div>3,400円</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped lang="scss">
.pickup-container {
  margin-top: 40px;
  position: relative;
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

.title {
  position: relative;
  width: 95%;
  text-align: left;
  font-weight: bold;
  font-size: 1.2rem;
}

.items-container {
  width: 100%;
  display: flex;
  justify-content: flex-start;
  align-items: center;
  flex-direction: row;
  flex-wrap: wrap;
}

.item {
  width: 50%;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  margin-bottom: 10px;

  img {
    width: 100%;
    border: 3px solid #fff;
  }
}

.description {
  position: relative;
  font-size: 0.8rem;
  width: 100%;
  margin: 8px 0 0 8%;
  font-weight: bold;
  text-align: left;
}
</style>
