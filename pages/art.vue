<template>
  <div>
    <x-section class="section--wave-bottom" as="hero" size="lg" top>
      <x-content class="text-align--center">
        <x-group as="center" size="sm">
          <x-icon as="secondary" icon="stamp" class="margin--center margin-bottom--30"/>
          <h1 class="margin-bottom--20">Art & Printmaking</h1>
          <p>I love making things with my hands.</p>
          <p>I frequently experiment with different mediums, with my current focus being on pottery, printmaking (linocut & screenprinting) and digital illustrations.</p>
          <x-link as="standard" class="margin-top--20" href="https://www.etsy.com/ca/shop/LPDesignsCanada" target="_blank">Visit Shop</x-link>
        </x-group>
      </x-content>
    </x-section>
    <x-section>
      <x-content>
        <div class="text-align--center">
          <h2 class="h4">Pottery</h2>
          <h3 class="heading--accent">Thrown, trimmed, & glazed by hand</h3>
          <x-grid as="gallery" name="pottery" cols="4">
            <x-grid-item>
              <img src="~@/assets/images/art/pottery1.png" alt="">
            </x-grid-item>
            <x-grid-item>
              <img src="~@/assets/images/art/pottery2.png" alt="">
            </x-grid-item>
            <x-grid-item>
              <img src="~@/assets/images/art/pottery3.png" alt="">
            </x-grid-item>
            <x-grid-item>
              <img src="~@/assets/images/art/pottery4.png" alt="">
            </x-grid-item>
          </x-grid>
        </div>
        <div class="text-align--center margin-top--50">
          <h2 class="h4">Illustrated portraits</h2>
          <h3 class="heading--accent">Digital - iPad</h3>
          <x-grid as="gallery" name="illustration" cols="4">
            <x-grid-item>
              <img src="~@/assets/images/art/illustration2.png" alt="">
            </x-grid-item>
            <x-grid-item>
              <img src="~@/assets/images/art/illustration3.png" alt="">
            </x-grid-item>
            <x-grid-item>
              <img src="~@/assets/images/art/illustration1.png" alt="">
            </x-grid-item>
            <x-grid-item>
              <img src="~@/assets/images/art/illustration4.png" alt="">
            </x-grid-item>
          </x-grid>
        </div>
        <div class="text-align--center margin-top--50">
          <h2 class="h4">Printmaking</h2>
          <h3 class="heading--accent">Linocut, screenprinting, sewing</h3>
          <x-grid as="gallery" cols="4" name="prints">
            <x-grid-item>
              <img src="~@/assets/images/art/print1.png" alt="">
            </x-grid-item>
            <x-grid-item>
              <img src="~@/assets/images/art/print2.png" alt="">
            </x-grid-item>
            <x-grid-item>
              <img src="~@/assets/images/art/print3.png" alt="">
            </x-grid-item>
            <x-grid-item>
              <img src="~@/assets/images/art/print4.png" alt="">
            </x-grid-item>
            <x-grid-item>
              <img src="~@/assets/images/art/create1.png" alt="">
            </x-grid-item>
            <x-grid-item>
              <img src="~@/assets/images/art/create2.png" alt="">
            </x-grid-item>
            <x-grid-item>
              <img src="~@/assets/images/art/create3.png" alt="">
            </x-grid-item>
            <x-grid-item>
              <img src="~@/assets/images/art/create4.png" alt="">
            </x-grid-item>
          </x-grid>
        </div>
        <div class="text-align--center margin-top--50">
          <h2 class="h4">Animal portraits</h2>
          <h3 class="heading--accent">Watercolour</h3>
          <x-grid as="gallery" name="portraits" cols="4">
            <x-grid-item>
              <img src="~@/assets/images/art/portrait1.png" alt="">
            </x-grid-item>
            <x-grid-item>
              <img src="~@/assets/images/art/portrait2.png" alt="">
            </x-grid-item>
            <x-grid-item>
              <img src="~@/assets/images/art/portrait3.png" alt="">
            </x-grid-item>
            <x-grid-item>
              <img src="~@/assets/images/art/portrait4.png" alt="">
            </x-grid-item>
          </x-grid>
        </div>
      </x-content>
    </x-section>
  </div>
</template>

<script>
export default {}
</script>
