<template>
    <main class="page">
        <section class="hero">
            <div class="hero__container">
                <div class="hero__information">
                    <p class="hero__information__heading">
                        Travel Anywhere Within<br />
                        Africa
                    </p>

                    <div class="hero__information__sub__container">
                        <p class="hero__information__sub__location">Lagos</p>
                        <p class="hero__information__sub__destination">From Accra to Lagos</p>
                        <p class="circle__container">
                            <span class="circle__item__one"> </span>

                            <span class="circle__item"> </span>

                            <span class="circle__item"> </span>

                            <span class="circle__item"> </span>
                        </p>
                    </div>
                </div>

                <div class="hero__book__container">
                    <p class="hero__book__header">Book a Flight</p>

                    <div class="hero__book__direction__container">
                        <button class="hero__book__direction__text__blue" v-on:click="isActive = !isActive" :class="{ isActive: isActive }">ONE WAY</button>

                        <button class="hero__book__direction__text">ROUND TRIP</button>
                    </div>

                    <div class="hero__book__direction__location__container">
                        <p class="hero__book__direction__location">Departure Airport</p>

                        <p class="hero__book__direction__location__arrival">Arrival Airport</p>
                    </div>

                    <div class="hero__book__location__container">
                        <p class="hero__book__location">LAG</p>

                        <p class="hero__book__location__arrival">PH</p>
                    </div>

                    <div class="hero__book__arrow">
                        <img src="/images/right-arrow.png" alt="right-arrow" class="right-arrow" />
                    </div>

                    <div class="hero__book__location__smaller__case__container">
                        <p class="hero__book__location__smaller__case">LAG</p>

                        <p class="hero__book__location__arrival__smaller__case">Port-Harcourt</p>
                    </div>

                    <div class="hero__book__second__border"></div>

                    <div class="hero__book__location__date__container">
                        <p class="hero__book__location__date__text">Departure Date</p>
                        <p class="hero__book__location__date__figure">14</p>
                        <p class="hero__book__location__date__text__figure">December 2019</p>
                    </div>

                    <div class="hero__select__class__container">
                        <div class="hero__select__class">
                            <select name="status" id="status">
                                <option value="econony">Economy</option>
                                <option value="business-class">Business Class</option>
                                <option value="first-class">First Class</option>
                            </select>
                        </div>
                    </div>

                    <div class="hero__select__person__container">
                        <div class="hero__select__person">
                            <span>
                                <select name="person" id="person">
                                    <option value="four-adults">4 Adults</option>
                                    <option value="three-adults">3 Adults</option>
                                    <option value="two-adults">2 Adults</option>
                                    <option value="one-adult">1 Adult</option>
                                </select>
                            </span>
                            <span>
                                <select name="child" id="child">
                                    <option value="two-children">2 Children</option>
                                    <option value="three-children">3 Children</option>
                                    <option value="four-children">4 Children</option>
                                    <option value="one-child">1 Child</option>
                                </select>
                            </span>
                        </div>
                    </div>

                    <div class="hero__search__container">
                        <button class="hero__search__find" onclick='location.href="#"'>FLIGHT SEARCH</button>
                    </div>
                </div>
            </div>
        </section>

        <section class="section__stages">
            <div class="section__stages__container">
                <div class="section__intro__first__container">
                    <p class="section__intro__figure">1</p>
                    <div class="section__intro__first__grouping">
                        <div class="section__intro__first__picture__container">
                            <img src="/images/search.png" alt="search" class="search" />
                        </div>
                        <p class="section__intro__first__header">Search</p>
                        <p class="section__intro__first__text">Search for flights to a destination of your choice within Nigeria, Ghana, Liberia and Senegal.</p>
                    </div>
                </div>

                <div class="section__intro__first__container">
                    <p class="section__intro__figure">2</p>
                    <div class="section__intro__first__grouping">
                        <div class="section__intro__first__picture__container">
                            <img src="/images/precision.png" alt="precision" class="search" />
                        </div>
                        <p class="section__intro__first__header">SELECT</p>
                        <p class="section__intro__first__text">Flights are scheduled for your comfort and convenience..</p>
                    </div>
                </div>

                <div class="section__intro__first__container">
                    <p class="section__intro__figure">3</p>
                    <div class="section__intro__first__grouping">
                        <div class="section__intro__first__picture__container">
                            <img src="/images/airplane-ticket.png" alt="airplane-ticket" class="search" />
                        </div>
                        <p class="section__intro__first__header">BOOK</p>
                        <p class="section__intro__first__text">Book your flights and pay online with an option to book on-hold and pay later.</p>
                    </div>
                </div>
            </div>
        </section>

        <section class="section__promotion">
            <div class="section__promotion__container">
                <div class="section__promotion__arrows">
                    <span class="left-arrow">
                        <img src="/images/blue-left-arrow.png" alt="blue-left-arrow" class="blue__left__arrow" />
                    </span>
                    <span class="right-arrow">
                        <img src="/images/blue-right-arrow.png" alt="blue-right-arrow" class="blue__right__arrow" />
                    </span>
                </div>

                <div class="section__promotion__info__container">
                    <div class="section__promotion__info__box__one">
                        <img src="/images/radisson-blue-logo.png" alt="promotion-logo" class="promotion__logo" />
                        <p class="section__promotion__info__heading">WEEKEND PROMOTION</p>
                        <p class="section__promotion__info__text">This is for you if your Arik Air Boarding Pass is less than one month</p>
                        <p class="section__promotion__info__date">Offer valid from 9th till 31st August & all weekends till 31st December</p>
                    </div>

                    <div class="section__promotion__info__box__two__container">
                        <div class="section__promotion__info__box__two">
                            <div class="section__promotion__info__box__two__white__background">
                                <p class="section__promotion__info__box__two__header">10% off WEEKEND RATE</p>
                                <div class="section__promotion__info__box__two__list__container">
                                    <ul class="section__promotion__info__box__two__list">
                                        <li class="section__promotion__info__box__two__list__item">Free Room Upgrade</li>

                                        <li class="section__promotion__info__box__two__list__item">15% off buffet meals</li>

                                        <li class="section__promotion__info__box__two__list__item">10% off spa treatment</li>

                                        <li class="section__promotion__info__box__two__list__item">10% off beauty studio treatment</li>
                                    </ul>

                                    <div class="section__promotion__info__box__two__book__text__container">
                                        <a href="#" class="section__promotion__info__box__two__book__text"> Book Now </a>
                                        <span class="section__promotion__info__box__two__book__arrow">
                                            <img src="/images/blue-straight-arrow.png" class="section__promotion__info__box__two__book__arrow__icon" alt="blue-arrow" />
                                        </span>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section class="section__store__advert">
            <div class="section__store__advert__container">
                <div class="section__store__brand__advert">
                    <img src="/images/brand-post.png" alt="brand-post" class="brand__post" />
                </div>

                <div class="section__store__brand__container">
                    <p class="section__store__brand__header">Arik Air Mobile App</p>
                    <p class="section__store__brand__text">For better experience, you can now download our mobile app available on Android and IOS.</p>
                    <p class="section__store__icons__container">
                        <a href="#" class="section__store__icons">
                            <img src="/images/app-store.png" alt="app-store" class="app__store" />
                        </a>
                        <a href="#">
                            <img src="/images/play-store.png" alt="play-store" class="play__store" />
                        </a>
                    </p>
                </div>
            </div>
        </section>

        <section class="section__destination">
            <p class="section__destination__header">Top Destinations</p>
            <div class="grid-container">
                <div class="section__destination__first__element__container item1">
                    <p class="grid-item">Lagos, Nigeria</p>
                </div>
                <div class="section__destination__second__element__container">
                    <p class="grid-item">Accra, Ghana</p>
                </div>
                <div class="section__destination__third__element__container">
                    <p class="grid-item">Kaduna, Nigeria</p>
                </div>
                <div class="section__destination__fourth__element__container">
                    <p class="grid-item">Sokoto, Nigeria</p>
                </div>
                <div class="section__destination__fifth__element__container">
                    <p class="grid-item">Dakar, Senegal</p>
                </div>
            </div>

            <div class="section__destination__second__row__container">
                <div class="section__destination__second__row__first__picture">
                    <p class="section__destination__second__row__city">Monrovia, Liberia</p>
                </div>

                <div class="section__destination__second__row__second__picture">
                    <p class="section__destination__second__row__city">Bauchi, Nigeria</p>
                </div>

                <div class="section__destination__second__row__third__picture">
                    <p class="section__destination__second__row__city">Ibadan, Nigeria</p>
                </div>
            </div>
        </section>
    </main>
</template>

<script>
export default {
    data() {
        return {
            isActive: false,
            isActiveRound: false,
        };
    },
};
</script>

