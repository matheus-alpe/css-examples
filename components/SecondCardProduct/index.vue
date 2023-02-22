<template>
  <article class="card">
    <figure class="card__image">
      <img
        src="https://images.unsplash.com/photo-1494253109108-2e30c049369b?crop=entropy&cs=srgb&fm=jpg&ixid=MnwxNDU4OXwwfDF8cmFuZG9tfHx8fHx8fHx8MTYyNDcwMTUwOQ&ixlib=rb-1.2.1&q=85"
        alt="An orange painted blue, cut in half laying on a blue background"
      />
    </figure>

    <div class="card__header">
      <a>When life gives you oranges</a>

      <button class="icon-button">
        <IconsIconHeart />
      </button>
    </div>

    <div class="card__footer">
      <div class="card__footer-meta">
        <IconsIconEyeOpen />
        2,465
      </div>

      <div class="card__footer-meta">
        <IconsIconCalendar />
        Jul 26, 2019
      </div>
    </div>
  </article>
</template>

<style lang="scss" scoped>
@import './SecondaCardProduct.scss';
</style>
