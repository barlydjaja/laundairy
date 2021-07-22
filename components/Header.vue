<template>
  <header>
    <div>
      <h1 class="header__logo">
        Laundiary
      </h1>
      <p class="header__sub-title">Your Laundry Diary</p>
    </div>
    <div>

    </div>
  </header>
</template>

<script>
import logo from "@/assets/images/home/logo.png"

export default {
  name: "Header",
  data() {
    return {
      logo,
    }
  }
};
</script>

<style lang="scss" scoped>
@import 'assets/scss/variables';

header {
  background: $primaryColor;
  color: $textColor;

  .header__logo {
    font-size: 3em;
    letter-spacing: 2px;
    height: 3rem;
    font-family: $fontLogo;
  }

  .header__sub-title{
    font-family: $fontText;
    letter-spacing: 1px;
    font-size: 1.25em;
  }
}
</style>
