<template>
  <div>
    <x-section class="section--wave-bottom" as="hero" size="lg" top>
      <x-content class="text-align--center">
        <x-icon as="secondary" icon="code" class="margin--center margin-bottom--30"/>
        <h1>Laura Penstone</h1>
        <h2 class="heading--title margin-bottom--30">Frontend Developer</h2>
        <p>3+ years of industry experience writing scalable, tested, component-based code.</p>
        <P>Developing beautiful UI's that are accessible to all audiences.</p>
        <x-link as="standard" href="https://www.linkedin.com/in/laura-penstone-073431111/" target="_blank" class="margin-top--20">LinkedIn</x-link>
        <x-link as="hollow" href="/files/Laura_Penstone_Resume.pdf" target="_blank" class="margin-top--20" download icon="download" aria-label="download Laura Penstone resume">Download</x-link>
      </x-content>
    </x-section>
    <x-section>
      <x-content>
        <div class="row">
          <div class="col-sm-12 col-md-7">
            <h3 class="heading--accent margin-bottom--20">Experience</h3>
            <div>
              <h4 class="heading--title">Software Engineer (Frontend)</h4>
              <h5 class="h6">TunnelBear LLC - <em>November 2017 to Present</em></h5>
              <p class="margin-top--20 margin-bottom--20">
                Worked on a wide variety of web projects, using popular tools and frameworks, while also reducing technical debt.
                <ul class="font-size--sm">
                  <li>Full framework migration from Angular.js to Vue.js</li>
                  <li>Complete web rebrand: website, blog theme, support portal</li>
                  <li>Rebuilt the TunnelBear for Teams web app</li>
                  <li>Interactive animations, such as this <x-link href="https://help.tunnelbear.com/hc/en-us" target="_blank">search field animation</x-link> and <x-link href="https://www.tunnelbear.com/account/login" target="_blank">login form</x-link></li>
                </ul>
              </p>
              <p class="margin-bottom--20">Led initiatives to help scale existing web projects.
                <ul class="font-size--sm">
                  <li>Cypress e2e test coverage</li>
                  <li>Integrated a headless CMS, creating autonomy for the marketing team</li>
                </ul>
              </p>
              <p class="margin-bottom--20">Introduced systems to improve the web team workflow.
                <ul class="font-size--sm">
                  <li>Automations to reduce toil</li>
                  <li>Guidelines to fix team pain points (pull requests, code reviews, deployment)</li>
                  <li>Created a culture of documentation</li>
                </ul>
              </p>
              <div class="margin-top--20">
                <h6 class="margin-top--20">Culture &amp; Community</h6>
                <p class="margin-top--10">Founded a community outreach group, with a mission to give back to the local community and make STEM careers accessible to people of all backgrounds.</p>
                <ul class="font-size--sm">
                  <li>Hosted two resume review workshops for those new to the tech industry</li>
                  <li>Partnered with <x-link href="https://www.venturekids.ca" target="_blank">VentureKids</x-link> to teach under-resourced youth how to code</li>
                </ul>
                <p class="margin-top--10">
                  Trivia club co-host: Fostering company inclusivity with team-based fun and useless facts.
                </p>
              </div>
            </div>
            <div class="margin-top--30">
              <h4 class="heading--title">Instructor &amp; Mentor</h4>
              <h5 class="h6">Lighthouse Labs - <em>October 2019 to Present</em></h5>
              <p>Delivering weekly lectures: Git & development workflow, HTML, CSS, Ruby, Sinatra, Active Record, relational databases, sessions, cookies, and deployment.</p>
              <p class="margin-top--10">Fostering an inclusive and unintimidating learning environment by encouraging student input, questions, and humour.
                <ul>
                  <li>Preparing coding activities and running live demos</li>
                  <li>Creating illustrations to break down difficult concepts into familiar ideas</li>
                </ul>
              </p>
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
                <x-tag as="#888888" class="margin-top--5">HTML</x-tag>
                <x-tag as="#888888" class="margin-top--5">CSS/Stylus</x-tag>
                <x-tag as="#888888" class="margin-top--5">Javascript</x-tag>
                <x-tag as="#888888" class="margin-top--5">Vue.js</x-tag>
                <x-tag as="#888888" class="margin-top--5">Nuxt.js</x-tag>
                <x-tag as="#888888" class="margin-top--5">Web sockets</x-tag>
                <x-tag as="#888888" class="margin-top--5">Cypress</x-tag>
                <x-tag as="#888888" class="margin-top--5">Headless CMS</x-tag>
                <x-tag as="#888888" class="margin-top--5">Webpack</x-tag>
              </div>
              <div class="margin-top--20">
                <h4 class="h6">Design</h4>
                <x-tag as="#888888" class="margin-top--5">Adobe Photoshop</x-tag>
                <x-tag as="#888888" class="margin-top--5">Adobe Illustrator</x-tag>
                <x-tag as="#888888" class="margin-top--5">Figma</x-tag>
                <x-tag as="#888888" class="margin-top--5">Procreate</x-tag>
                <x-tag as="#888888" class="margin-top--5">svg</x-tag>
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

