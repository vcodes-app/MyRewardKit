<template>
  <Layout>
    <section id="container-centre" class="flex-1 column centre">
      <h1 class="page-title">Contact Us</h1>
      <div class="content">
        <p>Tell us wht's been bothering you in the form below.</p>
        <form class="form">
          <div class="row required">
            <label for="name">Name</label>
            <input class="input" id="name" type="text" name="name" autocomplete="name" required aria-required="true" />
          </div>
          <div class="row required">
            <label for="email">Email</label>
            <input class="input" id="email" type="text" name="email" autocorrect="off" autocapitalize="off"
              autocomplete="email" required aria-required="true" />
          </div>
          <div class="row required">
            <label for="phone">Phone</label>
            <input class="input" id="phone" type="text" name="phone" autocomplete="tel" required aria-required="true" />
          </div>
          <div class="row">
            <label for="message">Message</label>
            <textarea class="textarea" id="message" name="message"></textarea>
          </div>&nbsp;
          <div class="row">
            <button class="inline-block px-6 py-4 font-bold text-white bg-pink-500 rounded hover:bg-pink-600"
              type="submit">Send message!</button>
          </div>
        </form>
      </div>
    </section>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "Support"
  }
};
</script>
