<template>
  <div>
    <x-section as="hero" size="lg" top>
      <x-content class="text-align--center">
        <x-icon as="secondary" icon="code" class="margin--center margin-bottom--30"/>
        <h1>Laura Penstone</h1>
        <h2 class="heading--title margin-bottom--30">Frontend Developer</h2>
        <p>3+ years of industry experience writing scalable, tested, component-based code.</p>
        <P>Developing beautiful UI's that are accessibile to all audiences.</p>
        <x-link as="standard" class="margin-top--20" href="https://linkedin.com">LinkedIn</x-link>
      </x-content>
    </x-section>
    <x-section>
      <x-content>
        <div class="row">
          <div class="col-sm-12 col-md-7">
            <h3 class="heading--accent margin-bottom--20">Experience</h3>
            <div>
              <h4 class="heading--title">Software Engineer (frontend)</h4>
              <h5 class="h6">TunnelBear LLC - <em>November 2017 to Present</em></h5>
              <p></p>
              <ul>
                <li>Introduced Cypress e2e testing coverage.</li>
                <li>Streamlined development workflows with Slack integrations and Github actions.</li>
                <li>Integrated TunnelBear landing pages with a headless CMS to enable the marketing team to edit and create pages independently.</li>
                <li>Rebuilt the TunnelBear for Teams web app.</li>
                <li>Completed the execution of a website re-brand.</li>
                <li>Assisted in framework migration from Angular to Vue, reducing technical debt and creating a component-based project.</li>
                <li>Created delightful and interactive animations.</li>
                  <x-link href="https://help.tunnelbear.com/hc/en-us">Typing animation</x-link>,
                  <x-link href="https://www.tunnelbear.com/account/login">Login form animation</x-link>
                <li>Advocate for documentation and knowledge sharing.</li>
              </ul>
              <div class="margin-top--20">
                <p>I've also started a Community Outreach team at TunnelBear. I run bi-weekly meetings, plan new initiatives, gather volunteers, and oversee the logistics for the events.</p>
                <p>Since July 2020, the group has:</p>
                <ul>
                  <li>Hosted 2 Resume Review workshops for those new to the tech industry</li>
                  <li>Created a partnership with Toronto local organization, VentureKids</li>
                  <li>Participated in a volunteer week, teaching kids to code with VentureKids</li>
                </ul>
              </div>
            </div>
            <div class="margin-top--30">
              <h4 class="heading--title">Instructor &amp; Mentor</h4>
              <h5 class="h6">Lighthouse Labs - <em>October 2019 to Present</em></h5>
              <ul>
                <li>Delivering weekly lectures to students new to web development. Topics include: Git & development workflow, HTML, CSS, Ruby, Sinatra, Active Record, relational databases, sessions, cookies, and deployment.</li>
                <li>Fostering an inclusive and casual learning environment.</li>
                <li>Providing live demos, encouraging student input and suggestions.</li>
                <li>Putting together breakout activities for students to practice their learnings with free tools sush as Codepen and repl.it.</li>
                <li>Helping students understand error messages and debug their code.</li>
              </ul>
            </div>
          </div>
          <div class="col-sm-12 col-md-4 offset-md-1">
            <div class="margin-top--30">
              <h3 class="heading--accent margin-bottom--20">Education</h3>
              <p><strong>Lighthouse Labs</strong> - Web Development diploma</p>
              <p><strong>Queen's University</strong> - Bachelor of Applied Science (Mechanical Engineering)</p>
            </div>
            <div class="margin-top--30">
              <h3 class="heading--accent margin-bottom--20">Skills</h3>
              <div class="margin-top--20">
                <h4 class="h6">Tools</h4>
                <x-tag as="#888888" class="margin-top--10">HTML</x-tag>
                <x-tag as="#888888" class="margin-top--10">CSS/Stylus</x-tag>
                <x-tag as="#888888" class="margin-top--10">Javascript</x-tag>
                <x-tag as="#888888" class="margin-top--10">Vue.js</x-tag>
                <x-tag as="#888888" class="margin-top--10">Nuxt.js</x-tag>
                <x-tag as="#888888" class="margin-top--10">Web sockets</x-tag>
                <x-tag as="#888888" class="margin-top--10">Cypress</x-tag>
                <x-tag as="#888888" class="margin-top--10">Headless CMS</x-tag>
                <x-tag as="#888888" class="margin-top--10">Webpack</x-tag>
              </div>
              <div class="margin-top--20">
                <h4 class="h6">Workflow</h4>
                <x-tag as="#888888" class="margin-top--10">Git</x-tag>
                <x-tag as="#888888" class="margin-top--10">Netlify</x-tag>
                <x-tag as="#888888" class="margin-top--10">Figma</x-tag>
                <x-tag as="#888888" class="margin-top--10">Agile</x-tag>
                <x-tag as="#888888" class="margin-top--10">Design systems</x-tag>
              </div>
            </div>
          </div>
        </div>
      </x-content>
    </x-section>
    <x-section>
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
  name: 'resume',
  components: {
    'recent-projects': recentProjects
  },
  data () {
    return {}
  }
}
</script>
