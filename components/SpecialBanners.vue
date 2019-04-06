<template>
  <div class="special-banners-container">
    <nuxt-link to="WSTLF00101.html?type=bannner&num=1" tag="div" class="banner">
      <img
        class="logo"
        src="https://placehold.jp/370x200.png?text=特集バナー①"
      />
      <div class="description">
        <div>お菓子特集</div>
        <div>お土産の定番といえばやっぱりこれ！</div>
      </div>
    </nuxt-link>
    <div class="banner">
      <img
        class="logo"
        src="https://placehold.jp/370x200.png?text=特集バナー②"
      />
      <div class="description">
        <div>ハロウイーン特集</div>
        <div>うさたま・うさぴよグッズせいぞろい！</div>
      </div>
    </div>
    <!-- <div class="banner">
      <img
        class="logo"
        src="https://placehold.jp/370x200.png?text=特集バナー③"
      />
      <div class="description">
        <div>ダッフィー特集</div>
        <div>ステラ・ルーやジェラトーニ</div>
      </div>
    </div> -->
    <div class="mini-banner">
      <img
        class="logo"
        src="https://placehold.jp/180x100.png?text=ミニバナー①"
      />
      <div class="description">
        <div>SALE</div>
        <div>お得な価格で！</div>
      </div>
    </div>
    <div class="mini-banner">
      <img
        class="logo"
        src="https://placehold.jp/180x100.png?text=ミニバナー②"
      />
      <div class="description">
        <div>ベイマックス特集は</div>
        <div>こちらから</div>
      </div>
    </div>
    <div class="mini-banner">
      <img
        class="logo"
        src="https://placehold.jp/180x100.png?text=ミニバナー③"
      />
      <div class="description">
        <div>【お部屋に一つ】</div>
        <div>ゴミ箱やお掃除グッズ</div>
      </div>
    </div>
    <div class="mini-banner">
      <img
        class="logo"
        src="https://placehold.jp/180x100.png?text=ミニバナー④"
      />
      <div class="description">
        <div>普段使いにもおしゃれ</div>
        <div>バッグやポーチを特集</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped lang="scss">
.special-banners-container {
  position: relative;
  width: 100%;
  display: flex;
  justify-content: flex-start;
  align-items: flex-start;
  flex-direction: row;
  flex-wrap: wrap;
}

.banner {
  cursor: pointer;
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  margin-bottom: 20px;

  img {
    width: 100%;
  }
}

.mini-banner {
  cursor: pointer;
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
