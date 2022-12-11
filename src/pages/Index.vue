<template>
  <Layout>
    <section id="container-centre" class="flex flex-wrap-reverse centre">

      <div class="justify-center content">
        <h1 class="page-title"> My Reward Kit</h1>
        <p>
          A
          <a href="https://www.gridsome.org">Gridsome</a> starter built with
          <a href="https://tailwindcss.com">TailwindCSS</a>.
        </p>
        <h2 class="text-3xl">Features</h2>
        <ul class="pl-4 mb-12 list-disc">
          <li>Build sites faster with the power of Gridsome, TailwindCSS and SCSS</li>
          <li>Image lazyloading via gridsome builtin functionality</li>
          <li>A simple blog with categories, tags and featured images</li>
        </ul>
        <h2 class="text-3xl">Credits</h2>
        <p>
          This template was built for <a href="https://www.11ty.dev/docs/" target="_blank">Eleventy</a> by <a
            href="https://github.com/josephdyer" target="_blank"> Joseph Dyer</a>.
        </p>
      </div>
      <g-image src="~/myreward.png" width="500"></g-image>
    </section>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "Home"
  }
};
</script>
