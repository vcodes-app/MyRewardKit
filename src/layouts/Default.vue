<template>
  <div>
    <a class="visually-hidden" href="#main">Skip to content</a>

    <div id="wrapper" class="relative flex flex-col min-h-screen pb-16 wrapper md:pb-0">

      <HeaderPartial />


      <main id="main" class="flex py-10 main inner lg:py-20">
        <slot />
      </main>

      <FooterPartial />

    </div>

    <ClientOnly>
      <ResponsiveNav />
    </ClientOnly>

  </div>
</template>

<static-query>
query {
  metadata {
    siteName
  }
}
</static-query>

<script>
import HeaderPartial from '~/layouts/partials/Header.vue'
import FooterPartial from '~/layouts/partials/Footer.vue'
import ResponsiveNav from '~/layouts/partials/ResponsiveNav.vue'

export default {
  components: {
    HeaderPartial,
    FooterPartial,
    ResponsiveNav
  }
}
</script>