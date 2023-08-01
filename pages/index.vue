<script setup lang="ts">
import InstagramIcon from '~/statics/icons/instagram.vue'
</script>

<template>
  <div class="relative grid grid-cols-4">
    <div class="mx-5 mt-10">
      <div class="sticky top-5">
        <div id="profile">
          <div class="flex flex-col gap-5">
            <div class="h-32 w-32 overflow-hidden rounded-full bg-white p-5 shadow-md">
              <img src="../statics/bust_up.jpg" class="h-full w-full object-cover" />
            </div>
            <h1 class="text-3xl font-bold">John Doe Commission</h1>
            <div>
              <span
                class="pointer-events-none rounded-xl bg-green-400 px-5 py-2 text-white shadow-md"
                >Open</span
              >
            </div>
            <p class="text-gray-500">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Natus commodi amet ipsa
              exercitationem assumenda rerum veniam atque soluta nemo, fugit illo consequatur quod
              quos sed hic libero praesentium animi et.
            </p>
          </div>
        </div>
        <div id="contacts" class="mt-10 flex flex-col gap-3">
          <div id="instagram" class="group">
            <a href="https://www.instagram.com/yudis.enugraha/" target="_blank">
              <div class="flex gap-3">
                <div
                  class="relative flex h-10 w-10 cursor-pointer rounded-full bg-white text-center shadow-md"
                >
                  <InstagramIcon class="m-auto h-5 w-5 transition-all group-hover:animate-jello" />
                  <span class="sr-only">Follow on Instagram</span>
                </div>
                <div class="flex grow items-center">Instagram</div>
              </div>
            </a>
          </div>
          <div id="whatsapp" class="group">
            <a href="https://www.instagram.com/yudis.enugraha/" target="_blank">
              <div class="flex gap-3">
                <div
                  class="relative flex h-10 w-10 cursor-pointer rounded-full bg-white text-center shadow-md"
                >
                  <InstagramIcon class="m-auto h-5 w-5 transition-all group-hover:animate-jello" />
                  <span class="sr-only">Follow on Instagram</span>
                </div>
                <div class="flex grow items-center">Instagram</div>
              </div>
            </a>
          </div>
        </div>
      </div>
    </div>
    <div class="col-span-3 m-5">
      <section>
        <div id="hero" class="mx-auto mt-5 max-w-container">
          <div class="-ml-5 flex items-center justify-center gap-5 max-md:hidden">
            <div
              class="group flex flex-1 overflow-hidden transition-all duration-700 hover:grow-[10]"
            >
              <div class="relative h-96 flex-1">
                <img
                  src="../statics/bust_up.jpg"
                  class="h-full w-full object-cover transition-all duration-700 group-hover:grayscale-0"
                />

                <!-- <img
                  class="h-full w-full object-cover transition-all duration-700 group-hover:grayscale-0"
                  src="https://upload.wikimedia.org/wikipedia/commons/d/d6/Cat_plotting_something_evil%21.jpg"
                /> -->
                <div
                  class="absolute bottom-0 left-0 min-w-full origin-[0%_0%] -rotate-90 whitespace-nowrap bg-red-300 p-2 text-center text-sm text-black transition-all duration-700 group-hover:rotate-90 group-hover:bg-black/50 group-hover:text-xl group-hover:text-white group-hover:[transform:skew(0deg)]"
                >
                  Plotting Cat
                </div>
              </div>
            </div>
            <div
              class="group flex flex-1 overflow-hidden transition-all duration-700 hover:grow-[10]"
            >
              <div class="relative h-96 flex-1">
                <img
                  class="h-full w-full object-cover transition-all duration-700 group-hover:grayscale-0"
                  src="https://upload.wikimedia.org/wikipedia/commons/d/d6/Cat_plotting_something_evil%21.jpg"
                />
                <div
                  class="absolute bottom-0 left-0 min-w-full origin-[0%_0%] -rotate-90 whitespace-nowrap bg-red-300 p-2 text-center text-sm text-black transition-all duration-700 group-hover:rotate-90 group-hover:bg-black/50 group-hover:text-xl group-hover:text-white group-hover:[transform:skew(0deg)]"
                >
                  Plotting Cat
                </div>
              </div>
            </div>
            <div
              class="group flex flex-1 overflow-hidden transition-all duration-700 hover:grow-[10]"
            >
              <div class="relative h-96 flex-1">
                <img
                  class="h-full w-full object-cover transition-all duration-700 group-hover:grayscale-0"
                  src="https://upload.wikimedia.org/wikipedia/commons/d/d6/Cat_plotting_something_evil%21.jpg"
                />
                <div
                  class="absolute bottom-0 left-0 min-w-full origin-[0%_0%] -rotate-90 whitespace-nowrap bg-red-300 p-2 text-center text-sm text-black transition-all duration-700 group-hover:rotate-90 group-hover:bg-black/50 group-hover:text-xl group-hover:text-white group-hover:[transform:skew(0deg)]"
                >
                  Plotting Cat
                </div>
              </div>
            </div>
            <div
              class="group flex flex-1 overflow-hidden transition-all duration-700 hover:grow-[10]"
            >
              <div class="relative h-96 flex-1">
                <img
                  class="h-full w-full object-cover transition-all duration-700 group-hover:grayscale-0"
                  src="https://upload.wikimedia.org/wikipedia/commons/d/d6/Cat_plotting_something_evil%21.jpg"
                />
                <div
                  class="absolute bottom-0 left-0 min-w-full origin-[0%_0%] -rotate-90 whitespace-nowrap bg-red-300 p-2 text-center text-sm text-black transition-all duration-700 group-hover:rotate-90 group-hover:bg-black/50 group-hover:text-xl group-hover:text-white group-hover:[transform:skew(0deg)]"
                >
                  Plotting Cat
                </div>
              </div>
            </div>
            <div
              class="group flex flex-1 overflow-hidden transition-all duration-700 hover:grow-[10]"
            >
              <div class="relative h-96 flex-1">
                <img
                  class="h-full w-full object-cover transition-all duration-700 group-hover:grayscale-0"
                  src="https://upload.wikimedia.org/wikipedia/commons/d/d6/Cat_plotting_something_evil%21.jpg"
                />
                <div
                  class="absolute bottom-0 left-0 min-w-full origin-[0%_0%] -rotate-90 whitespace-nowrap bg-red-300 p-2 text-center text-sm text-black transition-all duration-700 group-hover:rotate-90 group-hover:bg-black/50 group-hover:text-xl group-hover:text-white group-hover:[transform:skew(0deg)]"
                >
                  Plotting Cat
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
      <div class="mx-auto mt-10 max-w-container">
        <h2 class="py-3 text-xl font-bold">Commission Categories :</h2>
        <div class="grid grid-cols-2 max-md:grid-cols-1">
          <div class="relative order-1 aspect-square h-auto w-full bg-red-500">
            <img src="../statics/bust_up.jpg" class="h-full w-full object-cover" />
          </div>
          <div
            class="order-2 flex aspect-square h-auto w-full items-center justify-center bg-gray-800 p-5"
          >
            <div class="m-auto text-gray-200">
              <span class="text-xl font-bold">Bust Up :</span>
              <div class="mt-2">
                <span class="rounded-md bg-green-300/50 px-2 py-1">$20 USD</span>
              </div>
              <div class="mt-1 text-lg font-semibold">Notes:</div>
              <ol class="list-decimal pl-5">
                <li>Additional fees $5-10 USD for complexity and details.</li>
                <li>Additional character fees $10 USD (Max 2 characters per artwork).</li>
              </ol>
            </div>
          </div>
          <div class="order-4 aspect-square w-full bg-white max-md:order-3">
            <img src="../statics/half_body.jpg" class="h-full w-full object-contain" />
          </div>
          <div
            class="order-3 flex aspect-square h-auto w-full items-center justify-center bg-gray-800 p-5 max-md:order-4"
          >
            <div class="m-auto text-gray-200">
              <span class="text-xl font-bold">Half-Body :</span>
              <div class="mt-2">
                <span class="rounded-md bg-yellow-300/50 px-2 py-1">$35 USD</span>
              </div>
              <div class="mt-1 text-lg font-semibold">Notes:</div>
              <ol class="list-decimal pl-5">
                <li>Could be a waist-up or knee-up.</li>
                <li>Additional fees $15-20 USD for complexity and details.</li>
                <li>Additional character fees $15 USD (Max 2 characters per artwork).</li>
              </ol>
            </div>
          </div>
          <div class="order-5 aspect-square w-full bg-white">
            <img src="../statics/full_body.jpg" class="h-full w-full object-contain" />
          </div>
          <div
            class="order-6 flex aspect-square h-auto w-full items-center justify-center bg-gray-800 p-5"
          >
            <div class="m-auto text-gray-200">
              <span class="text-xl font-bold">Full Body :</span>
              <div class="mt-2">
                <span class="rounded-md bg-red-300/50 px-2 py-1">$50 USD</span>
              </div>
              <div class="mt-1 text-lg font-semibold">Notes:</div>
              <ol class="list-decimal pl-5">
                <li>Additional fees $20-30 USD for complexity and details.</li>
                <li>Additional character fees $25 USD (Max 2 characters per artwork).</li>
              </ol>
            </div>
          </div>
        </div>
      </div>
      <div class="mx-auto mt-10 max-w-container">
        <div class="border border-red-500 py-5">
          <span class="text-xl font-bold">How to order :</span>
        </div>
        <div class="border border-green-500">
          <span>Terms of Service</span>
        </div>
      </div>
    </div>
  </div>
</template>
