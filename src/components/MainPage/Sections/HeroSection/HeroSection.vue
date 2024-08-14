<script setup lang='ts'>
import './hero-section.css'
import ButtonComponent from '../../../../components/controls/ButtonControl.vue'
</script>

<template>
    <section class="hero container">
        <div class="hero--wrapper ">
            <h1 class="hero--title">Быстрый старт: <span class="hero--span">
              Запуск доставки за 5 дней!
                </span>
            </h1>
            <ButtonComponent class="hero--button" text="Начать"/>
        </div>
            <img src="../../../../assets/images/hero-images/phone.png" alt="" class="hero--phone">
            <img src="../../../../assets/images/hero-images/elipse.png" alt="" class="hero--bg">
    </section>
</template>
