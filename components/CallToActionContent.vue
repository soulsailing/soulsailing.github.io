<template>
  <section class="container mx-auto text-center py-6 mb-12">
    <h1
      class="w-full my-2 text-5xl font-bold leading-tight text-center text-white"
    >
      Call to Action
    </h1>
    <div class="w-full mb-4">
      <div
        class="h-1 mx-auto bg-white w-1/6 opacity-25 my-0 py-0 rounded-t"
      ></div>
    </div>

    <h3 class="my-4 text-3xl leading-tight">
      Main Hero Message to sell yourself!
    </h3>

    <form
        action="https://formspree.io/f/mlezeloa"
        method="POST"
      >
        <label>
          Your email:
          <input type="email" name="_replyto">
        </label>
        <label>
          Your message:
          <textarea name="message"></textarea>
        </label>
        <!-- your other form fields go here -->
        <button type="submit">Send</button>
    </form>
  </section>
</template>

<script>
export default {
  name: 'CallToActionContent'
}
</script>
