<template>
  <div>
    <x-section class="bg-wave-bottom" as="hero" size="lg" top>
      <x-content class="text-align--center">
        <x-icon as="secondary" icon="comments" class="margin--center margin-bottom--30"/>
        <h1>Let's chat</h1>
        <p>Communication welcome via <x-link href="https://www.linkedin.com/in/laura-penstone-073431111/" target="_blank">LinkedIn</x-link> or message form below.</p>
      </x-content>
    </x-section>
    <x-section>
      <x-content>
        <x-group as="center" size="md">
          <div v-if="success" class="text-align--center">
            <div class="h2">👏</div>
            <h2 class="h3">Thanks!</h2>
            <p>I look forward to reading your message, and I'll reply as soon as I can.</p>
            <x-button @click="reset()" class="margin-top--20">New message</x-button>
          </div>
          <x-card v-else as="shadow" size="lg">
            <h2 class="heading--title margin-bottom--20">Send a message</h2>
            <x-form as="submit" name="contact" method="POST" netlify action="/contact/?notice=success">
              <x-form-input as="text" name="name" label="Name" required/>
              <x-form-input as="email" name="email" label="Email" required/>
              <x-form-group as="select" name="subject" label="Subject" required>
                <x-form-group-option name="art" label="Art inquiry"/>
                <x-form-group-option name="business" label="Business inquiry"/>
                <x-form-group-option name="hi" label="Saying hi"/>
                <x-form-group-option name="other" label="Other"/>
              </x-form-group>
              <x-form-input as="textarea" name="message" label="Message" required/>
            </x-form>
          </x-card>
        </x-group>
      </x-content>
    </x-section>
  </div>
</template>

<script>
export default {
  data () {
    return {
      success: this.$route.query.notice && this.$route.query.notice === 'success'
    }
  },
  mounted: function () {
    this.$router.push({name: 'contact'})
  },
  methods: {
    reset: function () {
      this.success = false
    }
  }
}
</script>
