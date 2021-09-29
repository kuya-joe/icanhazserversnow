<template>
  <section class="section">
    <div class="columns is-mobile">
      <card
        title="Free"
        icon="github"
      >
          <code>
         <pre>
           $  sudo fallocate -l 1G /swapfile
           $ sudo mkswap /swapfile
           $ sudo swapon /swapfile
           # Check if free
           $ free -h

</pre>

          </code>
      </a>
      </card>

      <card
        title="Responsive"
        icon="cellphone-link"
      >
        <b class="has-text-grey">
          Every
        </b> component is responsive
      </card>

      <card
        title="Modern"
        icon="alert-decagram"
      >
        Built with <a href="https://vuejs.org/">
          Vue.js
        </a> and <a href="http://bulma.io/">
          Bulma
        </a>
      </card>

      <card
        title="Lightweight"
        icon="arrange-bring-to-front"
      >
        <NuxtLink  to="/add-swap-to-server">How to add swap space to linux server</NuxtLink>
      </card>
    </div>
  </section>
</template>

<script>
import Card from '~/components/Card'

export default {
  name: 'HomePage',

  components: {
    Card
  }
}
</script>
