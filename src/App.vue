<template>
  <div class="container">
    <header class="header">
      <img src="img/logo.png" alt="trillo logo" class="logo">
      <form class="search" action="#">
        <input type="text" class="search__input" placeholder="Search hotels">
        <button class="search__button">
          <svg class="search__icon">
            <use xlink:href="img/sprite.svg#icon-magnifying-glass"></use>
          </svg>
        </button>
      </form>
      <nav class="user-nav">
        <div class="user-nav__icon-box">
          <svg class="user-nav__icon">
            <use xlink:href="img/sprite.svg#icon-bookmark"></use>
          </svg>
          <span class="user-nav__notification">7</span>
        </div>
        <div class="user-nav__icon-box">
          <svg class="user-nav__icon">
            <use xlink:href="img/sprite.svg#icon-chat"></use>
          </svg>
          <span class="user-nav__notification">13</span>
        </div>
        <div class="user-nav__user">
          <img src="img/user.jpg" alt="" class="user-nav__user-photo">
          <span class="user-nav__user-name">Jonas</span>
        </div>
      </nav>
    </header>
    <div class="content">
      <nav class="sidebar">
        <ul class="side-nav">

          <li class="side-nav__item side-nav__item--active">
            <a href="#" class="side-nav__link">
              <svg class="side-nav__icon">
                <use xlink:href="img/sprite.svg#icon-home"></use>
              </svg>
              <span>Hotel</span>
            </a>
          </li>

          <li class="side-nav__item">
            <a href="#" class="side-nav__link">
              <svg class="side-nav__icon">
                <use xlink:href="img/sprite.svg#icon-aircraft-take-off"></use>
              </svg>
              <span>Flight</span>
            </a>
          </li>

          <li class="side-nav__item">
            <a href="#" class="side-nav__link">
              <svg class="side-nav__icon">
                <use xlink:href="img/sprite.svg#icon-key"></use>
              </svg>
              <span>Car rental</span>
            </a>
          </li>

          <li class="side-nav__item">
            <a href="#" class="side-nav__link">
              <svg class="side-nav__icon">
                <use xlink:href="img/sprite.svg#icon-map"></use>
              </svg>
              <span>Tours</span>
            </a>
          </li>
        </ul>
        <div class="legal">
          &copy; 2017 by trillo. All rights reserved.
        </div>
      </nav>
      <main class="hotel-view">
        <div class="gallery">
          <figure class="gallery__item">
            <img class="gallery__photo" src="img/hotel-1.jpg" alt="Photo of hotel 1">
          </figure>

            <figure class="gallery__item">
              <img class="gallery__photo" src="img/hotel-2.jpg" alt="Photo of hotel 2">
          </figure>

              <figure class="gallery__item">
                <img class="gallery__photo" src="img/hotel-3.jpg" alt="Photo of hotel 3">
          </figure>
        </div>
        <div class="overview">
          <h1 class="overview__heading">
            Hotel Las Palmas
          </h1>
          <div class="overview__stars">
            <svg class="overview__icon-star">
              <use xlink:href="img/sprite.svg#icon-star"></use>
            </svg>
            <svg class="overview__icon-star">
              <use xlink:href="img/sprite.svg#icon-star"></use>
            </svg>
            <svg class="overview__icon-star">
              <use xlink:href="img/sprite.svg#icon-star"></use>
            </svg>
            <svg class="overview__icon-star">
              <use xlink:href="img/sprite.svg#icon-star"></use>
            </svg>
            <svg class="overview__icon-star">
              <use xlink:href="img/sprite.svg#icon-star"></use>
            </svg>
          </div>
          <div class="overview__location">
            <svg class="overview__icon-location">
              <use xlink:href="img/sprite.svg#icon-location-pin"></use>
            </svg>
            <button class="btn-inline">Albufeira, Portugal</button>
          </div>
          <div class="overview__rating">
            <div class="overview__rating-average">8.6</div>
            <div class="overview__rating-count">429 votes</div>

          </div>
        </div>
        <div class="detail">
          <div class="description">
            <p class="paragraph">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Eaque, dolore a nemo fugit voluptatem doloremque veniam, itaque temporibus libero reiciendis tempore unde iure dignissimos alias. Ea neque natus explicabo veritatis.
            </p>
            <p class="paragraph">
              Lorem ipsum dolor sit, amet consectetur adipisicing elit. Repudiandae quae ipsum nulla impedit earum temporibus accusamus veniam perspiciatis ipsam consequuntur.
            </p>
            <ul class="list">
              <li class="list__item">Close to the beach</li>
              <li class="list__item">Breakfast included</li>
              <li class="list__item">Free airport shuttle</li>
              <li class="list__item">Free wifi in all rooms</li>
              <li class="list__item">Air conditioning and heating</li>
              <li class="list__item">Pets allowed</li>
              <li class="list__item">We spead all alanguages</li>
              <li class="list__item">Perfect for families</li>
            </ul>
            <div class="recommend">
              <p class="recommend__count">
                Lucy and 3 other friends recommend this hotel.
              </p>
              <div class="recommend__friends">
                <img src="img/user-3.jpg" alt="Friend 3" class="recommend__photo">
                <img src="img/user-4.jpg" alt="Friend 4" class="recommend__photo">
                <img src="img/user-5.jpg" alt="Friend 5" class="recommend__photo">
                <img src="img/user-6.jpg" alt="Friend 6" class="recommend__photo">
              </div>
              </div>
            </div>
            <div class="user-review">
              <figure class="review">
                <blockquote class="review__text">
                  Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima ut porro quis!
                </blockquote>
                <figcaption class="review__user">
                  <img src="img/user-1.jpg" alt="" class="review__photo">
                  <div class="review__user-box">
                    <p class="review__user-name">Nick Smith</p>
                    <p class="review__user-date">Feb 23rd, 2017</p>
                  </div>
                  <div class="review__rating">7.8</div>
                </figcaption>
              </figure>

              <figure class="review review--2">
                <blockquote class="review__text">
                  Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima ut porro quis!
                </blockquote>
                <figcaption class="review__user">
                  <img src="img/user-2.jpg" alt="" class="review__photo">
                  <div class="review__user-box">
                    <p class="review__user-name">Mary Thomas</p>
                    <p class="review__user-date">Sep 13th, 2017</p>
                  </div>
                  <div class="review__rating">9.2</div>
                </figcaption>
              </figure>
              <button class="btn-inline">Show all <span>&rarr;</span> </button>
            </div>
          </div>
      </main>
    </div>
  </div>
</template>

<script>
export default {
  name: 'app'
};
</script>

<style>
</style>
