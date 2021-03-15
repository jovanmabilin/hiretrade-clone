<template>
  <div>
    <header-content />
    <body-content />
    <footer-content />
  </div>
</template>

<script>
  import HeaderContent from '../view/Header'
  import BodyContent from '../view/Body'
  import FooterContent from '../view/Footer'
  export default {
    components: {
      HeaderContent,
      BodyContent,
      FooterContent,
    }
  }
</script>