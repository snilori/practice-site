<template>
    <header class="header">
        <div class="header__container">
            <div class="brand__logo">
                <img src="/images/logo.png" alt="brand__logo" class="brand__logo__icon" />
            </div>

            <nav class="header__nav">
                <div class="header__nav__list">
                    <div class="header__nav__item">
                        <a href="#" target="_blank" class="header__nav__link">HOME</a>
                    </div>

                    <div class="header__nav__item">
                        <a href="#" target="_blank" class="header__nav__link">CAREERS</a>
                    </div>

                    <div class="header__nav__item">
                        <a href="#" target="_blank" class="header__nav__link">AFFINITY WINGS</a>
                    </div>

                    <div class="header__nav__item">
                        <a href="#" target="_blank" class="header__nav__link">TALK TO US</a>
                    </div>
                </div>
            </nav>

            <div class="header__buttons">
                <div class="header__buttons__list">
                    <div class="header__buttons__item">
                        <button onclick='location.href="#"' class="header__buttons__link">FLIGHTS</button>
                    </div>

                    <div class="header__buttons__item">
                        <button onclick='location.href="#"' class="header__buttons__link">MANAGE BOOKINGS</button>
                    </div>

                    <div class="header__buttons__item">
                        <button onclick='location.href="#"' class="header__buttons__link">AFFINITY WINGS</button>
                    </div>
                </div>
            </div>
        </div>
    </header>
</template>


<script>
export default {
    name: "Header",
};
</script>


