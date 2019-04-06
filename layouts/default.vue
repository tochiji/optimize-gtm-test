<template>
  <div id="container">
    <header id="header">
      <div>ホーム</div>
      <div>お気に入り</div>
      <div>購入履歴</div>
      <div>カート</div>
    </header>
    <nuxt />
  </div>
</template>

<style scoped lang="scss">
#container {
  position: relative;
  width: 375px;
  border: 1px solid rgb(216, 216, 216);
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
}

#header {
  position: relative;
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: row;

  div {
    width: 25%;
    height: 60px;
    border: 1px solid rgb(216, 216, 216);
    font-size: 0.8rem;

    flex-grow: 1;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
  }
}
</style>
