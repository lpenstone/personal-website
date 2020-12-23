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
                    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/aa/Potcakedog.jpg/1920px-Potcakedog.jpg" alt="">
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
          <x-carousel height="240" name="about-me">
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
    <x-section class="section--wave-top" as="secondary-light">
      <x-icon as="secondary" icon="code" class="margin--center margin-bottom--20"/>
      <h2 class="heading--accent margin-bottom--60 text-align--center">Recent Projects</h2>
      <x-content>
        <recent-projects/>
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
    return {}
  }
}
</script>

<style lang="stylus" scoped>

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

</style>
