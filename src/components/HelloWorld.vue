<template>
<div>
    <div class="bg-yellow-400 px-4 py-4">
      <div class="md:max-w-6xl md:mx-auto md:flex md:items-center md:justify-between">
        <div>
          <div class="hidden md:block flex space-x-4">
            <a href="#" class="inline-block py-1 md:py-4 text-black mr-6 font-bold">Products</a>
            <a href="#" class="inline-block py-1 md:py-4 text-black font-bold hover:text-emerald-400 mr-6">Resources</a>
            <a href="#" class="inline-block py-1 md:py-4 text-black font-bold hover:text-emerald-400">Inspiration</a>
             <a href="#" class="inline-block py-1 md:py-4 text-black font-bold hover:text-emerald-400">Pricing</a>
          </div>
        </div>

          <div class="flex justify-between items-center">
            <img src="../assets/download.png" class="inline-block py-2 transition transform hover:-translate-y-1" width="25" alt="download">
          <a href="#" class="inline-block py-2 text-black text-xl font-bold">mailchimp</a>
          <div class="inline-block cursor-pointer md:hidden">
            <div class="bg-gray-400 w-8 mb-2" style="height: 2px;"></div>
            <div class="bg-gray-400 w-8 mb-2" style="height: 2px;"></div>
            <div class="bg-gray-400 w-8" style="height: 2px;"></div>
          </div>
        </div>

        <div class="hidden md:block flex space-x-4">
          <button type="submit" class="px-4 focus:outline-none focus:shadow-outline inline-block py-2 md:py-4 text-gray-500 hover:text-gray-100 mr-6">
          <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="4" viewBox="0 0 24 24" class="w-6 h-5"><path d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"></path></svg>
        </button>
          <a href="#" class="inline-block py-2 px-4 text-black text-lg border-double border-4 border-black hover:bg-gray-100 rounded-lg">Login</a>
          <a href="#" class="inline-block py-2 px-4 text-black text-lg bg-indigo-600 hover:bg-gray-100 rounded-lg space-x-1.5 ">Sign Up Free</a>
        </div>
      </div>
    </div>

    <div class="bg-yellow-400 md:overflow-hidden">
      <div class="px-4 py-20 md:py-4">
        <div class="md:max-w-6xl md:mx-auto">
          <div class="md:flex md:flex-wrap">
            <div class="md:w-1/2 text-center md:text-left md:pt-16">
              <h1
                class="font-bold font-serif text-black text-5xl md:text-5xl leading-tight mb-4"
              >
                Marketing smarts for big ideas
              </h1>

              <p class="text-black font-serif md:text-xl md:pr-48">
                Mailchimp helps small businesses do big things,
                 with the right tools and guidance every step of the way.
              </p>

              <a
                href="#"
                class="mt-6 mb-12 md:mb-0 md:mt-10 text-lg inline-block py-3 px-8 text-black bg-indigo-600 hover:bg-indigo-800 rounded-lg shadow"
                >Pick A Plan</a
              >
            </div>
            <div class="md:w-1/2 relative">
              <div class="hidden md:block">
                <div
                  class="-ml-24 -mb-40 absolute left-0 bottom-0 w-40 bg-white rounded-lg shadow-lg px-6 py-8"
                  style="transform: rotate(-8deg);"
                >
                  <div
                    class="bg-indigo-800 mx-auto rounded-lg px-2 pb-2 relative mb-8"
                  >
                    <div class="mb-1">
                      <span
                        class="w-1 h-1 bg-indigo-100 rounded-full inline-block"
                        style="margin-right: 1px;"
                      ></span
                      ><span
                        class="w-1 h-1 bg-indigo-100 rounded-full inline-block"
                        style="margin-right: 1px;"
                      ></span
                      ><span
                        class="w-1 h-1 bg-indigo-100 rounded-full inline-block"
                      ></span>
                    </div>
                    <div class="h-1 w-12 bg-indigo-100 rounded mb-1"></div>
                    <div class="h-1 w-10 bg-indigo-100 rounded mb-2"></div>

                    <div class="flex">
                      <div class="w-6 h-3 rounded bg-indigo-100 mr-1"></div>
                      <div class="w-6 h-3 rounded bg-indigo-100"></div>
                    </div>

                    <div
                      class="-mr-2 -mb-4 absolute bottom-0 right-0 h-16 w-10 rounded-lg bg-green-700 border-2 border-white"
                    ></div>
                    <div
                      class="w-2 h-2 rounded-full bg-green-800 mx-auto absolute bottom-0 right-0 mr-2 -mb-2 z-10 border-2 border-white"
                    ></div>
                  </div>

                  <div class="text-gray-800 text-center">
                    Online <br />Services
                  </div>
                </div>

                <div
                  class="ml-24 mb-16 absolute left-0 bottom-0 w-40 bg-white rounded-lg shadow-lg px-6 py-8"
                  style="transform: rotate(-8deg); z-index: 2;"
                >
                  <div
                    class="bg-indigo-800 mx-auto rounded-lg relative mb-8 py-2 w-20 border-2 border-white"
                  >
                    <div
                      class="h-8 bg-green-700 w-8 rounded absolute left-0 top-0 -mt-3 ml-4"
                      style="transform: rotate(-45deg); z-index: -1;"
                    ></div>
                    <div
                      class="h-8 bg-green-800 w-8 rounded absolute left-0 top-0 -mt-3 ml-8"
                      style="transform: rotate(-12deg); z-index: -2;"
                    ></div>

                    <div
                      class="flex items-center justify-center h-6 bg-indigo-800 w-6 rounded-l-lg ml-auto border-4 border-white -mr-1"
                    >
                      <div
                        class="h-2 w-2 rounded-full bg-indigo-800 border-2 border-white"
                      ></div>
                    </div>

                    <div
                      class="w-8 h-8 bg-green-700 border-4 border-white rounded-full -ml-3 -mb-5"
                    ></div>
                  </div>

                  <div class="text-gray-800 text-center">
                    Banking Services
                  </div>
                </div>

                <div
                  class="ml-32 absolute left-0 bottom-0 w-48 bg-white rounded-lg shadow-lg px-10 py-8"
                  style="transform: rotate(-8deg); z-index: 2; margin-bottom: -220px;"
                >
                  <div
                    class="bg-indigo-800 mx-auto rounded-lg pt-4 mb-16 relative"
                  >
                    <div class="h-4 bg-white"></div>

                    <div class="text-right my-2 pb-1">
                      <div
                        class="inline-flex w-3 h-3 rounded-full bg-white -mr-2"
                      ></div>
                      <div
                        class="inline-flex w-3 h-3 rounded-full bg-indigo-800 border-2 border-white mr-2"
                      ></div>
                    </div>

                    <div
                      class="-ml-4 -mb-6 absolute left-0 bottom-0 w-16 bg-green-700 mx-auto rounded-lg pb-2 pt-3"
                    >
                      <div class="h-2 bg-white mb-2"></div>
                      <div class="h-2 bg-white w-6 ml-auto rounded mr-2"></div>
                    </div>
                  </div>

                  <div class="text-gray-800 text-center">
                    Payment for <br />Internet
                  </div>
                </div>

                <div
                  class="mt-10 w-full absolute right-0 top-0 flex rounded-lg bg-white overflow-hidden shadow-lg"
                  style="transform: rotate(-8deg); margin-right: -250px; z-index: 1;"
                >
                  <div class="w-32 bg-gray-200" style="height: 560px;"></div>
                  <div class="flex-1 p-6">
                    <h2 class="text-lg text-gray-700 font-bold mb-3">
                      Popular Payments
                    </h2>
                    <div class="flex mb-5">
                      <div class="w-16 rounded-full bg-gray-100 py-2 px-4 mr-2">
                        <div class="p-1 rounded-full bg-gray-300"></div>
                      </div>
                      <div class="w-16 rounded-full bg-gray-100 py-2 px-4 mr-2">
                        <div class="p-1 rounded-full bg-gray-300"></div>
                      </div>
                      <div class="w-16 rounded-full bg-gray-100 py-2 px-4 mr-2">
                        <div class="p-1 rounded-full bg-gray-300"></div>
                      </div>
                      <div class="w-16 rounded-full bg-gray-100 py-2 px-4">
                        <div class="p-1 rounded-full bg-gray-300"></div>
                      </div>
                    </div>

                    <div class="flex flex-wrap -mx-4 mb-5">
                      <div class="w-1/3 px-4">
                        <div class="h-40 rounded-lg bg-white shadow-lg p-6">
                          <div
                            class="w-16 h-16 rounded-full bg-gray-200 mb-6"
                          ></div>
                          <div
                            class="h-2 w-16 bg-gray-200 mb-2 rounded-full"
                          ></div>
                          <div class="h-2 w-10 bg-gray-200 rounded-full"></div>
                        </div>
                      </div>
                      <div class="w-1/3 px-4">
                        <div class="h-40 rounded-lg bg-white shadow-lg p-6">
                          <div
                            class="w-16 h-16 rounded-full bg-gray-200 mb-6"
                          ></div>
                          <div
                            class="h-2 w-16 bg-gray-200 mb-2 rounded-full"
                          ></div>
                          <div class="h-2 w-10 bg-gray-200 rounded-full"></div>
                        </div>
                      </div>
                      <div class="w-1/3 px-4">
                        <div class="h-40 rounded-lg bg-white shadow-lg p-6">
                          <div
                            class="w-16 h-16 rounded-full bg-gray-200 mb-6"
                          ></div>
                          <div
                            class="h-2 w-16 bg-gray-200 mb-2 rounded-full"
                          ></div>
                          <div class="h-2 w-10 bg-gray-200 rounded-full"></div>
                        </div>
                      </div>
                    </div>

                    <h2 class="text-lg text-gray-700 font-bold mb-3">
                      Popular Payments
                    </h2>

                    <div
                      class="w-full flex flex-wrap justify-between items-center border-b-2 border-gray-100 py-3"
                    >
                      <div class="w-1/3">
                        <div class="flex">
                          <div class="h-8 w-8 rounded bg-gray-200 mr-4"></div>
                          <div>
                            <div
                              class="h-2 w-16 bg-gray-200 mb-1 rounded-full"
                            ></div>
                            <div
                              class="h-2 w-10 bg-gray-100 rounded-full"
                            ></div>
                          </div>
                        </div>
                      </div>
                      <div class="w-1/3">
                        <div
                          class="w-16 rounded-full bg-green-100 py-2 px-4 mx-auto"
                        >
                          <div class="p-1 rounded-full bg-green-200"></div>
                        </div>
                      </div>
                      <div class="w-1/3">
                        <div
                          class="h-2 w-10 bg-gray-100 rounded-full mx-auto"
                        ></div>
                      </div>
                    </div>

                    <div
                      class="flex flex-wrap justify-between items-center border-b-2 border-gray-100 py-3"
                    >
                      <div class="w-1/3">
                        <div class="flex">
                          <div class="h-8 w-8 rounded bg-gray-200 mr-4"></div>
                          <div>
                            <div
                              class="h-2 w-16 bg-gray-200 mb-1 rounded-full"
                            ></div>
                            <div
                              class="h-2 w-10 bg-gray-100 rounded-full"
                            ></div>
                          </div>
                        </div>
                      </div>
                      <div class="w-1/3">
                        <div
                          class="w-16 rounded-full bg-orange-100 py-2 px-4 mx-auto"
                        >
                          <div class="p-1 rounded-full bg-orange-200"></div>
                        </div>
                      </div>
                      <div class="w-1/3">
                        <div
                          class="h-2 w-16 bg-gray-100 rounded-full mx-auto"
                        ></div>
                      </div>
                    </div>

                    <div
                      class="flex flex-wrap justify-between items-center border-b-2 border-gray-100 py-3"
                    >
                      <div class="w-1/3">
                        <div class="flex">
                          <div class="h-8 w-8 rounded bg-gray-200 mr-4"></div>
                          <div>
                            <div
                              class="h-2 w-16 bg-gray-200 mb-1 rounded-full"
                            ></div>
                            <div
                              class="h-2 w-10 bg-gray-100 rounded-full"
                            ></div>
                          </div>
                        </div>
                      </div>
                      <div class="w-1/3">
                        <div
                          class="w-16 rounded-full bg-blue-100 py-2 px-4 mx-auto"
                        >
                          <div class="p-1 rounded-full bg-blue-200"></div>
                        </div>
                      </div>
                      <div class="w-1/3">
                        <div
                          class="h-2 w-8 bg-gray-100 rounded-full mx-auto"
                        ></div>
                      </div>
                    </div>
                  </div>
                </div>

                <div
                  class="w-full absolute left-0 bottom-0 ml-1"
                  style="transform: rotate(-8deg); z-index: 1; margin-bottom: -360px;"
                >
                  <div class="grid--gray h-48 w-48"></div>
                </div>
              </div>

              <div
                class="md:hidden w-full absolute right-0 top-0 flex rounded-lg bg-white overflow-hidden shadow"
              >
                <div
                  class="h-4 bg-gray-200 absolute top-0 left-0 right-0 rounded-t-lg flex items-center"
                >
                  <span
                    class="h-2 w-2 rounded-full bg-red-500 inline-block mr-1 ml-2"
                  ></span>
                  <span
                    class="h-2 w-2 rounded-full bg-orange-400 inline-block mr-1"
                  ></span>
                  <span
                    class="h-2 w-2 rounded-full bg-green-500 inline-block mr-1"
                  ></span>
                </div>
                <div class="w-32 bg-gray-100 px-2 py-8" style="height: 340px;">
                  <div class="h-2 w-16 bg-gray-300 rounded-full mb-4"></div>
                  <div class="flex items-center mb-4">
                    <div
                      class="h-5 w-5 rounded-full bg-gray-300 mr-3 flex-shrink-0"
                    ></div>
                    <div>
                      <div class="h-2 w-10 bg-gray-300 rounded-full"></div>
                    </div>
                  </div>

                  <div class="h-2 w-16 bg-gray-200 rounded-full mb-2"></div>
                  <div class="h-2 w-10 bg-gray-200 rounded-full mb-2"></div>
                  <div class="h-2 w-20 bg-gray-200 rounded-full mb-2"></div>
                  <div class="h-2 w-6 bg-gray-200 rounded-full mb-2"></div>
                  <div class="h-2 w-16 bg-gray-200 rounded-full mb-2"></div>
                  <div class="h-2 w-10 bg-gray-200 rounded-full mb-2"></div>
                  <div class="h-2 w-20 bg-gray-200 rounded-full mb-2"></div>
                  <div class="h-2 w-6 bg-gray-200 rounded-full mb-2"></div>
                </div>
                <div class="flex-1 px-4 py-8">
                  <h2 class="text-xs text-gray-700 font-bold mb-1">
                    Popular Payments
                  </h2>
                  <div class="flex mb-5">
                    <div class="p-2 w-12 rounded-full bg-gray-100 mr-2"></div>
                    <div class="p-2 w-12 rounded-full bg-gray-100 mr-2"></div>
                    <div class="p-2 w-12 rounded-full bg-gray-100 mr-2"></div>
                    <div class="p-2 w-12 rounded-full bg-gray-100 mr-2"></div>
                  </div>

                  <div class="flex flex-wrap -mx-2 mb-5">
                    <div class="w-1/3 px-2">
                      <div class="p-3 rounded-lg bg-white shadow">
                        <div
                          class="w-6 h-6 rounded-full bg-gray-200 mb-2"
                        ></div>
                        <div
                          class="h-2 w-10 bg-gray-200 mb-1 rounded-full"
                        ></div>
                        <div class="h-2 w-6 bg-gray-200 rounded-full"></div>
                      </div>
                    </div>
                    <div class="w-1/3 px-2">
                      <div class="p-3 rounded-lg bg-white shadow">
                        <div
                          class="w-6 h-6 rounded-full bg-gray-200 mb-2"
                        ></div>
                        <div
                          class="h-2 w-10 bg-gray-200 mb-1 rounded-full"
                        ></div>
                        <div class="h-2 w-6 bg-gray-200 rounded-full"></div>
                      </div>
                    </div>
                    <div class="w-1/3 px-2">
                      <div class="p-3 rounded-lg bg-white shadow">
                        <div
                          class="w-6 h-6 rounded-full bg-gray-200 mb-2"
                        ></div>
                        <div
                          class="h-2 w-10 bg-gray-200 mb-1 rounded-full"
                        ></div>
                        <div class="h-2 w-6 bg-gray-200 rounded-full"></div>
                      </div>
                    </div>
                  </div>

                  <h2 class="text-xs text-gray-700 font-bold mb-1">
                    Popular Payments
                  </h2>

                  <div
                    class="w-full flex flex-wrap justify-between items-center border-b-2 border-gray-100 py-3"
                  >
                    <div class="w-1/3">
                      <div class="flex">
                        <div
                          class="h-5 w-5 rounded-full bg-gray-200 mr-3 flex-shrink-0"
                        ></div>
                        <div>
                          <div
                            class="h-2 w-16 bg-gray-200 mb-1 rounded-full"
                          ></div>
                          <div class="h-2 w-10 bg-gray-100 rounded-full"></div>
                        </div>
                      </div>
                    </div>
                    <div class="w-1/3">
                      <div
                        class="w-16 rounded-full bg-green-100 py-2 px-4 mx-auto"
                      >
                        <div class="p-1 rounded-full bg-green-200"></div>
                      </div>
                    </div>
                    <div class="w-1/3">
                      <div
                        class="h-2 w-10 bg-gray-100 rounded-full mx-auto"
                      ></div>
                    </div>
                  </div>

                  <div class="flex flex-wrap justify-between items-center py-3">
                    <div class="w-1/3">
                      <div class="flex">
                        <div
                          class="h-5 w-5 rounded-full bg-gray-200 mr-3 flex-shrink-0"
                        ></div>
                        <div>
                          <div
                            class="h-2 w-16 bg-gray-200 mb-1 rounded-full"
                          ></div>
                          <div class="h-2 w-10 bg-gray-100 rounded-full"></div>
                        </div>
                      </div>
                    </div>
                    <div class="w-1/3">
                      <div
                        class="w-16 rounded-full bg-orange-100 py-2 px-4 mx-auto"
                      >
                        <div class="p-1 rounded-full bg-orange-200"></div>
                      </div>
                    </div>
                    <div class="w-1/3">
                      <div
                        class="h-2 w-16 bg-gray-100 rounded-full mx-auto"
                      ></div>
                    </div>
                  </div>
                </div>
              </div>

              <div
                class="mr-3 md:hidden absolute right-0 bottom-0 w-40 bg-white rounded-lg shadow-lg px-10 py-6"
                style="z-index: 2; margin-bottom: -380px;"
              >
                <div
                  class="bg-indigo-800 mx-auto rounded-lg w-20 pt-3 mb-12 relative"
                >
                  <div class="h-3 bg-white"></div>

                  <div class="text-right my-2">
                    <div
                      class="inline-flex w-3 h-3 rounded-full bg-white -mr-2"
                    ></div>
                    <div
                      class="inline-flex w-3 h-3 rounded-full bg-indigo-800 border-2 border-white mr-2"
                    ></div>
                  </div>

                  <div class="-ml-4 -mb-6 absolute left-0 bottom-0 w-16 bg-green-700 mx-auto rounded-lg pb-2 pt-3">
                    <div class="h-2 bg-white mb-2"></div>
                    <div class="h-2 bg-white w-6 ml-auto rounded mr-2"></div>
                  </div>
                </div>

                <div class="text-gray-800 text-center text-sm">
                  Payment for <br />Internet
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <svg
        class="fill-current text-white hidden md:block"
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 1440 320"
      >
        <path fill-opacity="1" d="M0,224L1440,32L1440,320L0,320Z"></path>
      </svg>
    </div>

      <div class="mb-10 mt-20">
     <h1 class="font-bold uppercase font-serif text-5xl mb-5">Do it all with Mailchimp</h1>
      <p class="text-sm text-lg font-serif">Bring your audience data, marketing channels, and insights together so you can reach <br> your goals faster—all from a single platform.</p>
      </div>

<div class="min-w-screen min-h-screen bg-white flex items-center p-5 lg:p-10 overflow-hidden relative">
    <div class="w-full max-w-6xl rounded bg-gray-500 shadow-xl p-10 lg:p-20 mx-auto text-white relative md:text-left">
        <div class="md:flex items-center -mx-10">
            <div class="w-full md:w-1/2 px-10">
                <div class="mb-10">
                    <h1 class="font-bold font-serif uppercase text-2xl mb-5">Get your business online</h1>
                    <p class="text-sm font-serif text-lg">Give your brand a home with a custom domain. Then create a website with built-in marketing tools to help you launch it.</p>
                </div>
                <div>
                    <div class="inline-block align-bottom">
                        <button class="bg-yellow-300 opacity-75 hover:opacity-100 text-yellow-900 hover:text-gray-900 rounded-full px-10 py-2 font-semibold">Websites and domains</button>
                    </div>
                </div>
            </div>
             <div class="w-full md:w-1/2 px-10 mb-10 md:mb-0">
                <div class="relative">
                    <img src="../assets/MC.png" class="w-full relative z-10" alt="Mc">
                    <div class="border-4 border-yellow-200 absolute top-10 bottom-10 left-10 right-10 z-0"></div>
                </div>
            </div>
        </div>
    </div>
</div>

<div class="min-w-screen min-h-screen bg-white flex items-center p-5 lg:p-10 overflow-hidden relative">
    <div class="w-full max-w-6xl rounded bg-gray-500 shadow-xl p-10 lg:p-20 mx-auto text-white relative md:text-left">
        <div class="md:flex items-center -mx-10">
            <div class="w-full md:w-1/2 px-10">
                <div class="mb-10">
                    <h1 class="font-bold font-serif uppercase text-2xl mb-5">Market your business</h1>
                    <p class="text-sm font-serif text-lg">Send the right messages on all the right channels. Build emails, social ads, landing pages, postcards, and more from one place..</p>
                </div>
                <div>
                    <div class="inline-block align-bottom">
                        <button class="bg-yellow-300 opacity-75 hover:opacity-100 text-yellow-900 hover:text-gray-900 rounded-full px-10 py-2 font-semibold">Marketing campaigns</button>
                    </div>
                </div>
            </div>
             <div class="w-full md:w-1/2 px-10 mb-10 md:mb-0">
                <div class="relative">
                    <img src="../assets/MC2.png" class="w-full relative z-10" alt="MC2">
                    <div class="border-4 border-yellow-200 absolute top-10 bottom-10 left-10 right-10 z-0"></div>
                </div>
            </div>
        </div>
    </div>
</div>


<div class="min-w-screen min-h-screen bg-white flex items-center p-5 lg:p-10 overflow-hidden relative">
    <div class="w-full max-w-6xl rounded bg-white shadow-xl p-10 lg:p-20 mx-auto text-gray-800 relative md:text-left">
        <div class="md:flex items-center -mx-10">
            <div class="w-full md:w-1/2 px-10 mb-10 md:mb-0">
                <div class="relative">
                    <img src="https://pngimg.com/uploads/raincoat/raincoat_PNG53.png" class="w-full relative z-10" alt="">
                    <div class="border-4 border-yellow-200 absolute top-10 bottom-10 left-10 right-10 z-0"></div>
                </div>
            </div>


            <div class="w-full md:w-1/2 px-10">
                <div class="mb-10">
                    <h1 class="font-bold font-serif uppercase text-2xl mb-5">Create better content</h1>
                    <p class="text-sm font-serif">Let your brand shine through with easy-to-use design tools and flexible templates. Our AI-powered Creative Assistant will even generate custom designs for you in seconds..</p>
                </div>
                <div>

                    <div class="inline-block align-bottom ">
                        <button class="bg-yellow-300 opacity-75 hover:opacity-100 font-serif text-yellow-900 hover:text-gray-900 rounded-full px-10 py-2 font-semibold">Explore content studio</button>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

<div class="min-w-screen min-h-screen bg-white flex items-center p-5 lg:p-10 overflow-hidden relative">
    <div class="w-full max-w-6xl rounded bg-white shadow-xl p-10 lg:p-20 mx-auto text-gray-800 relative md:text-left">
        <div class="md:flex items-center -mx-10">
            <div class="w-full md:w-1/2 px-10 mb-10 md:mb-0">
                <div class="relative">
                    <img src="https://pngimg.com/uploads/raincoat/raincoat_PNG53.png" class="w-full relative z-10" alt="">
                    <div class="border-4 border-yellow-200 absolute top-10 bottom-10 left-10 right-10 z-0"></div>
                </div>
            </div>
            <div class="w-full md:w-1/2 px-10">
                <div class="mb-10">
                    <h1 class="font-bold font-serif uppercase text-2xl mb-5">Automate your marketing</h1>
                    <p class="text-sm font-serif">Add a personal touch without the personal effort through automated messages that reach your customers at exactly the right moments.</p>
                </div>
                <div>

                    <div class="inline-block align-bottom">
                        <button class="bg-yellow-300 font-serif opacity-75 hover:opacity-100 text-yellow-900 hover:text-gray-900 rounded-full px-10 py-2 font-semibold">Learn about automations</button>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

<div class="min-w-screen min-h-screen bg-white flex items-center p-5 lg:p-10 overflow-hidden relative">
    <div class="w-full max-w-6xl rounded bg-white shadow-xl p-10 lg:p-20 mx-auto text-gray-800 relative md:text-left">
        <div class="md:flex items-center -mx-10">
            <div class="w-full md:w-1/2 px-10 mb-10 md:mb-0">
                <div class="relative">
                    <img src="https://pngimg.com/uploads/raincoat/raincoat_PNG53.png" class="w-full relative z-10" alt="">
                    <div class="border-4 border-yellow-200 absolute top-10 bottom-10 left-10 right-10 z-0"></div>
                </div>
            </div>
            <div class="w-full md:w-1/2 px-10">
                <div class="mb-10">
                    <h1 class="font-bold font-serif uppercase text-2xl mb-5">Take action with our insights</h1>
                    <p class="text-sm font-serif">With all your data and insights in one place, you can see what’s working best and get recommendations to help you do more of it.</p>
                </div>
                <div>

                    <div class="inline-block align-bottom">
                        <button class="bg-yellow-300 font-serif opacity-75 hover:opacity-100 text-yellow-900 hover:text-gray-900 rounded-full px-10 py-2 font-semibold">Insights & analytics tools</button>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

<div class="min-w-screen min-h-screen bg-white flex items-center p-5 lg:p-10 overflow-hidden relative">
    <div class="w-full max-w-6xl rounded bg-white shadow-xl p-10 lg:p-20 mx-auto text-gray-800 relative md:text-left">
        <div class="md:flex items-center -mx-10">
            <div class="w-full md:w-1/2 px-10 mb-10 md:mb-0">
                <div class="relative">
                    <img src="https://pngimg.com/uploads/raincoat/raincoat_PNG53.png" class="w-full relative z-10" alt="">
                    <div class="border-4 border-yellow-200 absolute top-10 bottom-10 left-10 right-10 z-0"></div>
                </div>
            </div>
            <div class="w-full md:w-1/2 px-10">
                <div class="mb-10">
                    <h1 class="font-bold font-serif uppercase text-2xl mb-5">Reach the right people</h1>
                    <p class="text-sm font-serif">Put your people at the heart of your marketing with tools that help you get to know your audience and see who you should be talking to.</p>
                </div>
                <div>

                    <div class="inline-block align-bottom">
                        <button class="bg-yellow-300 font-serif opacity-75 hover:opacity-100 text-yellow-900 hover:text-gray-900 rounded-full px-10 py-2 font-semibold">Audience management tools</button>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

  <div class="mb-10 mt-20">
      <h1 class="font-bold uppercase text-black font-serif text-5xl mb-5">Grow with Mailchimp</h1>
        <p class="text-sm text-lg font-serif">Our marketing platform helps brands like these build their thing and keep it growing.</p>
        </div>

  <div class="p-10 grid grid-cols-1 sm:grid-cols-1 md:grid-cols-3 lg:grid-cols-3 xl:grid-cols-3 gap-5 object-center">
    <!--Card 1-->
    <div class="rounded overflow-hidden shadow-lg">
      <img class="w-64" src="../assets/new.png" width="15" alt="new">
      <div class="px-6 py-4">
        <p class="text-gray-700 text-base">Customers since 2011</p>
      </div>
    </div>
    <!--Card 2-->
    <div class="rounded overflow-hidden shadow-lg">
      <img class="w-64" src="../assets/Vimeo_bw.png" width="15" alt="Vimeo_bw">
      <div class="px-6 py-4">
        <p class="text-gray-800 text-base">Customers since 2012</p>
      </div>
    </div>

    <!--Card 3-->
    <div class="rounded overflow-hidden shadow-lg">
      <img class="w-64" src="../assets/ted.png" width="15" alt="ted">
      <div class="px-6 py-4">
        <p class="text-gray-700 text-base">Customers since 2010</p>
      </div>
    </div>
  </div>
</div>


  <div class="mb-10 mt-20">
      <h1 class="font-bold uppercase text-black font-serif text-5xl mb-5">Keep pushing  <br>forward. We've got <br> your back.</h1>
        </div>
     <div class="p-10 grid grid-cols-1 sm:grid-cols-1 md:grid-cols-3 lg:grid-cols-3 xl:grid-cols-3 gap-5">
    <!--Card 1-->
    <div class="rounded overflow-hidden shadow-lg">
      <img class="w-64" src="../assets/LLO.png" alt="LLO">
      <div class="px-6 py-4">
        <div class="font-bold text-xl mb-2 text-black">Award-winning support</div>
        <p class="text-gray-700 text-base font-serif">
          Get the help you need, whenever<br> you need it with our 24/7 support.
          Learn More
        </p>
        <br><br>
        <a href="#" class="text-gray-700 text-base text-indigo-600 font-serif"> Learn More</a>

      </div>
    </div>
    <!--Card 2-->
    <div class="rounded overflow-hidden shadow-lg">
      <img class="w-64" src="../assets/LLO_Spot.png" alt="LLO_Spot">
      <div class="px-6 py-4">
        <div class="font-bold text-xl mb-2 text-black">250+ app integrations</div>
        <p class="text-gray-700 text-base font-serif">
          You can connect all your tools to <br>Mailchimp and unlock even more features.
        </p>
        <br><br>
     <a href="#" class="text-gray-700 text-base text-indigo-600 font-serif"> Learn More</a>

      </div>
    </div>

    <!--Card 3-->
    <div class="rounded overflow-hidden shadow-lg">
      <img class="w-64" src="../assets/LLO_Mini.png" alt="LLO_Mini">
      <div class="px-6 py-4">
        <div class="font-bold text-xl mb-2 text-black">A directory of trusted pros</div>
        <p class="text-gray-700 text-base font-serif">
          Take your marketing to the next level<br> when you work with a Mailchimp partner.
        </p>
        <br><br>
        <a href="#" class="text-gray-700 text-base text-indigo-600 font-serif"> Browse partners</a>
      </div>
    </div>
  </div>

<div class="bg-yellow-200">
 <div class="mb-10 mt-20">
  <h1 class="font-bold uppercase text-black font-serif text-5xl mb-5 pt-20">See how it all comes<br> together</h1></div>

<div class="min-w-screen min-h-screen bg-yellow-200 flex items-center p-5 lg:p-10 overflow-hidden relative">
    <div class="w-full max-w-6xl rounded bg-yellow-200 shadow-xl p-10 lg:p-20 mx-auto text-gray-800 relative md:text-left">
        <div class="md:flex items-center -mx-10">
            <div class="w-full md:w-1/2 px-10 mb-10 md:mb-0">
                <div class="relative">
                    <img src="../assets/Woo.png" class="w-full relative z-10" alt="woo">
                    <div class="border-4 border-yellow-200 absolute top-10 bottom-10 left-10 right-10 z-0"></div>
                </div>
            </div>
            <div class="w-full md:w-1/2 px-10">
                <div class="mb-10">
                    <h1 class="font-bold font-serif uppercase text-2xl mb-5">Connect your store to give <br> emails a sales boost</h1>
                    <p class="text-sm font-serif">Do more with your marketing using the power of analytics. Sync your store data and get pre-built customer segments based<br> on purchase behavior to improve your sales.</p>
                </div>
            </div>
        </div>
    </div>
</div>

<div class="min-w-screen min-h-screen bg-yellow-200 flex items-center p-5 lg:p-10 overflow-hidden relative">
    <div class="w-full max-w-6xl rounded bg-yellow-200 shadow-xl p-10 lg:p-20 mx-auto text-black relative md:text-left">
        <div class="md:flex items-center -mx-10">
            <div class="w-full md:w-1/2 px-10">
                <div class="mb-10">
                    <h1 class="font-bold font-serif uppercase text-2xl mb-5">Pave the way to purchase</h1>
                    <p class="text-sm font-serif text-lg">Put your customers on personalized journeys that lead them to checkout.</p>
                </div>
            </div>
             <div class="w-full md:w-1/2 px-10 mb-10 md:mb-0">
                <div class="relative">
                    <img src="../assets/Purchase.png" class="w-full relative z-10" alt="Purchase">
                    <div class="border-4 border-yellow-200 absolute top-10 bottom-10 left-10 right-10 z-0"></div>
                </div>
            </div>
        </div>
    </div>
</div>


<div class="min-w-screen min-h-screen bg-yellow-200 flex items-center p-5 lg:p-10 overflow-hidden relative">
    <div class="w-full max-w-6xl rounded bg-yellow-200 shadow-xl p-10 lg:p-20 mx-auto text-gray-800 relative md:text-left">
        <div class="md:flex items-center -mx-10">
            <div class="w-full md:w-1/2 px-10 mb-10 md:mb-0">
                <div class="relative">
                    <img src="../assets/Results.png" class="w-full relative z-10" alt="Results">
                    <div class="border-4 border-yellow-200 absolute top-10 bottom-10 left-10 right-10 z-0"></div>
                </div>
            </div>
            <div class="w-full md:w-1/2 px-10">
                <div class="mb-10">
                    <h1 class="font-bold font-serif uppercase text-2xl mb-5">Sit back and watch the results roll in</h1>
                    <p class="text-sm font-serif">Track sales from first click to purchase. See who paid for what and how much money your campaign has earned.</p>
                </div>
            </div>
        </div>
    </div>
</div>
<div class="mb-10 mt-20 bg-yellow-200">
      <h1 class="font-bold uppercase text-black font-serif text-5xl mb-5">Up to 6x more orders with<br>automation</h1>
      <p>Make your marketing work harder so you can focus on running your business. Our<br> data shows automations can generate up to 6 times more orders than bulk email<br> alone. See All Smarts</p>

      <div>

        <div class="inline-block align-bottom pt-10">
              <button class="bg-indigo-600 font-serif opacity-75 hover:opacity-100 text-white hover:text-white rounded-full px-10 py-2 font-semibold">See All Smarts</button>
        </div>
      </div>
</div>
<img class="mx-auto" src="../assets/LLO_Hero.png" alt="LLO_Hero">
</div>



<div class="py-16">
  <div class="container m-auto px-6">
    <img src="../assets/why_mailchimp.png" alt="why_mailchimp">
   <div class="lg:flex justify-between items-center">
       <div class="lg:w-6/12 lg:p-0 p-7">
          <h1 class="font-serif text-m leading-tight mb-5 capitalize">&#x22;Since using Mailchimp, I feel so much more<br> confident in managing all our marketing<br> Like I got this&#x22;.</h1>
          <p class="font-serif text-m">– Marissa Axell, co-founder of 17th Street Athletic Club</p>

          <div class="py-5">
               <h1 class="text-black inline-block text-3xl font-bold">37%</h1>
               <p> lift on online bookings</p>
               <h1 class="text-black inline-block text-3xl font-bold">250%</h1>
               <p> increase in email signups</p>
          </div>

        </div>
        <div class="lg:w-5/12 order-2">
          <img src="../assets/wis.jpg"
          style="transform: scale(1) perspective(1040px) rotateY(-11deg) rotateX(2deg) rotate(2deg);" alt="" class="rounded">
        </div>
    </div>

  </div>
</div>

<div class="mb-10 mt-20 bg-gray-200">
      <h1 class="font-bold uppercase text-black font-serif text-5xl mb-5 pt-20">Mailchimp was <br>recently named one<br> of the Best Software <br>Companies of 2020 by G2.</h1>
      <div>
        <div class="inline-block align-bottom pt-10 bg-gray-200">
              <button class="border border-indigo-600 font-serif opacity-75 hover:opacity-100 text-indigo-500 hover:text-indigo-700 rounded-full px-10 py-2 font-semibold">See how we Setup</button>
        </div>
      </div>
      <div class="">
<img class="mx-auto pt-20" src="../assets/Hero.png" alt="Hero">
</div>
</div>

 <div class="mb-10 mt-20">
     <h1 class="font-bold uppercase font-serif text-5xl mb-5">Resources to give you the <br> inside track</h1>
      <p class="text-sm text-lg font-serif">Looking to get ahead? We have expert guidance, timely resources, and inspiring stories from <br>entrepreneurs who’ve been in your shoes. Business-growing shoes.</p>
      </div>

     <div class="container mx-auto">
    <div class="grid grid-cols-1 md:grid-cols-2 h-screen">
      <div class="max-h-96 md:h-screen">
        <img class="w-screen h-45 object-cover object-top" src="../assets/All.jpg" alt="All">

        <div class="border-solid border-4 border-black-500">
        <img src="../assets/download.png" class="inline-block py-2 transition transform hover:-translate-y-1" width="40" alt="download">
          <a href="#" class="inline-block py-2 text-black text-xl font-bold">mailchimp presents</a>

        <h3 class="pt-10 font-serif">SERIES</h3>
        <h1 class="pt-6 text-3xl font-serif">All in a Day’s Work</h1>
        <p class="pt-5 mb-6 font-serif">Created with It’s Nice That, our new animated<br> series reveals the ups, downs, and realities of life as an entrepreneur.</p>
        </div>
        </div>
      <div class="flex bg-pink-200 p-10">
        <div class="mb-0 mt-40 max-w-lg">
          <h1 class="text-3xl uppercase font-serif">Mailchimp Report</h1>
          <p class="font-bold text-3xl mb-5 font-serif">How Small Businesses are Finding New Ways to Grow</p>
          <p>You need data-based insights, actionable takeaways, and loads of inspiration to adapt. As it turns out, our new report has all that and more.</p>
          <button class="bg-indigo-600 font-serif rounded-md py-3 px-7 mt-6 text-white">Read the Report</button>
        </div>
      </div>
    </div>
  </div>
  <div class="pt-40">
  <div class="mb-10 mt-20 bg-yellow-400 h-screen">
      <h1 class="font-bold uppercase text-black font-serif text-5xl mb-5 pt-60">Let’s do this</h1>
      <p class="pt-5 font-serif text-2xl">Every big idea starts with a small step forward.</p>
      <div>
        <div class="inline-block align-bottom pt-10 bg-yellow-400 mb-20">
              <button class="bg-indigo-600 font-serif opacity-75 hover:opacity-100 text-white hover:text-white rounded-full px-10 py-2 font-semibold">See how we Setup</button>
        </div>
      </div>
  </div>
      <!-- component -->
<div class="bg-gray-100 pt-40">
   <div class="max-w-6xl m-auto text-gray-800 flex flex-wrap justify-center">
      <div class="p-5 w-48 ">
         <div class="text-m uppercase text-black font-bold">Home</div>
         <a class="my-3 block" href="/#">Services <span class="text-teal-600 text-xs p-1"></span></a><a class="my-3 block" href="/#">Products <span class="text-teal-600 text-xs p-1"></span></a><a class="my-3 block" href="/#">About Us <span class="text-teal-600 text-xs p-1"></span></a><a class="my-3 block" href="/#">Pricing <span class="text-teal-600 text-xs p-1"></span></a><a class="my-3 block" href="/#">Partners <span class="text-teal-600 text-xs p-1">New</span></a>
      </div>
      <div class="p-5 w-48 ">
         <div class="text-m uppercase text-black font-bold">User</div>
         <a class="my-3 block" href="/#">Sign in <span class="text-teal-600 text-xs p-1"></span></a><a class="my-3 block" href="/#">New Account <span class="text-teal-600 text-xs p-1"></span></a><a class="my-3 block" href="/#">Demo <span class="text-teal-600 text-xs p-1">New</span></a><a class="my-3 block" href="/#">Career <span class="text-teal-600 text-xs p-1">We're hiring</span></a><a class="my-3 block" href="/#">Surveys <span class="text-teal-600 text-xs p-1">New</span></a>
      </div>
      <div class="p-5 w-48 ">
         <div class="text-m uppercase text-black font-bold">Resources</div>
         <a class="my-3 block" href="/#">Documentation <span class="text-teal-600 text-xs p-1"></span></a><a class="my-3 block" href="/#">Tutorials <span class="text-teal-600 text-xs p-1"></span></a><a class="my-3 block" href="/#">Support <span class="text-teal-600 text-xs p-1">New</span></a>
      </div>
      <div class="p-5 w-48 ">
         <div class="text-m uppercase text-black font-bold">Product</div>
         <a class="my-3 block" href="/#">Our Products <span class="text-teal-600 text-xs p-1"></span></a><a class="my-3 block" href="/#">Great Deals <span class="text-teal-600 text-xs p-1">New</span></a><a class="my-3 block" href="/#">Analytics <span class="text-teal-600 text-xs p-1"></span></a><a class="my-3 block" href="/#">Mobile <span class="text-teal-600 text-xs p-1"></span></a>
      </div>
      <div class="p-5 w-48 ">
         <div class="text-m uppercase text-black font-bold">Support</div>
         <a class="my-3 block" href="/#">Help Center <span class="text-teal-600 text-xs p-1"></span></a><a class="my-3 block" href="/#">Privacy Policy <span class="text-teal-600 text-xs p-1"></span></a><a class="my-3 block" href="/#">Conditions <span class="text-teal-600 text-xs p-1"></span></a>
      </div>
      <div class="p-5 w-48 ">
          <img src="../assets/download.png" class="inline-block py-2 transition transform hover:-translate-y-1" width="30" alt="download">
          <a href="#" class="inline-block py-2 text-black font-bold">mailchimp presents</a>
        <p class="mb-6 font-serif">Films, podcasts and original series that celebrate the entrepreneurial spirit.</p>
   </div>
</div>

<div class="bg-gray-100 pt-2 ">
   <div class="flex pb-5 px-3 m-auto pt-5 border-t text-gray-800 text-sm flex-col
      md:flex-row max-w-6xl">
      <div class="mt-2">Lloyd | Copyright © 2021 | All Rights Reserved.</div>
      <div class="md:flex-auto md:flex-row-reverse mt-2 flex-row flex">
         <a href="/#" class="w-6 mx-1">
            <svg class="fill-current cursor-pointer text-gray-500 hover:text-gray-400" width="100%" height="100%" viewBox="0 0 24 24" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xml:space="preserve" xmlns:serif="http://www.serif.com/" style="fill-rule: evenodd; clip-rule: evenodd; stroke-linejoin: round; stroke-miterlimit: 2;">
               <path id="Twitter" d="M24,12c0,6.627 -5.373,12 -12,12c-6.627,0 -12,-5.373 -12,-12c0,-6.627
                  5.373,-12 12,-12c6.627,0 12,5.373 12,12Zm-6.465,-3.192c-0.379,0.168
                  -0.786,0.281 -1.213,0.333c0.436,-0.262 0.771,-0.676
                  0.929,-1.169c-0.408,0.242 -0.86,0.418 -1.341,0.513c-0.385,-0.411
                  -0.934,-0.667 -1.541,-0.667c-1.167,0 -2.112,0.945 -2.112,2.111c0,0.166
                  0.018,0.327 0.054,0.482c-1.754,-0.088 -3.31,-0.929
                  -4.352,-2.206c-0.181,0.311 -0.286,0.674 -0.286,1.061c0,0.733 0.373,1.379
                  0.94,1.757c-0.346,-0.01 -0.672,-0.106 -0.956,-0.264c-0.001,0.009
                  -0.001,0.018 -0.001,0.027c0,1.023 0.728,1.877 1.694,2.07c-0.177,0.049
                  -0.364,0.075 -0.556,0.075c-0.137,0 -0.269,-0.014 -0.397,-0.038c0.268,0.838
                  1.048,1.449 1.972,1.466c-0.723,0.566 -1.633,0.904 -2.622,0.904c-0.171,0
                  -0.339,-0.01 -0.504,-0.03c0.934,0.599 2.044,0.949 3.237,0.949c3.883,0
                  6.007,-3.217 6.007,-6.008c0,-0.091 -0.002,-0.183 -0.006,-0.273c0.413,-0.298
                  0.771,-0.67 1.054,-1.093Z"></path>
            </svg>
         </a>
         <a href="/#" class="w-6 mx-1">
            <svg class="fill-current cursor-pointer text-gray-500 hover:text-gray-400" width="100%" height="100%" viewBox="0 0 24 24" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xml:space="preserve" xmlns:serif="http://www.serif.com/" style="fill-rule: evenodd; clip-rule: evenodd; stroke-linejoin: round; stroke-miterlimit: 2;">
               <path id="Facebook" d="M24,12c0,6.627 -5.373,12 -12,12c-6.627,0 -12,-5.373 -12,-12c0,-6.627
                  5.373,-12 12,-12c6.627,0 12,5.373
                  12,12Zm-11.278,0l1.294,0l0.172,-1.617l-1.466,0l0.002,-0.808c0,-0.422
                  0.04,-0.648 0.646,-0.648l0.809,0l0,-1.616l-1.295,0c-1.555,0 -2.103,0.784
                  -2.103,2.102l0,0.97l-0.969,0l0,1.617l0.969,0l0,4.689l1.941,0l0,-4.689Z"></path>
            </svg>
         </a>
         <a href="/#" class="w-6 mx-1">
            <svg class="fill-current cursor-pointer text-gray-500 hover:text-gray-400" width="100%" height="100%" viewBox="0 0 24 24" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xml:space="preserve" xmlns:serif="http://www.serif.com/" style="fill-rule: evenodd; clip-rule: evenodd; stroke-linejoin: round; stroke-miterlimit: 2;">
               <g id="Layer_1">
                  <circle id="Oval" cx="12" cy="12" r="12"></circle>
                  <path id="Shape" d="M19.05,8.362c0,-0.062 0,-0.125 -0.063,-0.187l0,-0.063c-0.187,-0.562
                     -0.687,-0.937 -1.312,-0.937l0.125,0c0,0 -2.438,-0.375 -5.75,-0.375c-3.25,0
                     -5.75,0.375 -5.75,0.375l0.125,0c-0.625,0 -1.125,0.375
                     -1.313,0.937l0,0.063c0,0.062 0,0.125 -0.062,0.187c-0.063,0.625 -0.25,1.938
                     -0.25,3.438c0,1.5 0.187,2.812 0.25,3.437c0,0.063 0,0.125
                     0.062,0.188l0,0.062c0.188,0.563 0.688,0.938 1.313,0.938l-0.125,0c0,0
                     2.437,0.375 5.75,0.375c3.25,0 5.75,-0.375 5.75,-0.375l-0.125,0c0.625,0
                     1.125,-0.375 1.312,-0.938l0,-0.062c0,-0.063 0,-0.125
                     0.063,-0.188c0.062,-0.625 0.25,-1.937 0.25,-3.437c0,-1.5 -0.125,-2.813
                     -0.25,-3.438Zm-4.634,3.927l-3.201,2.315c-0.068,0.068 -0.137,0.068
                     -0.205,0.068c-0.068,0 -0.136,0 -0.204,-0.068c-0.136,-0.068 -0.204,-0.204
                     -0.204,-0.34l0,-4.631c0,-0.136 0.068,-0.273 0.204,-0.341c0.136,-0.068
                     0.272,-0.068 0.409,0l3.201,2.316c0.068,0.068 0.136,0.204
                     0.136,0.34c0.068,0.136 0,0.273 -0.136,0.341Z" style="fill: rgb(255, 255, 255);"></path>
               </g>
            </svg>
         </a>
         <a href="/#" class="w-6 mx-1">
            <svg class="fill-current cursor-pointer text-gray-500 hover:text-gray-400" width="100%" height="100%" viewBox="0 0 24 24" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xml:space="preserve" xmlns:serif="http://www.serif.com/" style="fill-rule: evenodd; clip-rule: evenodd; stroke-linejoin: round; stroke-miterlimit: 2;">
               <path id="Shape" d="M7.3,0.9c1.5,-0.6 3.1,-0.9 4.7,-0.9c1.6,0 3.2,0.3 4.7,0.9c1.5,0.6 2.8,1.5
                  3.8,2.6c1,1.1 1.9,2.3 2.6,3.8c0.7,1.5 0.9,3 0.9,4.7c0,1.7 -0.3,3.2
                  -0.9,4.7c-0.6,1.5 -1.5,2.8 -2.6,3.8c-1.1,1 -2.3,1.9 -3.8,2.6c-1.5,0.7
                  -3.1,0.9 -4.7,0.9c-1.6,0 -3.2,-0.3 -4.7,-0.9c-1.5,-0.6 -2.8,-1.5
                  -3.8,-2.6c-1,-1.1 -1.9,-2.3 -2.6,-3.8c-0.7,-1.5 -0.9,-3.1 -0.9,-4.7c0,-1.6
                  0.3,-3.2 0.9,-4.7c0.6,-1.5 1.5,-2.8 2.6,-3.8c1.1,-1 2.3,-1.9
                  3.8,-2.6Zm-0.3,7.1c0.6,0 1.1,-0.2 1.5,-0.5c0.4,-0.3 0.5,-0.8 0.5,-1.3c0,-0.5
                  -0.2,-0.9 -0.6,-1.2c-0.4,-0.3 -0.8,-0.5 -1.4,-0.5c-0.6,0 -1.1,0.2
                  -1.4,0.5c-0.3,0.3 -0.6,0.7 -0.6,1.2c0,0.5 0.2,0.9 0.5,1.3c0.3,0.4 0.9,0.5
                  1.5,0.5Zm1.5,10l0,-8.5l-3,0l0,8.5l3,0Zm11,0l0,-4.5c0,-1.4 -0.3,-2.5
                  -0.9,-3.3c-0.6,-0.8 -1.5,-1.2 -2.6,-1.2c-0.6,0 -1.1,0.2 -1.5,0.5c-0.4,0.3
                  -0.8,0.8 -0.9,1.3l-0.1,-1.3l-3,0l0.1,2l0,6.5l3,0l0,-4.5c0,-0.6 0.1,-1.1
                  0.4,-1.5c0.3,-0.4 0.6,-0.5 1.1,-0.5c0.5,0 0.9,0.2 1.1,0.5c0.2,0.3 0.4,0.8
                  0.4,1.5l0,4.5l2.9,0Z"></path>
            </svg>
         </a>
         <a href="/#" class="w-6 mx-1">
            <svg class="fill-current cursor-pointer text-gray-500 hover:text-gray-400" width="100%" height="100%" viewBox="0 0 24 24" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xml:space="preserve" xmlns:serif="http://www.serif.com/" style="fill-rule: evenodd; clip-rule: evenodd; stroke-linejoin: round; stroke-miterlimit: 2;">
               <path id="Combined-Shape" d="M12,24c6.627,0 12,-5.373 12,-12c0,-6.627 -5.373,-12 -12,-12c-6.627,0
                  -12,5.373 -12,12c0,6.627 5.373,12 12,12Zm6.591,-15.556l-0.722,0c-0.189,0
                  -0.681,0.208 -0.681,0.385l0,6.422c0,0.178 0.492,0.323
                  0.681,0.323l0.722,0l0,1.426l-4.675,0l0,-1.426l0.935,0l0,-6.655l-0.163,0l-2.251,8.081l-1.742,0l-2.222,-8.081l-0.168,0l0,6.655l0.935,0l0,1.426l-3.74,0l0,-1.426l0.519,0c0.203,0
                  0.416,-0.145 0.416,-0.323l0,-6.422c0,-0.177 -0.213,-0.385
                  -0.416,-0.385l-0.519,0l0,-1.426l4.847,0l1.583,5.704l0.042,0l1.598,-5.704l5.021,0l0,1.426Z"></path>
            </svg>
         </a>
      </div>
   </div>
</div>
</div>
</div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
