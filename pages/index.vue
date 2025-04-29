<template>
<div>
  <Button/>

<h1 class="text-4xl">Hello World </h1>
</div>
</template>
    <script>
    import '../assets/scss/index.scss';
    import Button from '../components/button/Button.vue';

    export default {
      components: { 
        Button
      },
      head() {
        return {
          link: [
            { rel: 'stylesheet', href: '../assets/css/index.css' }
          ]
        }
      }
    }
    </script>
