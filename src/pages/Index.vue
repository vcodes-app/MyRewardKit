<template>
  <Layout>
    <section class="flex flex-wrap-reverse flex-1">

      <div class="ml-12 content">
        <h1 class="page-title"> My Reward Kit</h1>
        <p>
          An
          <a class="font-bold text-purple-650">AWESOME</a> reward kit built for
          <a class="font-bold text-purple-650">Parents and Kids</a>.
        </p>
        <h2 class="text-3xl">For Prarents</h2>
        <ul class="pl-4 mb-12 list-disc">
          <li>Easy management of tasks</li>
          <li>Develop a positive feedback/reward system</li>
          <li>Help keep your promises</li>
        </ul>
        <h2 class="text-3xl">For Kids</h2>
        <ul class="pl-4 mb-12 list-disc">
          <li>Easy management of tasks</li>
          <li>Efforts paid off </li>
        </ul>
      </div>
      <g-image class="ml-12" src="~/myreward.png" width="500"></g-image>
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


