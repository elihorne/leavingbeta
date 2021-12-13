<template>
  <div class="">
    <Header />
    <div class="container mx-auto">
      <h3 class="text-xl font-bold uppercase mb-4">About</h3>
      <p class="mb-4">
        Leaving Beta, LLC was formed in 2021 to serve as a holding company for
        the various ideas and explorations of its founder, Eli Horne.
      </p>
      <h3 class="text-xl font-bold uppercase mb-4">Contact</h3>
      <p class="mb-4">
        If you'd like to get in touch, you send email to info@leavingbeta.com or
        send physical correspondence to:
      </p>
      <p>
        9450 SW Gemini Dr <br />PMB 41471 <br />Beaverton, Oregon 97008-7105 US
      </p>

      <div
        class="bio my-10 rounded-xl overflow-hidden bg-gray-900 text-white flex"
      >
        <div class="meta flex-none p-10 w-1/3">
          <h4 class="font-bold uppercase mb-4">Founder/owner</h4>
          <p class="my-2">
            Eli Horne is a designer, developer and entrepreneur who enjoys
            learning new technologies through exploration.
          </p>
          <a
            class="inline-block mt-4 bg-white rounded-xl text-black p-3"
            href="/about"
            >Learn more</a
          >
        </div>
        <div class="img">
          <img
            src="https://elihorne.com/photos/eli-plane-iceland.jpg"
            alt="Eli Horne"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "IndexPage",
};
</script>
