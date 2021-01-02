<template>
  <div>
    <x-section as="hero" id="hero">
      <x-content>
        <div class="hero__content">
          <x-group class="margin-top--40">
            <div class="hero__copy">
              <h1>Welcome 👋</h1>
              <p>I'm Laura.</p>
              <p>A frontend developer with a wide range of artistic hobbies and interests.</p>
              <p>Currently working in Toronto, Canada 🇨🇦 with my <x-link href="https://en.wikipedia.org/wiki/Potcake_dog" target="_blank">potcake</x-link> dog Kipper.</p>
              <x-see-more label="..." as="plain" class="margin-top--20">
                <strong>More?!</strong>
                <ul class="margin-top--10">
                  <li>I am passionate about teaching others and making the world of web developement accessible to people of all backgrounds.</li>
                  <li>I value and foster a diverse and inclusive workplace.</li>
                  <li>Big believer in being a <x-link href="https://signalvnoise.com/posts/1430-hire-managers-of-one" target="_blank">Manager of One</x-link>.</li>
                </ul>
                <x-combo as="circle" size="sm" class="margin-top--20 margin-bottom--10">
                  <x-combo-img landscape>
                    <img src="~@/assets/images/index/kipper.png" alt="Russet coloured potcake dog">
                  </x-combo-img>
                  <x-combo-text>
                    <p>Here's a bonus photo of Kipper!</p>
                    <p>He was adopted in 2017 as a street dog from Saint Vincent and the Grenadines.</p>
                  </x-combo-text>
                </x-combo>
              </x-see-more>
            </div>
          </x-group>
          <div class="hero__doodle">
            <img class="hero__doodle--light" src="~@/assets/images/index/hero.png" alt="">
            <img class="hero__doodle--dark" src="~@/assets/images/index/hero-dm.png" alt="">
          </div>
        </div>
      </x-content>
    </x-section>
    <x-section id="hats" size="lg">
      <x-content class="text-align-center">
        <x-group as="center">
          <div id="venn">
            <div class="venn__wrap">
              <div class="venn__label venn__label--left">design</div>
              <div class="venn__label venn__label--right">development</div>
              <div class="venn__circle venn__circle--left"></div>
              <div class="venn__circle venn__circle--right"></div>
              <div class="venn__label venn__label--magic">
                <img srcset="~@/assets/images/index/unicorn@2x.png 2x, ~@/assets/images/index/unicorn.png 1x" src="~@/assets/images/index/unicorn.png" alt="" class="venn__img venn__img--lm">
                <img srcset="~@/assets/images/index/unicorn-dm@2x.png 2x, ~@/assets/images/index/unicorn-dm.png 1x" src="~@/assets/images/index/unicorn-dm.png" alt="" class="venn__img venn__img--dm">
              </div>
            </div>
          </div>
          <x-carousel height="248" name="about-me">
            <x-carousel-item>
              <h2 class="margin-bottom--20">Frontend Developer</h2>
              <p>3+ years of industry experience.</p>
              <p>Writing scalable, tested, component-based code.</p>
              <p>Developing UI's with a focus on accessibility and delight.</p>
              <div class="margin-top--20">
                <x-tag class="margin-top--10">
                  Javascript &amp; tools
                  <x-tag-label>
                    <p>Experience with Javascript, jQuery, Vue.js, Nuxt.js, Pug, Liquid.</p>
                    <p>Writing Javascript on a daily basis in a Vue.js project.</p>
                  </x-tag-label>
                </x-tag>
                <x-tag class="margin-top--10">
                  Developing UIs
                  <x-tag-label>
                    <p>HTML5, CSS3, CSS preprocessors (<x-link href="https://stylus-lang.com/" target="_blank">Stylus</x-link>, Sass), building component-based projects.</p>
                  </x-tag-label>
                </x-tag>
                <x-tag class="margin-top--10">
                  e2e testing
                  <x-tag-label>
                    <p>Introduced <x-link href="cypress" target="_blank">Cypress</x-link> e2e testing in my current role. The tests trigger automatically with PR's as part of our CI/CD flow.</p>
                  </x-tag-label>
                </x-tag>
                <x-tag class="margin-top--10">
                  CMS
                  <x-tag-label>
                    <p><x-link href="https://buttercms.com/" target="_blank">Butter CMS</x-link> integration, enabling non-technical members to create and release marketing pages independently using existing, flexible components.</p>
                  </x-tag-label>
                </x-tag>
                <x-tag class="margin-top--10">
                  Git
                  <x-tag-label>
                    <p>Vital tool in current development workflow.</p>
                    <p>Experience with Github and <x-link href="https://bitbucket.org/" target="_blank">Bitbucket</x-link> web UI's.</p>
                  </x-tag-label>
                </x-tag>
                <x-tag class="margin-top--10">
                  Design systems
                  <x-tag-label>
                    <p>Developing design systems to ensure projects are set-up for success. Build faster, cleaner, more consistently, and with scale in mind. I've built <x-link href="https://www.stylx.dev/" target="_blank">my own component library.</x-link></p>
                  </x-tag-label>
                </x-tag>
              </div>
            </x-carousel-item>
            <x-carousel-item>
              <h2 class="margin-bottom--20">Instructor</h2>
              <p>Delivering weekly lectures to students new to web development at one of Canada's leading tech education companies</p>
              <p>Fostering an inclusive and casual learning environment</p>
              <div class="margin-top--20">
                <h3 class="h5 heading--accent">Curriculum topics:</h3>
                <p>
                  Development workflows (version control, git, pull requests),
                  HTML,
                  CSS,
                  Ruby,
                  <x-link href="http://sinatrarb.com/" target="_blank">Sinatra</x-link>,
                  <x-link href="https://guides.rubyonrails.org/active_record_querying.html#what-is-the-active-record-query-interface-questionmark" target="_blank">Active Record</x-link>,
                  Relational Databses,
                  Deployment
                </p>
              </div>
            </x-carousel-item>
            <x-carousel-item>
              <h2 class="margin-bottom--20">Artisan</h2>
              <p>Creating art with digital and traditional mediums</p>
              <p>I frequently experiment with different mediums, with my current focus being on printmaking</p>
              <div class="margin-top--20 margin-bottom--30">
                <x-tag class="margin-top--10">
                  Illustration
                  <x-tag-label>
                    <p>Drawing illustrations using <x-link href="https://procreate.art/" target="_blank">Procreate</x-link> on my iPad.</p>
                  </x-tag-label>
                </x-tag>
                <x-tag class="margin-top--10">
                  Linocut
                  <x-tag-label>
                    <p>Printmaking technique: A design is carved into a soft linoleum block. Ink is used to transfer the design onto paper.</p>
                  </x-tag-label>
                </x-tag>
                <x-tag class="margin-top--10">
                  Watercolour
                  <x-tag-label>
                    <p>Creating one-of-a-kind watercolour portraits of people's beloved pets.</p>
                  </x-tag-label>
                </x-tag>
                <x-tag class="margin-top--10">
                  Screenprinting
                  <x-tag-label>
                    <p>Creating custom screens with photo emulsion in a darkroom. The screens are used to transfer ink onto fabrics. I sew the resulting textiles into practical items.</p>
                  </x-tag-label>
                </x-tag>
              </div>
            </x-carousel-item>
          </x-carousel>
        </x-group>
      </x-content>
    </x-section>
    <x-section wave="top" as="secondary-light">
      <x-icon as="secondary" icon="code" class="margin--center margin-bottom--20"/>
      <h2 class="heading--accent margin-bottom--60 text-align--center">Recent Projects</h2>
      <x-content>
        <recent-projects/>
      </x-content>
    </x-section>
    <x-section id="swap" ref="resizeContainer">
        <img class="swap__img--spotlight2" :class="{'on': spotlight2}" src="~@/assets/images/index/spotlight.svg" alt="">
        <div class="swap__img-wrap">
          <div class="swap__wrap--swim">
          <img class="swap__img--swim" src="~@/assets/images/index/swim.png" alt="">
        </div>
      </div>
      <div class="resize__wrap" :style="`width: ${demoWidth}px;`">
        <button ref="resize" id="resize"
          @mousedown="start"
          @mouseup="stop">
          <x-icon icon="arrows-alt-h"/>
        </button>
        <div class="swap__wrap--run">
          <div class="swap__img-wrap">
            <img class="swap__img--spotlight1" :class="{'on': spotlight1}" src="~@/assets/images/index/spotlight.svg" alt="">
            <img class="swap__img--run" src="~@/assets/images/index/run.png" alt="">
          </div>
        </div>
      </div>
    </x-section>
    <x-section size="lg">
      <x-content>
        <x-group as="center" size="sm" class="text-align--center">
          <h2 class="h3">Let's connect?</h2>
          <x-link href="https://www.linkedin.com/in/laura-penstone-073431111/" as="standard" size="lg" class="margin-top--20">View LinkedIn</x-link>
        </x-group>
      </x-content>
    </x-section>
  </div>
</template>

<script>
import recentProjects from '../components/recent-projects/recent-projects'

export default {
  name: 'index',
  components: {
    'recent-projects': recentProjects
  },
  data () {
    return {
      demoWidth: 1000,
      maxWidth: 1000,
      minWidth: 50,
      swapWidth: 400,
      timer: null,
      x1: 0,
      x2: 0,
      spotlight1: true,
      spotlight2: false
    }
  },
  mounted: function () {
    this.getMaxWidth()
    window.addEventListener('resize', this.getMaxWidth)
    this.$refs.resize.addEventListener('touchstart', this.mobileStart, true)
  },
  methods: {
    getMaxWidth: function () {
      let elWidth = this.$refs.resizeContainer.$el.clientWidth
      this.maxWidth = 0.95 * elWidth
      this.swapWidth = 0.4 * this.maxWidth
      const reachedMax = (0.9 * elWidth) > 1100
      this.demoWidth = reachedMax ? 1100 : (0.9 * elWidth)
      if (this.demoWidth > this.maxWidth) this.demoWidth = this.maxWidth
    },
    start: function (e) {
      this.x1 = e.screenX
      this.x2 = e.screenX
      window.addEventListener('mouseup', this.stop)
      window.addEventListener('mousemove', this.resize)
    },
    resize: function (e) {
      this.x2 = e.screenX
      let diff = this.x2 - this.x1
      this.demoWidth += diff

      if (this.demoWidth > this.maxWidth) this.demoWidth = this.maxWidth
      if (this.demoWidth < this.minWidth) this.demoWidth = this.minWidth
      this.x1 = this.x2
      this.spotlightCheck()
    },
    mobileStart: function (e) {
      this.x1 = parseInt(e.touches[0].screenX)
      this.x2 = parseInt(e.touches[0].screenX)

      this.$refs.resize.addEventListener('touchmove', this.mobileResize, true)
      this.$refs.resize.addEventListener('touchend', this.stop, true)
    },
    mobileResize: function (e) {
      this.x2 = parseInt(e.touches[0].screenX)
      let diff = this.x2 - this.x1
      this.demoWidth += diff

      if (this.demoWidth > this.maxWidth) this.demoWidth = this.maxWidth
      if (this.demoWidth < this.minWidth) this.demoWidth = this.minWidth
      this.x1 = this.x2
      this.spotlightCheck()
    },
    stop: function (e) {
      window.removeEventListener('mousemove', this.resize)
      window.removeEventListener('mouseup', this.stop)

      this.$refs.resize.removeEventListener('touchmove', this.resize, true)
      this.$refs.resize.removeEventListener('touchend', this.stop, true)
    },
    spotlightCheck: function () {
      if(this.spotlight1 && (this.demoWidth < this.swapWidth)) {
        this.spotlight1 = false
        this.spotlight2 = true
      }
      if(this.spotlight2 && (this.demoWidth > this.swapWidth)) {
        this.spotlight1 = true
        this.spotlight2 = false
      }
    }
  },
  destroyed: function () {
    window.removeEventListener('resize', this.getMaxWidth)
  }
}
</script>

<style lang="stylus" scoped>
@import '~@/assets/styles/variables'

@keyframes flickerAnimation {
  0%   { opacity:1 }
  1%  { opacity:1 }
  2%  { opacity:0 }
  5%  { opacity:1 }
  6%  { opacity:0 }
  28%  { opacity:1 }
  100% { opacity:1 }
}

@keyframes vennRightAnimation {
  0%   { transform: translate(170px, 0); }
  50%  { transform: translate(50px, 0); }
  60%  { transform: translate(50px, 0); }
  100%  { transform: translate(170px, 0); }
}

@keyframes vennLeftAnimation {
  0%   { transform: translate(-170px, 0); }
  50%  { transform: translate(-50px, 0); }
  60%  { transform: translate(-50px, 0); }
  100%  { transform: translate(-170px, 0); }
}

@keyframes vennMagicAnimation {
  0%   { width: 0px }
  15%  { width: 0px }
  34%  { width: 76px }
  65%  { width: 76px }
  71%  { width: 0px }
  100%  { width: 0px }
}

>>>#hero
  padding-top: 0
  padding-bottom: 0
  height: 90vh
  max-height: 660px

  @media(max-width: 991px)
    padding-top: 120px
    height: auto
    max-height: 100%

  .section__inner
    height: 100%

  .container
    height: 100%

  .hero__content
    display: flex
    flex-direction: column
    height: 100%
    justify-content: center

  .hero__copy
    position: relative
    z-index: 1

  .hero__doodle
    position: absolute
    max-width: 700px
    bottom: 0
    right: 0
    order: 2
    
    @media(max-width: 991px)
      position: relative
      display: block

  .hero__doodle--light
    display: block

  .hero__doodle--dark
    display: none


.mode--dark
  #hero
    .hero__doodle--light
      display: none

    .hero__doodle--dark
      display: block

#hats
  padding-bottom: 20px

#venn
  margin-bottom: 100px

  .venn__wrap
    display: flex
    position: relative
    height: 200px
    justify-content: center

  .venn__label
    font-family: 'Sacramento', cursive
    font-size: 38px

  .venn__label--left
    padding-right: 60px

    @media(max-width: 767px)
      padding-right: 40px

  .venn__label--right
    padding-left: 60px

    @media(max-width: 767px)
      padding-left: 40px

  .venn__label--magic
    position: absolute
    display: flex
    align-items: center
    justify-content: center
    height: 100px
    top: 45px
    color: $secondary
    animation: vennMagicAnimation 5s infinite
    overflow: hidden
    border-radius: 48%

  .venn__img
    position: absolute
    width: 76px

  .venn__img--lm
    display: block

  .venn__img--dm
    display: none

  .venn__circle
    position: absolute
    display: block
    height: 200px
    width: 200px
    border-radius: 50%

  .venn__circle--left
    background-color: $brand
    opacity: 0.2
    display: block
    animation: vennLeftAnimation 5s infinite

  .venn__circle--right
    background-color: $secondary
    opacity: 0.2
    display: block
    animation: vennRightAnimation 5s infinite

.mode--dark
  #venn
    .venn__img--lm
      display: none

    .venn__img--dm
      display: block

#resize
  position: absolute
  width: 50px
  height: 50px
  border-radius: 50%
  background-color: $brand
  border: none
  top: 40%
  right: -25px
  z-index: 5
  outline: 0
  color: white !important
  cursor: ew-resize

#swap
  background-color: lighten($brand-xxlight, 60%)
  padding: 0
  position: relative

  .resize__wrap
    height: 100%
    display: inline-block
    position: absolute
    top: 0
    left: 0
    border-right: 3px solid $brand

  .swap__wrap--swim, .swap__wrap--run
    position: relative
    padding-right: 20px
    padding-left: 20px
    overflow: hidden

  .swap__wrap--swim
    width: 100%
    padding-top: 0px
    padding-bottom: 30px

  .swap__wrap--run
    width: 100%
    position: absolute
    top: 0
    left: 0
    padding-top: 60px
    background-color: lighten($secondary-xxlight, 40%)
    padding-bottom: 50px
    z-index: 4

    @media(max-width: 767px)
      padding-top: 20px

  .swap__img--spotlight1
    width: 950px
    position: absolute
    top: -265px
    left: 80px
    transform: rotate(-21deg)
    display: none
    animation: flickerAnimation 6s infinite

    @media(max-width: 900px)
      left: -18%

    @media(max-width: 767px)
      top: -185px
      left: -22%
      width: 450px

  .swap__img--spotlight2
    width: 950px
    position: absolute
    bottom: -185px
    left: 13%
    transform: rotate(210deg)
    display: none
    animation: flickerAnimation 3s infinite

    @media(max-width: 900px)
      left: -12%

    @media(max-width: 767px)
      width: 450px

  .swap__img-wrap
    width: 1250px
    position: relative

    @media(max-width: 767px)
      width: 500px

  .swap__img--run, .swap__img--swim
    position: relative
    display: block
    margin: auto
    z-index: 3

    @media(max-width: 900px)
      margin: 0

  .swap__img--run
    width: 600px

    @media(max-width: 767px)
      width: 320px

  .swap__img--swim
    width: 670px

    @media(max-width: 767px)
      width: 320px

.mode--dark
  #swap
    background-color: darken($brand-xxdark, 60%)

    .swap__wrap--run
      background-color: darken($secondary-xxdark, 40%)

    .swap__img--spotlight1, .swap__img--spotlight2
      display: none

      &.on
        display: block

</style>
