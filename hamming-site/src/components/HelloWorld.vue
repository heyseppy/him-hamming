<template>
<div>
<large class="title-heading"> enter hamming code</large>
<large class="title-subheading"> check hamming code</large>
  <v-text-field
            class=" textbox centered-input"
            focus
  ></v-text-field>
  </div>
</template>
<style scoped>
  .title-heading
  {
    position: absolute;
    color: green;
    font-family: monospace;
    top: 4em;
    left: 35vw;
    font-size: 50px;
    font-weight: bold;
  }
  .title-subheading
  {
    position: absolute;
    color: purple;
    font-family: monospace;
    top: 17em;
    left: 35vw;
    font-size: 16px;
    font-weight: bold;
  }
  .textbox
  {
    
    display:inline-block;
    margin-left: 40vw;
    margin-right: 40vw;
    margin-top: 30vh;
    font-family: monospace;
    font-size: 2.6em;
    direction: RTL; 
    text-align: center;
    font-weight: bold;
  }
  .centered-input >>> input {
      text-align: center
    }
</style>
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
