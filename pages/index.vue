<template>
  <div class="">
    <Header />
    <div class="container mx-auto">
      <h3 class="text-xl font-bold uppercase mb-4">Products</h3>
      <ol>
        <li>
          <a class="font-bold" href="https://feedmirror.com">Feedmirror</a>
          <p class="my-3 max-w-2xl">
            Feedmirror fetches remote feeds on a regular, scheduled basis. The
            feeds are mirrored on fast, geographically distributed servers with
            permissions that allow the data to be requested and used on any
            website.
          </p>
          <span class="status"
            ><span class="font-bold">Status:</span> In contract</span
          >
        </li>
      </ol>
      <div
        class="bio my-10 rounded-xl overflow-hidden bg-gray-900 text-white flex"
      >
        <div class="meta flex-none p-10 w-1/3">
          <h4 class="font-bold uppercase mb-4">Founder/owner</h4>
          <p class="my-2">
            Eli Horne is a designer, developer and entrepreneur who enjoys
            learning new technologies through exploration.
          </p>
          <nuxt-link
            to="/about"
            class="inline-block mt-4 bg-white rounded-xl text-black p-3"
            href="/about"
            >Learn more</nuxt-link
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
