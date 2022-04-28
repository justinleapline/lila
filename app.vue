<template>
  <div class="relative">
    <Head>
      <Title>Lila's Fun Adventure</Title>
      <Meta name="description" content="Lila's Fun Adventure" />
    </Head>
    <!-- Lila Heading -->
    <div class="lg:relative bg-lilablue">
      <div
        class="mx-auto max-w-7xl w-full pt-16 pb-20 text-center lg:py-48 lg:text-left"
      >
        <div class="px-4 lg:w-1/2 sm:px-8 xl:pr-16">
          <h1
            class="text-4xl tracking-tight font-extrabold text-gray-900 sm:text-5xl md:text-6xl lg:text-5xl xl:text-6xl"
          >
            <span class="block xl:inline">Lila's</span>
            {{ ' ' }}
            <span class="block text-lilapurple xl:inline">Fun Adventure</span>
          </h1>
          <p
            class="mt-3 max-w-md mx-auto text-lg text-gray-500 sm:text-xl md:mt-5 md:max-w-3xl"
          >
            Hi, I'm Lila. I'm a student and this is my first website. I love
            listening to music and playing with friends. I like to learn new
            things and my favorite teacher is Mr. Hartzell.
          </p>
        </div>
      </div>
      <div
        class="relative w-full h-64 sm:h-72 md:h-96 lg:absolute lg:inset-y-0 lg:right-0 lg:w-1/2 lg:h-full"
      >
        <img
          class="absolute inset-0 w-full h-full object-cover"
          src="~/assets/img/IMG_2719.jpeg"
          alt=""
        />
      </div>
    </div>
    <!-- End Lila Heading -->
    <!-- Music -->
    <div class="py-16 bg-white">
      <div
        class="lg:mx-auto lg:max-w-7xl lg:px-8 lg:grid lg:grid-cols-2 lg:grid-flow-col-dense lg:gap-24"
      >
        <div
          class="px-4 max-w-xl mx-auto sm:px-6 lg:py-32 lg:max-w-none lg:mx-0 lg:px-0 lg:col-start-2"
        >
          <div>
            <div class="mt-6">
              <h2
                class="text-3xl font-extrabold tracking-tight text-gray-900 mb-10"
              >
                Music I Love 🎶
              </h2>
              <iframe
                allow="autoplay *; encrypted-media *;"
                frameborder="0"
                height="150"
                style="
                  width: 100%;
                  max-width: 660px;
                  overflow: hidden;
                  background: transparent;
                "
                sandbox="allow-forms allow-popups allow-same-origin allow-scripts allow-storage-access-by-user-activation allow-top-navigation-by-user-activation"
                src="https://embed.music.apple.com/us/album/a-sky-full-of-stars/829909653?i=829910927"
              ></iframe>
              <iframe
                allow="autoplay *; encrypted-media *;"
                frameborder="0"
                height="150"
                style="
                  width: 100%;
                  max-width: 660px;
                  overflow: hidden;
                  background: transparent;
                "
                sandbox="allow-forms allow-popups allow-same-origin allow-scripts allow-storage-access-by-user-activation allow-top-navigation-by-user-activation"
                src="https://embed.music.apple.com/us/album/could-have-been-me/1592745677?i=1592746244"
              ></iframe>
              <iframe
                allow="autoplay *; encrypted-media *; fullscreen *"
                frameborder="0"
                height="175"
                style="
                  width: 100%;
                  max-width: 660px;
                  overflow: hidden;
                  background: transparent;
                "
                sandbox="allow-forms allow-popups allow-same-origin allow-scripts allow-storage-access-by-user-activation allow-top-navigation-by-user-activation"
                src="https://embed.music.apple.com/us/album/into-you/1568020268?i=1568020292"
              ></iframe>
            </div>
          </div>
        </div>
        <div class="mt-12 sm:mt-16 lg:mt-0 lg:col-start-1">
          <div
            class="pr-4 -ml-48 sm:pr-6 md:-ml-16 lg:px-0 lg:m-0 lg:relative lg:h-full"
          >
            <img
              class="w-full rounded-xl shadow-xl ring-1 ring-black ring-opacity-5 lg:absolute lg:h-full lg:w-auto lg:max-w-none"
              src="~/assets/img/IMG_2721.jpeg"
              alt="Rockin out"
            />
          </div>
        </div>
      </div>
    </div>
    <!-- End Music -->
    <!-- Family -->
    <div class="py-16 bg-lilatufts">
      <div
        class="lg:mx-auto lg:max-w-7xl lg:px-8 lg:grid lg:grid-cols-2 lg:grid-flow-col-dense lg:gap-24"
      >
        <div
          class="px-4 max-w-xl mx-auto sm:px-6 lg:py-32 lg:max-w-none lg:mx-0 lg:px-0"
        >
          <div>
            <div class="mt-6">
              <h2 class="text-3xl font-extrabold tracking-tight text-white">
                My Family 🏠
              </h2>
              <p class="mt-4 text-lg text-white">
                My family is sweet and I love them. I have a sister and two
                brothers. I always seem to have company with me.
              </p>
            </div>
          </div>
        </div>
        <div class="mt-12 sm:mt-16 lg:mt-0">
          <div
            class="pr-4 -ml-48 sm:pr-6 md:-ml-16 lg:px-0 lg:m-0 lg:relative lg:h-full"
          >
            <img
              class="w-full rounded-xl shadow-xl ring-1 ring-black ring-opacity-5 lg:absolute lg:h-full lg:w-auto lg:max-w-none"
              src="~/assets/img/IMG_2685.jpeg"
              alt="Family"
            />
          </div>
        </div>
      </div>
    </div>
    <!-- End Family -->
  </div>
</template>
