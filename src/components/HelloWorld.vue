<template>
  <div>
    <div v-if="$vuetify.breakpoint.name === 'xs'">
      <div style="margin-left: 158px;">
        <v-btn color="green">xs-button</v-btn>
      </div>
    </div>
    <div v-if="$vuetify.breakpoint.name === 'sm'">
      <div style="margin-left: 158px;">
        <v-btn color="orange">sm-button</v-btn>
      </div>
    </div>
    <div v-if="$vuetify.breakpoint.name === 'md'">
      <div style="margin-left: 158px;">
        <v-btn color="red">md-button</v-btn>
      </div>
    </div>
    <div v-if="$vuetify.breakpoint.name === 'lg'">
      <div style="margin-left: 158px;">
        <v-btn color="blue">lg-button</v-btn>
      </div>
    </div>
    <div v-if="$vuetify.breakpoint.name === 'xl'">
      <div style="margin-left: 158px;">
        <v-btn color="yellow">xl-button</v-btn>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'HelloWorld',

    data: () => ({
      ecosystem: [
        {
          text: 'vuetify-loader',
          href: 'https://github.com/vuetifyjs/vuetify-loader',
        },
        {
          text: 'github',
          href: 'https://github.com/vuetifyjs/vuetify',
        },
        {
          text: 'awesome-vuetify',
          href: 'https://github.com/vuetifyjs/awesome-vuetify',
        },
      ],
      importantLinks: [
        {
          text: 'Documentation',
          href: 'https://vuetifyjs.com',
        },
        {
          text: 'Chat',
          href: 'https://community.vuetifyjs.com',
        },
        {
          text: 'Made with Vuetify',
          href: 'https://madewithvuejs.com/vuetify',
        },
        {
          text: 'Twitter',
          href: 'https://twitter.com/vuetifyjs',
        },
        {
          text: 'Articles',
          href: 'https://medium.com/vuetify',
        },
      ],
      whatsNext: [
        {
          text: 'Explore components',
          href: 'https://vuetifyjs.com/components/api-explorer',
        },
        {
          text: 'Select a layout',
          href: 'https://vuetifyjs.com/getting-started/pre-made-layouts',
        },
        {
          text: 'Frequently Asked Questions',
          href: 'https://vuetifyjs.com/getting-started/frequently-asked-questions',
        },
      ],
    }),
  }
</script>
