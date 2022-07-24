<template>
  <div>
    <x-section class="section--wave-bottom" as="hero" size="lg" top>
      <x-content class="text-align--center">
        <x-icon as="secondary" icon="code" class="margin--center margin-bottom--30"/>
        <h1>Laura Penstone</h1>
        <h2 class="heading--title margin-bottom--30">Frontend Developer</h2>
        <p>5 years of industry experience writing scalable, tested, component-based code.</p>
        <p>Developing beautiful UI's that are accessible to all audiences.</p>
        <x-link as="standard" href="https://www.linkedin.com/in/laura-penstone-073431111/" target="_blank" class="margin-top--20">LinkedIn</x-link>
      </x-content>
    </x-section>
    <x-section>
      <x-content>
        <div class="row">
          <div class="col-sm-12 col-md-7">
            <h3 class="heading--accent margin-bottom--20">Experience</h3>
            <div>
              <h4 class="heading--title">Software Engineer (Frontend)</h4>
              <h5 class="h6">Slack Technologies, LLC - <em>March 2021 to Present</em></h5>
            </div>
            <div class="margin-top--30">
              <h4 class="heading--title">Software Engineer (Frontend)</h4>
              <h5 class="h6">TunnelBear, LLC - <em>November 2017 to February 2021</em></h5>
            </div>
            <div class="margin-top--30">
              <h4 class="heading--title">Instructor &amp; Mentor</h4>
              <h5 class="h6">Lighthouse Labs - <em>October 2019 to September 2021</em></h5>
            </div>
            <div class="margin-top--30">
              <p>Please get in touch if you would like to see my full resume.</p>
            </div>
          </div>
          <div class="col-sm-12 col-md-4 offset-md-1">
            <div class="margin-top--30">
              <h3 class="heading--accent margin-bottom--20">Education</h3>
              <p><strong>Lighthouse Labs</strong> - Web Development diploma</p>
              <p><strong>Queen's University</strong> - Bachelor of Applied Science (Mechanical Engineering)</p>
            </div>
            <div class="margin-top--30">
              <h3 class="heading--accent margin-bottom--20">Skills Overview</h3>
              <div class="margin-top--20">
                <h4 class="h6">Tools</h4>
                <x-tag as="#888888" class="margin-top--5">Javascript</x-tag>
                <x-tag as="#888888" class="margin-top--5">React</x-tag>
                <x-tag as="#888888" class="margin-top--5">Redux</x-tag>
                <x-tag as="#888888" class="margin-top--5">Jest</x-tag>
                <x-tag as="#888888" class="margin-top--5">Vue.js</x-tag>
                <x-tag as="#888888" class="margin-top--5">Nuxt.js</x-tag>
                <x-tag as="#888888" class="margin-top--5">Web sockets</x-tag>
                <x-tag as="#888888" class="margin-top--5">Cypress</x-tag>
                <x-tag as="#888888" class="margin-top--5">Headless CMS</x-tag>
                <x-tag as="#888888" class="margin-top--5">HTML</x-tag>
                <x-tag as="#888888" class="margin-top--5">CSS/Stylus/Less</x-tag>
              </div>
              <div class="margin-top--20">
                <h4 class="h6">Design</h4>
                <x-tag as="#888888" class="margin-top--5">Adobe Photoshop</x-tag>
                <x-tag as="#888888" class="margin-top--5">Adobe Illustrator</x-tag>
                <x-tag as="#888888" class="margin-top--5">Figma</x-tag>
                <x-tag as="#888888" class="margin-top--5">Procreate</x-tag>
              </div>
              <div class="margin-top--20">
                <h4 class="h6">Workflow</h4>
                <x-tag as="#888888" class="margin-top--5">Git</x-tag>
                <x-tag as="#888888" class="margin-top--5">Netlify</x-tag>
                <x-tag as="#888888" class="margin-top--5">Agile</x-tag>
                <x-tag as="#888888" class="margin-top--5">Design systems</x-tag>
                <x-tag as="#888888" class="margin-top--5">UI/UX Design</x-tag>
              </div>
            </div>
          </div>
        </div>
      </x-content>
    </x-section>
    <x-section>
      <h2 class="heading--accent margin-bottom--60 text-align--center">Recent Projects &amp; Ventures</h2>
      <x-content>
        <recent-projects/>
      </x-content>
    </x-section>
  </div>
</template>

<script>
import recentProjects from '../components/recent-projects/recent-projects'

export default {
  name: 'resume',
  components: {
    'recent-projects': recentProjects
  },
  data () {
    return {}
  }
}
</script>

<style lang="stylus" scoped>
  .border-top--solid
    border-top: 1px solid lightgrey
</style>

