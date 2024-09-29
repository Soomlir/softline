<template>
  <header class="header">
    <a href="#!">
      <img
        class="header__logo"
        src="../../public/images/logo-mobile.svg"
        width="125"
        height="25"
        alt="Лого Softline."
      />
    </a>
    <nav class="header__nav">
      <ul class="header__list">
        <li class="header__item">
          <a href="#!" class="header__link">Облачные решения</a>
        </li>
        <li class="header__item">
          <a href="#!" class="header__link">Кибербезопасность</a>
        </li>
        <li class="header__item">
          <a href="#!" class="header__link">Импортозамещение</a>
        </li>
        <li class="header__item">
          <a href="#!" class="header__link">Цифровая трансформация</a>
        </li>
      </ul>
    </nav>
  </header>
</template>

<style lang="scss">
.header {
  min-width: 290px;
  margin-left: 15px;
  margin-right: 15px;
  padding-top: 16px;
  box-shadow: 0 4px 4px 0 rgba(#000000, 0.25);
}

.header__logo {
  margin-left: 5px;
  margin-bottom: 8px;
}

.header__nav {
  margin-left: 5px;
}

.header__list {
  display: grid;
  grid-template-columns: 121px 1fr;
  grid-template-rows: 21px 21px;
  flex-wrap: wrap;
  margin: 0;
  padding: 0;
  list-style: none;
}

.header__link {
  color: #444444;
  font-size: 14px;
  text-decoration: none;
  font-weight: 600;

  &::nth-child(4) {
    margin-left: 3px;
  }
}
</style>
