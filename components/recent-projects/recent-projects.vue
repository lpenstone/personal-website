<template>
  <div class="row">
    <div class="col-sm-12 col-md-6">
      <x-group size="sm" class="margin--center">
        <x-card as="shadow" class="margin-bottom--20">
          <h3>Stylx</h3>
          <div class="margin-top--30 margin-bottom--20">
            <p>A pre-styled component library & design system to help developers create websites (like this one) fast.</p>
            <p>Customizations are made in the stylx.config file to suit your brand. The components do the rest.</p>
            <p>Comes with <strong>dark mode, responsive styles, keyboard commands, and accessibility features</strong> out-of-the-box.</p>
            <div class="margin-top--20">
              <x-tag as="#888888" class="margin-top--10">Nuxt.js</x-tag>
              <x-tag as="#888888" class="margin-top--10">Design systems</x-tag>
              <x-tag as="#888888" class="margin-top--10">BEM</x-tag>
              <x-tag as="#888888" class="margin-top--10">Documentation</x-tag>
            </div>
          </div>
          <x-link href="https://www.stylx.dev" as="link-alt" icon="external-link-alt" target="_blank">Visit Stylx website</x-link>
        </x-card>
      </x-group>
    </div>
    <div class="col-sm-12 col-md-6">
      <x-group size="sm" class="margin--center">
        <x-card as="shadow" class="margin-bottom--20">
          <h3>ditto</h3>
          <div class="margin-top--30 margin-bottom--20">
            <p>Video conferencing UI wrapper that allows guests to break off into smaller video call rooms, while maintaning context of the whole virtual event.</p>
            <p>Users are able to customize their events with different rooms and features.</p>
            <p>ditto is currently not an open source project.</p>
            <p class="font-size--sm"><strong>Part of a 4 person team. Responsible for: UI/UX design, illustration, branding, and frontend development</strong></p>
            <div class="margin-top--20">
              <x-tag as="#888888" class="margin-top--10">UI Design</x-tag>
              <x-tag as="#888888" class="margin-top--10">Vue.js</x-tag>
              <x-tag as="#888888" class="margin-top--10">Websockets</x-tag>
              <x-tag as="#888888" class="margin-top--10">JAM Stack</x-tag>
            </div>
          </div>
          <x-modal size="lg" buttonAs="link-alt" name="ditto-modal" label="View app screenshots">
            <x-carousel as="modal" name="ditto-carousel">
              <x-carousel-item>
                <img srcset="~@/assets/images/projects/ditto1@2x.png 2x, ~@/assets/images/projects/ditto1.png 1x" src="~@/assets/images/projects/ditto1.png" class="ditto-1" alt="Screenshot of a demo for the ditto video conferencing web app">
                <p class="margin-top--20">View of a ditto event dashboard. Open and close ditto UI elements to suit your preference.</p>
              </x-carousel-item>
              <x-carousel-item>
                <img srcset="~@/assets/images/projects/ditto2@2x.png 2x, ~@/assets/images/projects/ditto2.png 1x" src="~@/assets/images/projects/ditto2.png" class="ditto-2" alt="">
                <p class="margin-top--20">See who's in a video room before joining. You can also spy on those waiting in the "lobby". 👀</p>
              </x-carousel-item>
              <x-carousel-item>
                <img srcset="~@/assets/images/projects/ditto3@2x.png 2x, ~@/assets/images/projects/ditto3.png 1x" src="~@/assets/images/projects/ditto3.png" class="ditto-3" alt="">
                <p class="margin-top--20">Get a description of the event and the purpose of each room.</p>
              </x-carousel-item>
              <x-carousel-item>
                <img srcset="~@/assets/images/projects/ditto4@2x.png 2x, ~@/assets/images/projects/ditto4.png 1x" src="~@/assets/images/projects/ditto4.png" class="ditto-4" alt="">
                <p class="margin-top--20">When creating an event, add details and features to the rooms to make it more custom. Or use the default settings for a quick set-up.</p>
              </x-carousel-item>
              <x-carousel-item>
                <img srcset="~@/assets/images/projects/ditto5@2x.png 2x, ~@/assets/images/projects/ditto5.png 1x" src="~@/assets/images/projects/ditto5.png" class="ditto-5" alt="">
                <p class="margin-top--20">Upon creating the event, copy the share details to send to your guests.</p>
              </x-carousel-item>
            </x-carousel>
          </x-modal>
          <div class="margin-top--10">
            <x-link href="https://www.dittoevent.com" as="link-alt" icon="external-link-alt" target="_blank">Visit ditto website</x-link>
          </div>
        </x-card>
      </x-group>
    </div>
  </div>
</template>

<script>
export default {
  name: 'recent-projects',
  data () {
    return {}
  }
}
</script>

<style lang="stylus" scoped>

.item
  img.ditto-1
    max-width: 850px
    width: 100%

  img.ditto-2, img.ditto-3, img.ditto-5
    max-width: 650px
    width: 100%

  img.ditto-4
    max-width: 730px
    width: 100%

</style>
