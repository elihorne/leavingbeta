<template>
  <div class="">
    <div class="intro bg-gray-900 text-white">
      <div class="container mx-auto">
        <header class="border-gray-700 border-b flex uppercase">
          <h1 class="font-bold text-2xl">
            <a class="inline-block p-3" href="/">Leaving Beta</a>
          </h1>
          <nav class="text-sm">
            <a class="p-4 inline-block" href="/products">Products</a>
            <a class="p-4 inline-block" href="/about">About</a>
          </nav>
        </header>
        <div class="intro text-center my-10 py-10 mx-auto">
          <h2 class="uppercase text-3xl mb-4">
            Ideas are cheap, execution speaks.
          </h2>
          <p class="my-2">
            Leaving Beta is a holding company for a collection of ideas meant to
            solve everyday problems.
          </p>
          <p class="my-2">
            If you have a question or idea, please get in touch.
          </p>
        </div>
      </div>
    </div>
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
