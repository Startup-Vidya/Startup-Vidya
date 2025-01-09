<!DOCTYPE html>
<html lang="en">

  <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>home</title>
    <link rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/tailwindcss/2.1.4/tailwind.min.css">
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="//unpkg.com/alpinejs" defer></script>
    <link rel="stylesheet" href="style.css">

  </head>

  <body>
    <div>
      <section class="bg-zinc-950">
        <div class=" max-w-full px-6 lg:px-24 mx-auto py-6">
          <nav id="is9j" x-data="{ mobile: false }"
            class="relative  mx-auto flex items-center justify-between h-full"><a
              id="inus" href
              class="h-full">
              <span class="text-lg font-bold text-white">Dr. Anant
                Sardeshmukh</span>
            </a><!-- Mobile menu button -->
            <div
              id="ik8g" x-on:click="mobile = !mobile"
              class="block text-gray-700 hover:text-gray-900 lg:hidden"><div
                id="i3ko"><svg id="ivq2" xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 14 14" height="24" width="24"><g id="iehi"><line
                      id="i4ndg" x1="13.5" y1="2" x2="0.5" y2="2" fill="#FFFFFF"
                      stroke="#FFFFFF" stroke-linecap="round"
                      stroke-linejoin="round">
                    </line><line id="i1e34" x1="13.5" y1="7" x2="0.5" y2="7"
                      fill="#FFFFFF" stroke="#FFFFFF" stroke-linecap="round"
                      stroke-linejoin="round">
                    </line><line id="ijpyv" x1="13.5" y1="12" x2="0.5" y2="12"
                      fill="#FFFFFF" stroke="#FFFFFF" stroke-linecap="round"
                      stroke-linejoin="round">
                    </line></g></svg></div>
            </div><!-- Mobile Menu open: "block", Menu closed: "hidden" -->
            <div id="i3f5s" :class="{ 'hidden' : !mobile, 'flex': mobile }"
              class="px-6 pb-6 pt-6 lg:pt-0 absolute -left-6 -right-6 z-20 top-10 flex-col select-none lg:static lg:top-0 lg:left-0 lg:right-0 lg:flex lg:flex-row lg:pb-0 lg:gap-6 lg:px-0 hidden text-sm bg-zinc-950">
              <a
                id="i187s" href="/home.html"
                class="py-3 text-gray-100 hover:text-gray-300 font-medium">Home</a>
              <a
                id="ipwgh" href="/about.html"
                class="py-3 text-gray-100 hover:text-gray-300 font-medium">About</a>
              <a
                id="iwtie" href="/services.html"
                class="py-3 text-gray-100 hover:text-gray-300 font-medium">Services</a>
              <a
                id="ig1i5" href="/books.html"
                class="py-3 text-gray-100 hover:text-gray-300 font-medium">Books
                and Blogs</a>
              <a
                id="ig1i5" href="/contact.html"
                class="py-3 text-gray-100 hover:text-gray-300 font-medium">Contact</a>
            </div>
            <div class="hidden lg:block">
              <div class="flex flex-row justify-center items-center gap-6">
                <a href="https://www.facebook.com/anant.sardeshmukh/"
                  target="_blank">
                  <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16"
                    fill="currentColor"
                    class="bi bi-facebook text-white hover:scale-125 transition ease-linear duration-300"
                    viewBox="0 0 16 16">
                    <path
                      d="M16 8.049c0-4.446-3.582-8.05-8-8.05C3.58 0-.002 3.603-.002 8.05c0 4.017 2.926 7.347 6.75 7.951v-5.625h-2.03V8.05H6.75V6.275c0-2.017 1.195-3.131 3.022-3.131.876 0 1.791.157 1.791.157v1.98h-1.009c-.993 0-1.303.621-1.303 1.258v1.51h2.218l-.354 2.326H9.25V16c3.824-.604 6.75-3.934 6.75-7.951"></path>
                  </svg>
                </a>
                <a
                  href="https://www.linkedin.com/in/dr-anant-sardeshmukh-a696ab7/"
                  target="_blank">
                  <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16"
                    fill="currentColor"
                    class="bi bi-linkedin text-white hover:scale-125 transition ease-linear duration-300"
                    viewBox="0 0 16 16">
                    <path
                      d="M0 1.146C0 .513.526 0 1.175 0h13.65C15.474 0 16 .513 16 1.146v13.708c0 .633-.526 1.146-1.175 1.146H1.175C.526 16 0 15.487 0 14.854zm4.943 12.248V6.169H2.542v7.225zm-1.2-8.212c.837 0 1.358-.554 1.358-1.248-.015-.709-.52-1.248-1.342-1.248S2.4 3.226 2.4 3.934c0 .694.521 1.248 1.327 1.248zm4.908 8.212V9.359c0-.216.016-.432.08-.586.173-.431.568-.878 1.232-.878.869 0 1.216.662 1.216 1.634v3.865h2.401V9.25c0-2.22-1.184-3.252-2.764-3.252-1.274 0-1.845.7-2.165 1.193v.025h-.016l.016-.025V6.169h-2.4c.03.678 0 7.225 0 7.225z"></path>
                  </svg>
                </a>
                <a href="https://twitter.com/Anantsardeshmuk" target="_blank">
                  <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16"
                    fill="currentColor"
                    class="bi bi-twitter-x text-white hover:scale-125 transition ease-linear duration-300"
                    viewBox="0 0 16 16">
                    <path
                      d="M12.6.75h2.454l-5.36 6.142L16 15.25h-4.937l-3.867-5.07-4.425 5.07H.316l5.733-6.57L0 .75h5.063l3.495 4.633L12.601.75Zm-.86 13.028h1.36L4.323 2.145H2.865z"></path>
                  </svg>
                </a>
                <a
                  href="https://www.youtube.com/@entrepreneurshipenterprise3931"
                  target="_blank">
                  <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20"
                    fill="currentColor"
                    class="bi bi-youtube text-white hover:scale-125 transition ease-linear duration-300"
                    viewBox="0 0 16 16">
                    <path
                      d="M8.051 1.999h.089c.822.003 4.987.033 6.11.335a2.01 2.01 0 0 1 1.415 1.42c.101.38.172.883.22 1.402l.01.104.022.26.008.104c.065.914.073 1.77.074 1.957v.075c-.001.194-.01 1.108-.082 2.06l-.008.105-.009.104c-.05.572-.124 1.14-.235 1.558a2.01 2.01 0 0 1-1.415 1.42c-1.16.312-5.569.334-6.18.335h-.142c-.309 0-1.587-.006-2.927-.052l-.17-.006-.087-.004-.171-.007-.171-.007c-1.11-.049-2.167-.128-2.654-.26a2.01 2.01 0 0 1-1.415-1.419c-.111-.417-.185-.986-.235-1.558L.09 9.82l-.008-.104A31 31 0 0 1 0 7.68v-.123c.002-.215.01-.958.064-1.778l.007-.103.003-.052.008-.104.022-.26.01-.104c.048-.519.119-1.023.22-1.402a2.01 2.01 0 0 1 1.415-1.42c.487-.13 1.544-.21 2.654-.26l.17-.007.172-.006.086-.003.171-.007A100 100 0 0 1 7.858 2zM6.4 5.209v4.818l4.157-2.408z" />
                  </svg>
                </a>
              </div>
            </div>
          </nav>
        </div>
      </section>
      <!-- hero  -->
      <section class>
        <div class="mx-auto">
          <div class="flex flex-col lg:flex-row">
            <div class="lg:w-1/1 flex flex-col justify-between">
              <div class="hero-data mt-10 p-6 lg:p-20">
                <div class="hero-content">
                  <h1
                    class="text-4xl font-medium lg:text-6xl">Leading
                    with Passion to Create Change</h1>
                  <div class="mt-6 text-lg">
                    <p>Dr. Anant Sardeshmukh, a finance professional with 40
                      years of expertise, specializes in MSME, project finance,
                      and strategic leadership, empowering businesses through
                      impactful contributions in academia and industry.</p>
                  </div>
                  <div class="group max-w-60 mt-10">
                    <a href="about.html"
                      class="border-3 inline-flex items-center justify-center gap-3 rounded-md text-white bg-purple-700 hover:bg-purple-900 px-6 py-3 text-lg font-medium text-black shadow-lg transition duration-300">
                      <span>Explore More</span>
                      <div class="relative">
                        <svg xmlns="http://www.w3.org/2000/svg" width="40"
                          height="40" fill="currentColor" stroke="white"
                          stroke-width="1"
                          class="bi bi-arrow-up-right w-5 group-hover:rotate-90 transition ease-in-out duration-500 font-extrabold"
                          viewBox="0 0 16 16">
                          <path fill-rule="evenodd"
                            d="M14 2.5a.5.5 0 0 0-.5-.5h-6a.5.5 0 0 0 0 1h4.793L2.146 13.146a.5.5 0 0 0 .708.708L13 3.707V8.5a.5.5 0 0 0 1 0z" />
                        </svg>
                      </div>
                    </a>
                  </div>
                  <p class="pt-4 italic">Empowering Communities Transforming
                    Lives</p>
                </div>
              </div>
              <div
                class="bg-zinc-900 py-10 px-10 hidden lg:block">
                <div class="container mx-auto px-5 text-center lg:text-left">
                  <div
                    class="hero-info flex flex-col items-center justify-between gap-8 lg:flex-row">
                    <div class="hero-skill">
                      <h3 class="mb-4 font-semibold text-white">Employment in
                        Companies :</h3>
                      <div
                        class="flex flex-row items-center gap-6 lg:gap-12 mt-6">
                        <div>
                          <img src="./Images/bajaj.png" alt
                            class="w-32">
                        </div>
                        <div>
                          <img src="./Images/fdc.png" alt
                            class="w-28">
                        </div>
                        <div>
                          <img src="./Images/deepak.png"
                            alt class="w-28">
                        </div>
                        <div>
                          <img src="./Images/century.png"
                            alt class="w-40">
                        </div>
                        <div>
                          <img
                            src="./Images/kinetic-finance.png"
                            alt class="w-40">
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="relative lg:bg-zinc-50 lg:w-2/3">
              <img src="./Images/Hero-Profile-Image-Desktop.png"
                alt="Hero Main"
                class="hero-thumbnail h-full w-full object-cover hidden lg:block" />
              <img src="./Images/Hero-Profile-Image-Mobile.png"
                alt="Hero Main"
                class="hero-thumbnail h-full w-full object-cover block lg:hidden" />
            </div>
            <div
              class="bg-zinc-900 py-10 px-10 lg:hidden block">
              <div class="container mx-auto px-5 text-center lg:text-left">
                <div
                  class="hero-info flex flex-col items-center justify-between gap-8 lg:flex-row">
                  <div class="hero-skill">
                    <h3 class="mb-4 font-medium text-gray-200">Employment in
                      Companies :</h3>
                    <div
                      class="flex flex-row items-center gap-6 lg:gap-12 mt-6">
                      <div>
                        <img loading="lazy" width="40" height="40"
                          src="./Images/bajaj.png"
                          alt="company-image" class="w-full lg:w-28">
                      </div>
                      <div>
                        <img loading="lazy" width="40" height="40"
                          src="./Images/fdc.png"
                          alt="company-image" class="w-full lg:w-20 h-full">
                      </div>
                      <div>
                        <img loading="lazy" width="40" height="40"
                          src="./Images/deepak.png"
                          alt="company-image" class="w-full lg:w-20 h-full">
                      </div>
                      <div>
                        <img loading="lazy" width="40" height="40"
                          src="./Images/century.png"
                          alt="company-image" class="w-full lg:w-28 h-full">
                      </div>
                      <div>
                        <img loading="lazy" width="40" height="40"
                          src="./Images/kinetic-finance.png"
                          alt="company-image" class="w-full lg:w-28 h-full">
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- about  -->
      <section class="py-20 lg:py-24 bg-gray-50">
        <div class="max-w-7xl mx-auto px-6 ">
          <div class="mb-10">
            <h2 class="text-4xl font-semibold">About</h2>
          </div>
          <div class="flex flex-col lg:flex-row gap-6 pb-10">
            <!-- Image Wrapper -->
            <div class="overflow-hidden rounded-2xl w-full lg:w-1/3">
              <img src="./Images/about-profile-image.png"
                alt="Hi I'm Sophie Moore Writing Portrait"
                class="h-full w-full object-cover" />
            </div>
            <!-- Hero Card -->
            <div class="bg-gray-100 p-6 lg:p-20 rounded-2xl w-full lg:w-2/3">
              <div class="flex flex-col justify-center h-full">
                <div>
                  <h1
                    class="text-3xl lg:text-4xl font-semibold text-gray-900">Dr.
                    Anant Sardeshmukh</h1>
                  <div class="pt-2 text-gray-700">
                    <p>- Certified Independent Director by Indian Institute of
                      Corporate affairs <br>(Under the Aegis of Ministry of
                      Corporate
                      Affairs, Government of India)</p>
                    <p>- Certified Director Corporate Governance ( IICA,MCA)</p>
                    <p>- Certified Director Start- up Board (IICA,MCA)</p>
                    <p class="text-gray-700 mt-2 hidden">A finance professional
                      with 40
                      years of expertise, specializes in MSME, project finance,
                      and
                      strategic leadership, empowering businesses through
                      impactful
                      contributions in academia and industry.</p>
                  </div>
                </div>
                <div class="mt-6">
                  <h2 class="text-2xl font-medium text-gray-900">About</h2>
                  <p class="text-gray-700 mt-2">A finance professional with 40
                    years of expertise, specializes in MSME, project finance,
                    and
                    strategic leadership, empowering businesses through
                    impactful
                    contributions in academia and industry. He Served as
                    Director and Executive
                    Committee Member, excelling in governance, start-up
                    consulting, and strategic planning to drive innovation and
                    sustainable business growth.</p>
                </div>
                <div class="mt-6">
                  <h2 class="font-medium text-gray-900">Connect with me on
                    social media:</h2>
                  <div class="flex flex-row items-center gap-6 mt-4">
                    <a href="https://www.facebook.com/anant.sardeshmukh/"
                      target="_blank">
                      <svg xmlns="http://www.w3.org/2000/svg" width="20"
                        height="20" fill="currentColor"
                        class="bi bi-facebook text-zinc-900 hover:scale-125 transition ease-linear duration-300"
                        viewBox="0 0 16 16">
                        <path
                          d="M16 8.049c0-4.446-3.582-8.05-8-8.05C3.58 0-.002 3.603-.002 8.05c0 4.017 2.926 7.347 6.75 7.951v-5.625h-2.03V8.05H6.75V6.275c0-2.017 1.195-3.131 3.022-3.131.876 0 1.791.157 1.791.157v1.98h-1.009c-.993 0-1.303.621-1.303 1.258v1.51h2.218l-.354 2.326H9.25V16c3.824-.604 6.75-3.934 6.75-7.951"></path>
                      </svg>
                    </a>
                    <a
                      href="https://www.linkedin.com/in/dr-anant-sardeshmukh-a696ab7/"
                      target="_blank">
                      <svg xmlns="http://www.w3.org/2000/svg" width="20"
                        height="20" fill="currentColor"
                        class="bi bi-linkedin text-zinc-900 hover:scale-125 transition ease-linear duration-300"
                        viewBox="0 0 16 16">
                        <path
                          d="M0 1.146C0 .513.526 0 1.175 0h13.65C15.474 0 16 .513 16 1.146v13.708c0 .633-.526 1.146-1.175 1.146H1.175C.526 16 0 15.487 0 14.854zm4.943 12.248V6.169H2.542v7.225zm-1.2-8.212c.837 0 1.358-.554 1.358-1.248-.015-.709-.52-1.248-1.342-1.248S2.4 3.226 2.4 3.934c0 .694.521 1.248 1.327 1.248zm4.908 8.212V9.359c0-.216.016-.432.08-.586.173-.431.568-.878 1.232-.878.869 0 1.216.662 1.216 1.634v3.865h2.401V9.25c0-2.22-1.184-3.252-2.764-3.252-1.274 0-1.845.7-2.165 1.193v.025h-.016l.016-.025V6.169h-2.4c.03.678 0 7.225 0 7.225z"></path>
                      </svg>
                    </a>
                    <a href="https://twitter.com/Anantsardeshmuk"
                      target="_blank">
                      <svg xmlns="http://www.w3.org/2000/svg" width="20"
                        height="20" fill="currentColor"
                        class="bi bi-twitter-x text-zinc-900 hover:scale-125 transition ease-linear duration-300"
                        viewBox="0 0 16 16">
                        <path
                          d="M12.6.75h2.454l-5.36 6.142L16 15.25h-4.937l-3.867-5.07-4.425 5.07H.316l5.733-6.57L0 .75h5.063l3.495 4.633L12.601.75Zm-.86 13.028h1.36L4.323 2.145H2.865z"></path>
                      </svg>
                    </a>
                    <a
                      href="https://www.youtube.com/@entrepreneurshipenterprise3931"
                      target="_blank">
                      <svg xmlns="http://www.w3.org/2000/svg" width="24"
                        height="24" fill="currentColor"
                        class="bi bi-youtube text-zinc-900 hover:scale-125 transition ease-linear duration-300"
                        viewBox="0 0 16 16">
                        <path
                          d="M8.051 1.999h.089c.822.003 4.987.033 6.11.335a2.01 2.01 0 0 1 1.415 1.42c.101.38.172.883.22 1.402l.01.104.022.26.008.104c.065.914.073 1.77.074 1.957v.075c-.001.194-.01 1.108-.082 2.06l-.008.105-.009.104c-.05.572-.124 1.14-.235 1.558a2.01 2.01 0 0 1-1.415 1.42c-1.16.312-5.569.334-6.18.335h-.142c-.309 0-1.587-.006-2.927-.052l-.17-.006-.087-.004-.171-.007-.171-.007c-1.11-.049-2.167-.128-2.654-.26a2.01 2.01 0 0 1-1.415-1.419c-.111-.417-.185-.986-.235-1.558L.09 9.82l-.008-.104A31 31 0 0 1 0 7.68v-.123c.002-.215.01-.958.064-1.778l.007-.103.003-.052.008-.104.022-.26.01-.104c.048-.519.119-1.023.22-1.402a2.01 2.01 0 0 1 1.415-1.42c.487-.13 1.544-.21 2.654-.26l.17-.007.172-.006.086-.003.171-.007A100 100 0 0 1 7.858 2zM6.4 5.209v4.818l4.157-2.408z" />
                      </svg>
                    </a>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <div class="mt-16">
            <div class="flex justify-center gap-10 h-full w-full">
              <div class="w-full lg:w-2/3">
                <div id="ie60l-2-2" class="mb-10 text-left">
                  <h2 id="ih0mc-2-2" class="text-4xl font-semibold">Vision and
                    Mission</h2>
                </div>
                <div class="grid gap-8 sm:grid-cols-2">
                  <div id="iae06h-4" class="flex gap-4">
                    <div id="ipws6j-5" class="mt-1 flex flex-col items-center">
                      <span id="ilfgu-4-4-2-4"
                        class="grid h-6 w-6 place-items-center rounded-full bg-purple-700 p-1"><svg
                          id="imri3-4-4-2-4" xmlns="http://www.w3.org/2000/svg"
                          width="14" height="14" fill="#ffffff"
                          viewBox="0 0 16 16"
                          class="bi bi-check-lg text-gray-800"><path
                            id="iye7a-4-4-2-4"
                            d="M12.736 3.97a.733.733 0 0 1 1.047 0c.286.289.29.756.01 1.05L7.88 12.01a.733.733 0 0 1-1.065.02L3.217 8.384a.757.757 0 0 1 0-1.06.733.733 0 0 1 1.047 0l3.052 3.093 5.4-6.425z"></path></svg></span>
                    </div>
                    <div id="i4roa8-5-2">
                      <div id="i28y9l"
                        class="mb-2 text-xl font-medium text-gray-800">Empowering
                        Businesses</div>
                      <div id="i3bksr" class="text-base text-gray-600">Fostering
                        sustainable development for MSMEs with innovative
                        strategies.</div>
                    </div>
                  </div>
                  <div id="iae06h-4-2" class="flex gap-4">
                    <div id="ipws6j-5-2"
                      class="mt-1 flex flex-col items-center">
                      <span id="ilfgu-4-4-2-5"
                        class="grid h-6 w-6 place-items-center rounded-full bg-purple-700 p-1"><svg
                          id="imri3-4-4-2-5" xmlns="http://www.w3.org/2000/svg"
                          width="14" height="14" fill="#ffffff"
                          viewBox="0 0 16 16"
                          class="bi bi-check-lg text-gray-800"><path
                            id="iye7a-4-4-2-5"
                            d="M12.736 3.97a.733.733 0 0 1 1.047 0c.286.289.29.756.01 1.05L7.88 12.01a.733.733 0 0 1-1.065.02L3.217 8.384a.757.757 0 0 1 0-1.06.733.733 0 0 1 1.047 0l3.052 3.093 5.4-6.425z"></path></svg></span>
                    </div>
                    <div id="i4roa8-5-2-2">
                      <div id="i28y9l-2"
                        class="mb-2 text-xl font-medium text-gray-800">Driving
                        Excellence</div>
                      <div id="i3bksr-2"
                        class="text-base text-gray-600">Promoting industry
                        standards through robust governance and practices.</div>
                    </div>
                  </div>
                  <div id="iae06h-4-3" class="flex gap-4">
                    <div id="ipws6j-5-3"
                      class="mt-1 flex flex-col items-center">
                      <span id="ilfgu-4-4-2-6"
                        class="grid h-6 w-6 place-items-center rounded-full bg-purple-700 p-1"><svg
                          id="imri3-4-4-2-6" xmlns="http://www.w3.org/2000/svg"
                          width="14" height="14" fill="#ffffff"
                          viewBox="0 0 16 16"
                          class="bi bi-check-lg text-gray-800"><path
                            id="iye7a-4-4-2-6"
                            d="M12.736 3.97a.733.733 0 0 1 1.047 0c.286.289.29.756.01 1.05L7.88 12.01a.733.733 0 0 1-1.065.02L3.217 8.384a.757.757 0 0 1 0-1.06.733.733 0 0 1 1.047 0l3.052 3.093 5.4-6.425z"></path></svg></span>
                    </div>
                    <div id="i4roa8-5-2-3">
                      <div id="i28y9l-3"
                        class="mb-2 text-xl font-medium text-gray-800">Inspiring
                        Leadership</div>
                      <div id="i3bksr-3" class="text-base text-gray-600">Shaping
                        future leaders with knowledge, guidance, and
                        mentorship.</div>
                    </div>
                  </div>
                  <div id="iae06h-4-4" class="flex gap-4">
                    <div id="ipws6j-5-4"
                      class="mt-1 flex flex-col items-center">
                      <span id="ilfgu-4-4-2-7"
                        class="grid h-6 w-6 place-items-center rounded-full bg-purple-700 p-1"><svg
                          id="imri3-4-4-2-7" xmlns="http://www.w3.org/2000/svg"
                          width="14" height="14" fill="#ffffff"
                          viewBox="0 0 16 16"
                          class="bi bi-check-lg text-gray-800"><path
                            id="iye7a-4-4-2-7"
                            d="M12.736 3.97a.733.733 0 0 1 1.047 0c.286.289.29.756.01 1.05L7.88 12.01a.733.733 0 0 1-1.065.02L3.217 8.384a.757.757 0 0 1 0-1.06.733.733 0 0 1 1.047 0l3.052 3.093 5.4-6.425z"></path></svg></span>
                    </div>
                    <div id="i4roa8-5-2-4">
                      <div id="i28y9l-4"
                        class="mb-2 text-xl font-medium text-gray-800">Strengthening
                        Communities</div>
                      <div id="i3bksr-4"
                        class="text-base text-gray-600">Building sustainable
                        growth through entrepreneurship and social
                        responsibility.</div>
                    </div>
                  </div>
                  <div id="iae06h-4-5" class="flex gap-4">
                    <div id="ipws6j-5-5"
                      class="mt-1 flex flex-col items-center">
                      <span id="ilfgu-4-4-2-8"
                        class="grid h-6 w-6 place-items-center rounded-full bg-purple-700 p-1"><svg
                          id="imri3-4-4-2-8" xmlns="http://www.w3.org/2000/svg"
                          width="14" height="14" fill="#ffffff"
                          viewBox="0 0 16 16"
                          class="bi bi-check-lg text-gray-800"><path
                            id="iye7a-4-4-2-8"
                            d="M12.736 3.97a.733.733 0 0 1 1.047 0c.286.289.29.756.01 1.05L7.88 12.01a.733.733 0 0 1-1.065.02L3.217 8.384a.757.757 0 0 1 0-1.06.733.733 0 0 1 1.047 0l3.052 3.093 5.4-6.425z"></path></svg></span>
                    </div>
                    <div id="i4roa8-5-2-5">
                      <div id="i28y9l-5"
                        class="mb-2 text-xl font-medium text-gray-800">Innovating
                        Solutions</div>
                      <div id="i3bksr-5"
                        class="text-base text-gray-600">Providing effective
                        strategies to address diverse industrial
                        challenges.</div>
                    </div>
                  </div>
                  <div id="iae06h-4-6" class="flex gap-4">
                    <div id="ipws6j-5-6"
                      class="mt-1 flex flex-col items-center">
                      <span id="ilfgu-4-4-2-9"
                        class="grid h-6 w-6 place-items-center rounded-full bg-purple-700 p-1"><svg
                          id="imri3-4-4-2-9" xmlns="http://www.w3.org/2000/svg"
                          width="14" height="14" fill="#ffffff"
                          viewBox="0 0 16 16"
                          class="bi bi-check-lg text-gray-800"><path
                            id="iye7a-4-4-2-9"
                            d="M12.736 3.97a.733.733 0 0 1 1.047 0c.286.289.29.756.01 1.05L7.88 12.01a.733.733 0 0 1-1.065.02L3.217 8.384a.757.757 0 0 1 0-1.06.733.733 0 0 1 1.047 0l3.052 3.093 5.4-6.425z"></path></svg></span>
                    </div>
                    <div id="i4roa8-5-2-6">
                      <div id="i28y9l-6"
                        class="mb-2 text-xl font-medium text-gray-800">RGlobal
                        Outreach</div>
                      <div id="i3bksr-6"
                        class="text-base text-gray-600">Expanding businesses
                        internationally with strategic partnerships and
                        opportunities.</div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="hidden w-1/3 lg:block">
                <div class="h-full">
                  <img loading="lazy" alt="benefits" width="100%" height="100%"
                    src="./Images/Dr.Anant-with-Awards.avif"
                    class="h-full w-full transform rounded-2xl object-cover" />
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- areas of work  -->
      <section class="mx-auto max-w-6xl px-6 py-20 lg:py-24">
        <div class="sm:text-center">
          <h2 class="text-4xl font-semibold">Services offered</h2>
          <p class="mx-auto mb-10 lg:mb-16 mt-4 text-gray-600">Services offered</p>
        </div>
        <div
          class="grid sm:grid-cols-2 md:grid-cols-2 lg:grid-cols-2 gap-x-6 gap-y-10">
          <div class="flex flex-col md:items-center md:text-center">
            <div class="rounded-xl">
              
              <img loading="lazy"
                src="./Images/service-1.jpeg"
                alt="problem 1"
                class="h-56 w-full rounded-xl object-cover transition-all duration-300 ease-out sm:h-52" />
            </div>
            <div class="mt-5">
              <h2 class="text-xl font-medium text-gray-900">Corporate Advisory
                on Strategy, policy, systems, Compliance and Governance</h2>
            </div>
          </div>
          <div class="flex flex-col md:items-center md:text-center">
            <div class="rounded-xl">
              
              <img loading="lazy"
                src="./Images/service-2.jpg"
                alt="problem 1"
                class="h-56 w-full rounded-xl object-cover transition-all duration-300 ease-out sm:h-52" />
            </div>
            <div class="mt-5">
              <h2 class="text-xl font-medium text-gray-900">Financial Services
                including Fund Sourcing </h2>
            </div>
          </div>
          <div class="flex flex-col md:items-center md:text-center">
            <div class="rounded-xl">
              
              <img loading="lazy"
                src="./Images/service-3.jpg"
                alt="problem 1"
                class="h-56 w-full rounded-xl object-cover transition-all duration-300 ease-out sm:h-52" />
            </div>
            <div class="mt-5">
              <h2 class="text-xl font-medium text-gray-900">International
                Partner identification, tie ups</h2>
            </div>
          </div>

          <div class="flex flex-col md:items-center md:text-center">
            <div class="rounded-xl">
              
              <img loading="lazy"
                src="./Images/service-4.jpg"
                alt="problem 1"
                class="h-56 w-full rounded-xl object-cover transition-all duration-300 ease-out sm:h-52" />
            </div>
            <div class="mt-5">
              <h2 class="text-xl font-medium text-gray-900">Business
                Negotiations, Agreements </h2>
            </div>
          </div>
          <div class="flex flex-col md:items-center md:text-center">
            <div class="rounded-xl">
              
              <img loading="lazy"
                src="./Images/service-5.jpg"
                alt="problem 1"
                class="h-56 w-full rounded-xl object-cover transition-all duration-300 ease-out sm:h-52" />
            </div>
            <div class="mt-5">
              <h2 class="text-xl font-medium text-gray-900">Government Relations
                and Representations</h2>
            </div>
          </div>
          <div class="flex flex-col md:items-center md:text-center">
            <div class="rounded-xl">
              
              <img loading="lazy"
                src="./Images/service-6.jpg"
                alt="problem 1"
                class="h-56 w-full rounded-xl object-cover transition-all duration-300 ease-out sm:h-52" />
            </div>
            <div class="mt-5">
              <h2 class="text-xl font-medium text-gray-900">Senior Management
                Selection, Training and Development </h2>
            </div>
          </div>
          <div class="flex flex-col md:items-center md:text-center">
            <div class="rounded-xl">
              
              <img loading="lazy"
                src="./Images/service-7.jpg"
                alt="problem 1"
                class="h-56 w-full rounded-xl object-cover transition-all duration-300 ease-out sm:h-52" />
            </div>
            <div class="mt-5">
              <h2 class="text-xl font-medium text-gray-900">New, Institutions,
                Project development and Implementation </h2>
            </div>
          </div>
        </div>
      </section>
      <!-- award  -->
      <section class="py-20 lg:py-24 bg-gray-100">
        <div class="max-w-4xl mx-auto px-6">
          <div>
            <img src="./Images/Dr.Anant-with-Awards.avif" alt="Anant Sardeshmukh"
              class="rounded-2xl w-full">
          </div>
          <div class="mt-10">
            <p class="text-2xl font-medium text-center text-gray-900">Honoring
              Achievements and Leadership Celebrating <br> Dr. Anant
              Sardeshmukh’s
              Impact on Business and Community</p>
            <div class="mt-16">
              <img src="./Images/Awards-Image.png" alt="Awards" class="w-full">
            </div>
          </div>
        </div>
      </section>
      <!-- book  -->
      <section class="py-20 lg:py-24 bg-zinc-900">
        <div class="max-w-6xl mx-auto px-6 md:px-8">
          <div class="flex flex-col lg:flex-row gap-6 lg:gap-12 justify-center">
            <!-- Book Image Wrapper -->
            <div class=" overflow-hidden lg:w-1/3 rounded-2xl">

              <a
                href="https://www.amazon.in/Startup-Vishayi-Sarva-Anant-Sirdeshmukh/dp/9391469892"
                class="relative overflow-hidden">
                <img
                  src="./Images/book-image.png"
                  alt="Book 01"
                  class="rounded-2xl w-full h-full hover:scale-105 transition ease-linear duration-500" />
              </a>
            </div>
            <!-- Book Info Wrapper -->
            <div class="flex flex-col justify-between gap-4 lg:w-2/3">
              <div>
                <h2 class="text-4xl font-semibold text-white">Comprehensive
                  Guide to Startups and Success</h2>
                <div class="text-lg text-gray-300 py-2">
                  <p class="mt-4">
                    Discover practical strategies to kickstart and grow your
                    startup journey with actionable insights and guidance.
                  </p>
                  <p class="mt-4">
                    Learn about essential startup concepts, planning, and
                    execution to create a sustainable and successful business.
                  </p>
                  <p class="mt-4">
                    Gain deep insights into MSME policies, entrepreneurial
                    characteristics, and strategies tailored for startup
                    success.
                  </p>
                  <p class="mt-4">
                    Explore real-world examples and case studies to understand
                    the challenges and opportunities in startup development.
                  </p>
                  <p class="mt-4">
                    Explore real-world examples and case studies to understand
                    the challenges and opportunities in startup development.
                  </p>
                </div>
              </div>
              <div
                class="group mt-4 flex flex-col lg:flex-row gap-6 items-center">
                <a
                  href="https://www.amazon.in/Startup-Vishayi-Sarva-Anant-Sirdeshmukh/dp/9391469892"
                  class="border-3 inline-flex items-center justify-center gap-3 rounded-md text-white bg-purple-700 hover:bg-purple-900 px-6 py-3 text-lg font-medium text-black shadow-lg transition duration-300 w-80">
                  <span>Buy Now</span>
                  <div class="relative">
                    <svg xmlns="http://www.w3.org/2000/svg" width="40"
                      height="40" fill="currentColor" stroke="white"
                      stroke-width="1"
                      class="bi bi-arrow-up-right w-5 group-hover:rotate-90 transition ease-in-out duration-500 font-extrabold"
                      viewBox="0 0 16 16">
                      <path fill-rule="evenodd"
                        d="M14 2.5a.5.5 0 0 0-.5-.5h-6a.5.5 0 0 0 0 1h4.793L2.146 13.146a.5.5 0 0 0 .708.708L13 3.707V8.5a.5.5 0 0 0 1 0z"></path>
                    </svg>
                  </div>
                </a>
                <div
                  class="grid grid-cols-4 items-center gap-6 lg:gap-4 lg:mt-0 mt-2">
                  <a
                    href="https://www.amazon.in/Startup-Vishayi-Sarva-Anant-Sirdeshmukh/dp/9391469892">
                    <img
                      src="./Images/amazon-white-icon.png"
                      alt class="w-8 h-auto">
                  </a>
                  <a
                    href="https://www.flipkart.com/startupvishayi-sarva-kahi/p/itm837c1efe7f999">
                    <img src="./Images/flipkart.png" alt
                      class="w-8 h-auto">
                  </a>
                  <a
                    href="https://www.rajhansprakashan.com/product-details/startup-vishayi-sarva-kahi">
                    <img
                      src="./Images/rajhans.jpg"
                      alt class="w-8 h-auto rounded-full">
                  </a>
                  <a
                    href="https://payalbooks.com/products/startupvishayi-sarva-kahi-by-dr-anant-sardeshmukh?srsltid=AfmBOooC8LkQGizOiWzyGKU-vSobP9BgQ7siNfJ6NPeOmfby4_g8tiDM">
                    <img src="./Images/payal.png"
                      alt class="w-8 h-auto rounded-full">
                  </a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
      <!-- news  -->
      <section class="py-20 lg:py-24">
        <div class="mx-auto max-w-7xl px-6">
          <div class="mb-10 flex w-full items-center">
            <h2 class="text-4xl font-semibold">In News</h2>
          </div>
          <div
            class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6 lg:gap-10">
            <div class="mb-10 space-y-4">
              <a
                href="https://www.hindustantimes.com/pune-news/brightest-minds-innovative-ideas-enter-mccia-hall-of-recognition/story-Jvnl26niv2odWO53tt980M.html"
                class="block w-full"><img
                  src="./Images/News1.webp"
                  class="h-full w-full rounded-xl scale-100 transform object-cover object-center transition duration-500 ease-out hover:scale-105" /></a>
              <p
                class="text-xs font-medium uppercase text-gray-400 pb-2">Hindustan
                Times: Sep 05, 2018</p>
              <a href="https://www.hindustantimes.com/pune-news/brightest-minds-innovative-ideas-enter-mccia-hall-of-recognition/story-Jvnl26niv2odWO53tt980M.html" class="mt-4 text-xl font-medium">MCCIA recognises
                brightest industrial minds, innovative ideas through innovation
                and entrepreneurship awards 2018</a>
            </div>
            <div class="mb-10 space-y-4">
              <a href="https://timesofindia.indiatimes.com/city/pune/pune-a-multi-industry-hub-now-people-here-dont-lack-entrepreneurship-says-sardeshmukh/articleshow/66011021.cms" class="block w-full"><img
                  src="./Images/News2.webp"
                  class="h-full w-full rounded-xl scale-100 transform object-cover object-center transition duration-500 ease-out hover:scale-105" /></a>
              <p class="text-xs font-medium uppercase text-gray-400 pb-2">Times
                of India: Sep 30, 2018</p>
              <a href="https://timesofindia.indiatimes.com/city/pune/pune-a-multi-industry-hub-now-people-here-dont-lack-entrepreneurship-says-sardeshmukh/articleshow/66011021.cms" class="mt-4 text-xl font-medium">Pune a
                multi-industry hub now, people here don’t lack entrepreneurship,
                says Sardeshmukh</a>
            </div>
            <div class="mb-10 space-y-4">
              <a href="https://indianexpress.com/article/business/budget/budget-2017-18-anant-sardeshmukh-demonetisation-industry-hit-hard-regain-the-lost-momentum-4495012/" class="block w-full"><img
                  src="./Images/News3.webp"
                  class="h-full w-full rounded-xl scale-100 transform object-cover object-center transition duration-500 ease-out hover:scale-105" /></a>
              <p class="text-xs font-medium uppercase text-gray-400 pb-2">The
                Indian Express: Jan 28, 2017</p>
              <a href="https://indianexpress.com/article/business/budget/budget-2017-18-anant-sardeshmukh-demonetisation-industry-hit-hard-regain-the-lost-momentum-4495012/" class="mt-4 text-xl font-medium">Industry hit hard…it
                could be more than six months before we regain the lost
                momentum: Anant Sardeshmukh</a>
            </div>
            <div class="mb-10 space-y-4">
              <a href="https://indianexpress.com/article/cities/pune/postcards-past-journey-pune-industrial-city-automobile-hub-escaped-fate-mumbai-mills-9004455/" class="block w-full"><img
                  src="./Images/News4.avif"
                  class="h-full w-full rounded-xl scale-100 transform object-cover object-center transition duration-500 ease-out hover:scale-105" /></a>
              <p class="text-xs font-medium uppercase text-gray-400 pb-2">The
                Indian Express: Oct 30, 2023</p>
              <a href="https://indianexpress.com/article/cities/pune/postcards-past-journey-pune-industrial-city-automobile-hub-escaped-fate-mumbai-mills-9004455/" class="mt-4 text-xl font-medium">Postcards from the
                Past: Journey of Pune as an industrial city and how its
                automobile hub escaped the fate of Mumbai mills</a>
            </div>
            <div class="mb-10 space-y-4">
              <a href="https://www.hindustantimes.com/pune-news/increased-interaction-genuine-outreach-helping-solve-problems/story-zd8k1svl0Ecy2Wx5QgJhLO.html" class="block w-full"><img
                  src="http://127.0.0.1:5502/Images/Dr.Anant-with-Awards.avif"
                  class="h-full w-full rounded-xl scale-100 transform object-cover object-center transition duration-500 ease-out hover:scale-105" /></a>
              <p
                class="text-xs font-medium uppercase text-gray-400 pb-2">Hindustan
                Times: Sep 29, 2018</p>
              <a href="https://www.hindustantimes.com/pune-news/increased-interaction-genuine-outreach-helping-solve-problems/story-zd8k1svl0Ecy2Wx5QgJhLO.html" class="mt-4 text-xl font-medium">Increased
                interaction, genuine outreach, helping solve problems</a>
            </div>
            <div class="mb-10 space-y-4">
              <a href="https://www.esakal.com/saptarang/article-write-anant-sardeshmukh-modern-medicine-bitter-or-sweet-390278" class="block w-full"><img
                  src="./Images/News5.avif"
                  class="h-full w-full rounded-xl scale-100 transform object-cover object-center transition duration-500 ease-out hover:scale-105" /></a>
              <p
                class="text-xs font-medium uppercase text-gray-400 pb-2">E-Sakal:
                Dec 27, 2020</p>
              <a href="https://www.esakal.com/saptarang/article-write-anant-sardeshmukh-modern-medicine-bitter-or-sweet-390278" class="mt-4 text-xl font-medium">आधुनिक वैद्यकशास्त्र
                कडू की गोड ? (अनंत सरदेशमुख)</a>
            </div>
          </div>
        </div>
      </section>
      <!-- youtube  -->
      <section data-gjs-highlightable="true" id="products"
        data-gjs-type="default" draggable="true" x-data="{isOpen:false}"
        class="py-20 lg:py-24 bg-gray-50">
        <div data-gjs-highlightable="true" id="ihnb7z" data-gjs-type="default"
          draggable="true"
          class="max-w-7xl mx-auto px-6">

          <div data-gjs-highlightable="true" id="id9733" data-gjs-type="default"
            draggable="true" class="mb-12 sm:mb-14">
            <div data-gjs-highlightable="true" id="i8vo8l"
              data-gjs-type="default" draggable="true">
              <h2 class="text-4xl font-semibold">Youtube</h2>
            </div>

          </div>

          <!-- video -->
          <div>
            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-5 gap-6">
              <div
                class="h-64 col-span-1 overflow-hidden sm:h-80 rounded-xl">
                <div
                  class="w-full h-full overflow-hidden bg-white border group rounded-xl">
                  <div role="cvideo" class="cvideo">
                    <div
                      class="fullHeight"
                      x-data="{ isOpen: false, isVideoPlaying: false }">
                      <!-- Button to open the modal -->
                      <div
                        @click="isOpen = true; isVideoPlaying = true"
                        class="cvideo__unique3">
                        <img
                          loading="lazy"
                          width="586"
                          height="318"
                          alt="video-img"
                          src="./Images/vid1.png"
                          class="cvideo__unique1" />

                        <img
                          loading="lazy"
                          width="64"
                          height="64"
                          alt="Play Button"
                          class="cvideo__unique2"
                          src="https://acdn.inaiways.com/filters:format(webp)/filters:quality(100)/filters:proportion(1)/batchcodingmachine.controlprint.com/play-btn.png" />
                      </div>
                      <!-- Modal backdrop -->
                      <div x-show="isOpen" class="cvideo__unique4">
                        <!-- Modal content -->
                        <div x-show="isOpen">
                          <div class="cvideo__unique5">
                            <span>
                              सॅनिटरी नॅपकिन्सच्या विल्हेवाटीचे जागतिक
                              तंत्रज्ञान विकसित करणारा तरुण स्टार्टअप
                              "पॅडकेअर लॅब"</span>
                          </div>
                          <!-- Video iframe -->
                          <div class="cvideo__unique6">
                            <iframe
                              @click.outside="isOpen = false; isVideoPlaying= false"
                              @keydown.escape.window="isOpen = false; isVideoPlaying= false"
                              x-if="isVideoPlaying"
                              :src="isVideoPlaying ? 'https://www.youtube.com/embed/7U4t18k_VPA?si=fBV-ukktI60cTYv7&autoplay=1' : ''"
                              title="YouTube video player"
                              frameborder="0"
                              allow="autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
                              allowfullscreen></iframe>

                          </div>
                          <div class="cvideo__unique7">
                            <div
                              @click="isOpen = false; isVideoPlaying = false">
                              <svg
                                xmlns="http://www.w3.org/2000/svg"
                                fill="none"
                                viewBox="0 0 24 24"
                                stroke-width="1.5"
                                stroke="currentColor">
                                <path
                                  stroke-linecap="round"
                                  stroke-linejoin="round"
                                  d="M6 18L18 6M6 6l12 12"></path>
                              </svg>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>

              <div
                class="h-64 col-span-1 overflow-hidden sm:h-80 rounded-xl">
                <div
                  class="w-full h-full overflow-hidden bg-white border group rounded-xl">
                  <div role="cvideo" class="cvideo">
                    <div
                      class="fullHeight"
                      x-data="{ isOpen: false, isVideoPlaying: false }">
                      <!-- Button to open the modal -->
                      <div
                        @click="isOpen = true; isVideoPlaying = true"
                        class="cvideo__unique3">
                        <img
                          loading="lazy"
                          width="280"
                          height="318"
                          alt="video-img"
                          src="./Images/vid2.png"
                          class="cvideo__unique1" />
                        <img
                          loading="lazy"
                          width="64"
                          height="64"
                          alt="Play Button"
                          class="cvideo__unique2"
                          src="https://acdn.inaiways.com/filters:format(webp)/filters:quality(100)/filters:proportion(1)/batchcodingmachine.controlprint.com/play-btn.png" />
                      </div>
                      <!-- Modal backdrop -->
                      <div x-show="isOpen" class="cvideo__unique4">
                        <!-- Modal content -->
                        <div x-show="isOpen">
                          <div class="cvideo__unique5">
                            <span>Interview with Karan Korke of The Healthy
                              Binge. Start Up.
                            </span>
                          </div>
                          <!-- Video iframe -->
                          <div class="cvideo__unique6">
                            <iframe
                              @click.outside="isOpen = false; isVideoPlaying= false"
                              @keydown.escape.window="isOpen = false; isVideoPlaying= false"
                              x-if="isVideoPlaying"
                              :src="isVideoPlaying ? 'https://www.youtube.com/embed/2kITpBqv96Q?si=7Rk2veCFID3wE_Ow&autoplay=1' : ''"
                              title="YouTube video player"
                              frameborder="0"
                              allow="autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
                              allowfullscreen></iframe>

                          </div>
                          <div class="cvideo__unique7">
                            <div
                              @click="isOpen = false; isVideoPlaying = false">
                              <svg
                                xmlns="http://www.w3.org/2000/svg"
                                fill="none"
                                viewBox="0 0 24 24"
                                stroke-width="1.5"
                                stroke="currentColor">
                                <path
                                  stroke-linecap="round"
                                  stroke-linejoin="round"
                                  d="M6 18L18 6M6 6l12 12"></path>
                              </svg>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>

              <div
                class="h-64 col-span-1 overflow-hidden sm:h-80 rounded-xl">
                <div
                  class="w-full h-full overflow-hidden bg-white border group rounded-xl">
                  <div role="cvideo" class="cvideo">
                    <div
                      class="fullHeight"
                      x-data="{ isOpen: false, isVideoPlaying: false }">
                      <!-- Button to open the modal -->
                      <div
                        @click="isOpen = true; isVideoPlaying = true"
                        class="cvideo__unique3">
                        <img
                          loading="lazy"
                          width="280"
                          height="318"
                          alt="video-img"
                          src="./Images/vid3.avif"
                          class="cvideo__unique1" />
                        <img
                          loading="lazy"
                          width="64"
                          height="64"
                          alt="Play Button"
                          class="cvideo__unique2"
                          src="https://acdn.inaiways.com/filters:format(webp)/filters:quality(100)/filters:proportion(1)/batchcodingmachine.controlprint.com/play-btn.png" />
                      </div>
                      <!-- Modal backdrop -->
                      <div x-show="isOpen" class="cvideo__unique4">
                        <!-- Modal content -->
                        <div x-show="isOpen">
                          <div class="cvideo__unique5">
                            <span>महाराष्ट्रातील उद्योगांना, इंग्लंड,
                              अमेरिकेच्या बाजारपेठत नेणारा उद्योजक प्रसाद
                              कुलकर्णी !</span>
                          </div>
                          <!-- Video iframe -->
                          <div class="cvideo__unique6">
                            <iframe
                              @click.outside="isOpen = false; isVideoPlaying= false"
                              @keydown.escape.window="isOpen = false; isVideoPlaying= false"
                              x-if="isVideoPlaying"
                              :src="isVideoPlaying ? 'https://www.youtube.com/embed/S2bdMz4rdWo?si=W1qXFO3BJsYRGwx0&autoplay=1' : ''"
                              title="YouTube video player"
                              frameborder="0"
                              allow="autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
                              allowfullscreen></iframe>

                          </div>
                          <div class="cvideo__unique7">
                            <div
                              @click="isOpen = false; isVideoPlaying = false">
                              <svg
                                xmlns="http://www.w3.org/2000/svg"
                                fill="none"
                                viewBox="0 0 24 24"
                                stroke-width="1.5"
                                stroke="currentColor">
                                <path
                                  stroke-linecap="round"
                                  stroke-linejoin="round"
                                  d="M6 18L18 6M6 6l12 12"></path>
                              </svg>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>

              <div
                class="h-64 col-span-1 overflow-hidden sm:h-80 rounded-xl">
                <div
                  class="w-full h-full overflow-hidden bg-white border group rounded-xl">
                  <div role="cvideo" class="cvideo">
                    <div
                      class="fullHeight"
                      x-data="{ isOpen: false, isVideoPlaying: false }">
                      <!-- Button to open the modal -->
                      <div
                        @click="isOpen = true; isVideoPlaying = true"
                        class="cvideo__unique3">
                        <img
                          loading="lazy"
                          width="280"
                          height="318"
                          alt="video-img"
                          src="./Images/vid4.png"
                          class="cvideo__unique1" />
                        <img
                          loading="lazy"
                          width="64"
                          height="64"
                          alt="Play Button"
                          class="cvideo__unique2"
                          src="https://acdn.inaiways.com/filters:format(webp)/filters:quality(100)/filters:proportion(1)/batchcodingmachine.controlprint.com/play-btn.png" />
                      </div>
                      <!-- Modal backdrop -->
                      <div x-show="isOpen" class="cvideo__unique4">
                        <!-- Modal content -->
                        <div x-show="isOpen">
                          <div class="cvideo__unique5">
                            <span>इलेक्ट्रॉनिक क्षेत्रातील प्रथम पिढीतील एक
                              यशस्वी उदयोजिका मानसी बिडकर बरोबर बातचीत.</span>
                          </div>
                          <!-- Video iframe -->
                          <div class="cvideo__unique6">
                            <iframe
                              @click.outside="isOpen = false; isVideoPlaying= false"
                              @keydown.escape.window="isOpen = false; isVideoPlaying= false"
                              x-if="isVideoPlaying"
                              :src="isVideoPlaying ? 'https://www.youtube.com/embed/qfQFNSnNIZI?si=ZHzKqNtXS7Cc7lba&autoplay=1' : ''"
                              title="YouTube video player"
                              frameborder="0"
                              allow="autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
                              allowfullscreen></iframe>

                          </div>
                          <div class="cvideo__unique7">
                            <div
                              @click="isOpen = false; isVideoPlaying = false">
                              <svg
                                xmlns="http://www.w3.org/2000/svg"
                                fill="none"
                                viewBox="0 0 24 24"
                                stroke-width="1.5"
                                stroke="currentColor">
                                <path
                                  stroke-linecap="round"
                                  stroke-linejoin="round"
                                  d="M6 18L18 6M6 6l12 12"></path>
                              </svg>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>

              <div
                class="h-64 col-span-1 overflow-hidden sm:h-80 rounded-xl">
                <div
                  class="w-full h-full overflow-hidden bg-white border group rounded-xl">
                  <div role="cvideo" class="cvideo">
                    <div
                      class="fullHeight"
                      x-data="{ isOpen: false, isVideoPlaying: false }">
                      <!-- Button to open the modal -->
                      <div
                        @click="isOpen = true; isVideoPlaying = true"
                        class="cvideo__unique3">
                        <img
                          loading="lazy"
                          width="280"
                          height="318"
                          alt="video-img"
                          src="./Images/vid5.avif"
                          class="cvideo__unique1" />
                        <img
                          loading="lazy"
                          width="64"
                          height="64"
                          alt="Play Button"
                          class="cvideo__unique2"
                          src="https://acdn.inaiways.com/filters:format(webp)/filters:quality(100)/filters:proportion(1)/batchcodingmachine.controlprint.com/play-btn.png" />
                      </div>
                      <!-- Modal backdrop -->
                      <div x-show="isOpen" class="cvideo__unique4">
                        <!-- Modal content -->
                        <div x-show="isOpen">
                          <div class="cvideo__unique5">
                            <span>Akshita Sachdeva, social startup assisting the
                              visually -impaired. ! know her
                              innovation"KIBO"</span>
                          </div>
                          <!-- Video iframe -->
                          <div class="cvideo__unique6">
                            <iframe
                              @click.outside="isOpen = false; isVideoPlaying= false"
                              @keydown.escape.window="isOpen = false; isVideoPlaying= false"
                              x-if="isVideoPlaying"
                              :src="isVideoPlaying ? 'https://www.youtube.com/embed/inbog1wKcN0?si=2oclK0-VVy0meN98&autoplay=1' : ''"
                              title="YouTube video player"
                              frameborder="0"
                              allow="autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
                              allowfullscreen></iframe>

                          </div>
                          <div class="cvideo__unique7">
                            <div
                              @click="isOpen = false; isVideoPlaying = false">
                              <svg
                                xmlns="http://www.w3.org/2000/svg"
                                fill="none"
                                viewBox="0 0 24 24"
                                stroke-width="1.5"
                                stroke="currentColor">
                                <path
                                  stroke-linecap="round"
                                  stroke-linejoin="round"
                                  d="M6 18L18 6M6 6l12 12"></path>
                              </svg>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="group max-w-96 mx-auto mt-10 lg:mt-20">
            <a href="https://www.youtube.com/@entrepreneurshipenterprise3931" class="border-3 inline-flex items-center justify-center gap-3 rounded-xl text-white bg-purple-700 hover:bg-purple-900 px-6 py-3 text-lg font-medium text-black shadow-lg transition duration-300">
              <span>Subscribe My Channel Now</span>
              <div class="relative">
                <svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" fill="currentColor" stroke="white" stroke-width="1" class="bi bi-arrow-up-right w-5 group-hover:rotate-90 transition ease-in-out duration-500 font-extrabold" viewBox="0 0 16 16">
                  <path fill-rule="evenodd" d="M14 2.5a.5.5 0 0 0-.5-.5h-6a.5.5 0 0 0 0 1h4.793L2.146 13.146a.5.5 0 0 0 .708.708L13 3.707V8.5a.5.5 0 0 0 1 0z"></path>
                </svg>
              </div>
            </a>
          </div>
        </div>

      </section>

      <!-- testimonials  -->
      <section class="py-20 lg:py-24 bg-zinc-900">
        <div class="max-w-7xl mx-auto px-6">
          <!-- Section Title -->
          <div class="mb-12 text-center">
            <h2 class="text-4xl font-semibold text-white">Testimonials</h2>
          </div>
          <!-- Testimonials Grid -->
          <div class="grid gap-6 md:grid-cols-2 lg:grid-cols-3">
            <!-- Testimonial Item 1 -->
            <div
              class="flex flex-col justify-between bg-zinc-900 md:p-6 rounded-2xl">

              <div class="mb-4">
                <div class="flex justify-between">
                  <div>
                    <svg xmlns="http://www.w3.org/2000/svg" width="40"
                      height="40" fill="currentColor"
                      class="bi bi-quote text-white" viewBox="0 0 16 16">
                      <path
                        d="M12 12a1 1 0 0 0 1-1V8.558a1 1 0 0 0-1-1h-1.388q0-.527.062-1.054.093-.558.31-.992t.559-.683q.34-.279.868-.279V3q-.868 0-1.52.372a3.3 3.3 0 0 0-1.085.992 4.9 4.9 0 0 0-.62 1.458A7.7 7.7 0 0 0 9 7.558V11a1 1 0 0 0 1 1zm-6 0a1 1 0 0 0 1-1V8.558a1 1 0 0 0-1-1H4.612q0-.527.062-1.054.094-.558.31-.992.217-.434.559-.683.34-.279.868-.279V3q-.868 0-1.52.372a3.3 3.3 0 0 0-1.085.992 4.9 4.9 0 0 0-.62 1.458A7.7 7.7 0 0 0 3 7.558V11a1 1 0 0 0 1 1z" />
                    </svg>
                  </div>
                  <div>
                    <svg xmlns="http://www.w3.org/2000/svg" width="40"
                      height="40"
                      fill="currentColor"
                      class="bi bi-linkedin w-8 text-blue-200"
                      viewBox="0 0 16 16">
                      <path
                        d="M0 1.146C0 .513.526 0 1.175 0h13.65C15.474 0 16 .513 16 1.146v13.708c0 .633-.526 1.146-1.175 1.146H1.175C.526 16 0 15.487 0 14.854zm4.943 12.248V6.169H2.542v7.225zm-1.2-8.212c.837 0 1.358-.554 1.358-1.248-.015-.709-.52-1.248-1.342-1.248S2.4 3.226 2.4 3.934c0 .694.521 1.248 1.327 1.248zm4.908 8.212V9.359c0-.216.016-.432.08-.586.173-.431.568-.878 1.232-.878.869 0 1.216.662 1.216 1.634v3.865h2.401V9.25c0-2.22-1.184-3.252-2.764-3.252-1.274 0-1.845.7-2.165 1.193v.025h-.016l.016-.025V6.169h-2.4c.03.678 0 7.225 0 7.225z" />
                    </svg>
                  </div>
                </div>
                <h3 class="text-lg text-gray-200 mt-4">Anant Sardeshmukh is a
                  very
                  professional man. Hats off to his achievements.</h3>
              </div>
              <div class>
                <h4 class="text-lg font-semibold text-gray-100">Nitin Ahire</h4>
                <p class="text-sm text-gray-300">Prasanna Enterprises &
                  Managements Systems <br>(Industrial Projects Management
                  Consultant) </p>
              </div>
            </div>
            <!-- Testimonial Item 2 -->
            <div
              class="flex flex-col justify-between bg-zinc-900 md:p-6 rounded-2xl">
              <div class="mb-4">
                <div class="flex justify-between">
                  <div>
                    <svg xmlns="http://www.w3.org/2000/svg" width="40"
                      height="40" fill="currentColor"
                      class="bi bi-quote text-white" viewBox="0 0 16 16">
                      <path
                        d="M12 12a1 1 0 0 0 1-1V8.558a1 1 0 0 0-1-1h-1.388q0-.527.062-1.054.093-.558.31-.992t.559-.683q.34-.279.868-.279V3q-.868 0-1.52.372a3.3 3.3 0 0 0-1.085.992 4.9 4.9 0 0 0-.62 1.458A7.7 7.7 0 0 0 9 7.558V11a1 1 0 0 0 1 1zm-6 0a1 1 0 0 0 1-1V8.558a1 1 0 0 0-1-1H4.612q0-.527.062-1.054.094-.558.31-.992.217-.434.559-.683.34-.279.868-.279V3q-.868 0-1.52.372a3.3 3.3 0 0 0-1.085.992 4.9 4.9 0 0 0-.62 1.458A7.7 7.7 0 0 0 3 7.558V11a1 1 0 0 0 1 1z" />
                    </svg>
                  </div>
                  <div>
                    <svg xmlns="http://www.w3.org/2000/svg" width="40"
                      height="40"
                      fill="currentColor"
                      class="bi bi-linkedin w-8 text-blue-200"
                      viewBox="0 0 16 16">
                      <path
                        d="M0 1.146C0 .513.526 0 1.175 0h13.65C15.474 0 16 .513 16 1.146v13.708c0 .633-.526 1.146-1.175 1.146H1.175C.526 16 0 15.487 0 14.854zm4.943 12.248V6.169H2.542v7.225zm-1.2-8.212c.837 0 1.358-.554 1.358-1.248-.015-.709-.52-1.248-1.342-1.248S2.4 3.226 2.4 3.934c0 .694.521 1.248 1.327 1.248zm4.908 8.212V9.359c0-.216.016-.432.08-.586.173-.431.568-.878 1.232-.878.869 0 1.216.662 1.216 1.634v3.865h2.401V9.25c0-2.22-1.184-3.252-2.764-3.252-1.274 0-1.845.7-2.165 1.193v.025h-.016l.016-.025V6.169h-2.4c.03.678 0 7.225 0 7.225z" />
                    </svg>
                  </div>
                </div>
                <h3 class="text-lg text-gray-200 mt-4">Anant is a proffessional
                  in
                  business finance and and an management expert</h3>
              </div>
              <div class>
                <h4 class="text-lg font-semibold text-gray-100">Cyrus
                  Golvala</h4>
                <p class="text-sm text-gray-300">Jobtrack Mgmt Services Pvt Ltd.
                  <br> (Associate Consultant) </p>

              </div>
            </div>
            <!-- Testimonial Item 3 -->
            <div
              class="flex flex-col justify-between bg-zinc-900 md:p-6 rounded-2xl">
              <div class="mb-4">
                <div class="flex justify-between">
                  <div>
                    <svg xmlns="http://www.w3.org/2000/svg" width="40"
                      height="40" fill="currentColor"
                      class="bi bi-quote text-white" viewBox="0 0 16 16">
                      <path
                        d="M12 12a1 1 0 0 0 1-1V8.558a1 1 0 0 0-1-1h-1.388q0-.527.062-1.054.093-.558.31-.992t.559-.683q.34-.279.868-.279V3q-.868 0-1.52.372a3.3 3.3 0 0 0-1.085.992 4.9 4.9 0 0 0-.62 1.458A7.7 7.7 0 0 0 9 7.558V11a1 1 0 0 0 1 1zm-6 0a1 1 0 0 0 1-1V8.558a1 1 0 0 0-1-1H4.612q0-.527.062-1.054.094-.558.31-.992.217-.434.559-.683.34-.279.868-.279V3q-.868 0-1.52.372a3.3 3.3 0 0 0-1.085.992 4.9 4.9 0 0 0-.62 1.458A7.7 7.7 0 0 0 3 7.558V11a1 1 0 0 0 1 1z" />
                    </svg>
                  </div>
                  <div>
                    <svg xmlns="http://www.w3.org/2000/svg" width="40"
                      height="40"
                      fill="currentColor"
                      class="bi bi-linkedin w-8 text-blue-200"
                      viewBox="0 0 16 16">
                      <path
                        d="M0 1.146C0 .513.526 0 1.175 0h13.65C15.474 0 16 .513 16 1.146v13.708c0 .633-.526 1.146-1.175 1.146H1.175C.526 16 0 15.487 0 14.854zm4.943 12.248V6.169H2.542v7.225zm-1.2-8.212c.837 0 1.358-.554 1.358-1.248-.015-.709-.52-1.248-1.342-1.248S2.4 3.226 2.4 3.934c0 .694.521 1.248 1.327 1.248zm4.908 8.212V9.359c0-.216.016-.432.08-.586.173-.431.568-.878 1.232-.878.869 0 1.216.662 1.216 1.634v3.865h2.401V9.25c0-2.22-1.184-3.252-2.764-3.252-1.274 0-1.845.7-2.165 1.193v.025h-.016l.016-.025V6.169h-2.4c.03.678 0 7.225 0 7.225z" />
                    </svg>
                  </div>
                </div>
                <h3 class="text-lg text-gray-200 mt-4">Anant sir was really a
                  dream
                  boss as his leadership skills always motivated me to deliver
                  best of me.</h3>
              </div>
              <div class>
                <h4 class="text-lg font-semibold text-gray-100">
                  MUKUND DHOLE</h4>
                <p class="text-sm text-gray-300">ELECTRONICA FINANCE Ltd. <br>
                  (Vice President)</p>
              </div>
            </div>
          </div>
        </div>
      </section>

      <div class="relative py-20 lg:py-60">
        <!-- Background Image -->
        <div class="absolute inset-0 h-full">
          <img src="./Images/Anant-Sirdeshmukh-Dark.jpg"
            alt="Robin Sharma's Mission" class="h-full w-full object-cover" />
        </div>

        <!-- Content -->
        <div class="relative z-10 mx-auto max-w-4xl px-6 text-center">
          <h2 class="mb-6 text-white text-2xl lg:text-4xl">
            “To help people and organizations around<br
              class="hidden lg:inline" />
            the world Lead Without a Title.”
          </h2>
          <h4 class="text-white text-lg lg:text-xl">Dr. Anant Sardeshmukh's
            Mission Statement</h4>
        </div>
      </div>
      <!-- cta  -->
      <section class="bg-gray-100 py-20">
        <div
          class="mx-auto flex max-w-7xl flex-col lg:items-center justify-between px-6 text-left lg:flex-row gap-10">
          <div class="lg:w-1/2">
            <h2 class="text-2xl md:text-3xl font-semibold mb-4">Explore
              opportunities connect for new ventures!</h2>
            <p class="text-gray-800">Embark on a journey of possibilities and
              connect with me for new ventures, where innovation meets
              opportunity, and together, we craft success stories.</p>
          </div>
          <div class="group">
            <a href="/contact.html"
              class="border-3 inline-flex items-center justify-center gap-3 rounded-xl text-white bg-purple-700 hover:bg-purple-900 px-6 py-3 text-lg font-medium text-black shadow-lg transition duration-300 w-full">
              Stay Connected <div class="relative">
                <svg xmlns="http://www.w3.org/2000/svg" width="40" height="40"
                  fill="currentColor" stroke="white" stroke-width="1"
                  class="bi bi-arrow-up-right w-5 group-hover:rotate-90 transition ease-in-out duration-500 font-extrabold"
                  viewBox="0 0 16 16">
                  <path fill-rule="evenodd"
                    d="M14 2.5a.5.5 0 0 0-.5-.5h-6a.5.5 0 0 0 0 1h4.793L2.146 13.146a.5.5 0 0 0 .708.708L13 3.707V8.5a.5.5 0 0 0 1 0z"></path>
                </svg>
              </div> </a>

          </div>
        </div>
      </section>
      <!-- footer  -->
      <footer
        class="bg-cover bg-center text-white bg-zinc-900 pt-20 lg:pt-24 pb-10 lg:pb-14">
        <div class="max-w-7xl px-6 mx-auto">
          <!-- Footer Top -->
          <div
            class="flex flex-col lg:flex-row lg:gap-20 justify-center gap-4">
            <!-- Left Column -->
            <div class="w-full lg:w-2/5">
              <div>
                <h2 class="text-2xl md:text-3xl font-semibold mb-4">
                  Why Dr. Anant Sardeshmukh is a Leader to Leaders
                </h2>
                <p class="mb-4 text-gray-100">
                  Dr. Sardeshmukh, a man who always traversed untrodden path
                  with a confidence of success and achievement, has contributed
                  significantly to the organizations of his association. He is a
                  man often credited for numerous “First-Time” initiatives. It
                  was his visionary efforts which enhanced the visibility.
                </p>
              </div>
            </div>
            <!-- middle column  -->
            <!-- USEFUL LINKS Section -->
            <div class="w-full lg:w-1/5 sm:mt-0 text-left">
              <span
                class="mt-4 mb-4 text-xl font-medium text-white sm:mt-0">Useful
                Links</span>
              <ul class="mt-4">
                <li><a id="iyl5ngj" href="/home.html"
                    class="block pb-3 font-normal text-white underline-offset-4 hover:text-gray-200 hover:underline">Home</a></li>
                <li><a id="ihly1gg" href="/about.html"
                    class="block pb-3 font-normal text-white underline-offset-4 hover:text-gray-200 hover:underline">About</a></li>
                <li><a id="it1f84j" href="/services.html"
                    class="block pb-3 font-normal text-white underline-offset-4 hover:text-gray-200 hover:underline">Services</a></li>
                <li><a id="it1f84j" href="/books.html"
                    class="block pb-3 font-normal text-white underline-offset-4 hover:text-gray-200 hover:underline">Books
                    and Blogs
                  </a></li>
                <li><a id="io9pl49" href="/contact.html"
                    class="block pb-3 font-normal text-white underline-offset-4 hover:text-gray-200 hover:underline">Contact</a></li>
              </ul>
            </div>
            <!-- Right Column -->
            <div class="w-full lg:w-1/5 py-2 lg:py-0">
              <h3 class="text-xl font-medium mb-4">Stay connected
              </h3>
              <div
                class="flex flex-col gap-6">
                <a href="https://www.facebook.com/anant.sardeshmukh/"
                  class="group" target="_blank">
                  <div class="flex gap-4">
                    <div>
                      <svg xmlns="http://www.w3.org/2000/svg" width="25"
                        height="25"
                        fill="currentColor" class="bi bi-facebook"
                        viewBox="0 0 16 16">
                        <path
                          d="M16 8.049c0-4.446-3.582-8.05-8-8.05C3.58 0-.002 3.603-.002 8.05c0 4.017 2.926 7.347 6.75 7.951v-5.625h-2.03V8.05H6.75V6.275c0-2.017 1.195-3.131 3.022-3.131.876 0 1.791.157 1.791.157v1.98h-1.009c-.993 0-1.303.621-1.303 1.258v1.51h2.218l-.354 2.326H9.25V16c3.824-.604 6.75-3.934 6.75-7.951" />
                      </svg>
                    </div>
                    <div>
                      <div class="group-hover:underline">Facebook</div>
                    </div>
                  </div>
                </a>
                <a href="https://twitter.com/Anantsardeshmuk" class="group"
                  target="_blank">
                  <div class="flex gap-4">
                    <div>
                      <svg xmlns="http://www.w3.org/2000/svg" width="25"
                        height="25" fill="currentColor"
                        class="bi bi-twitter-x"
                        viewBox="0 0 16 16">
                        <path
                          d="M12.6.75h2.454l-5.36 6.142L16 15.25h-4.937l-3.867-5.07-4.425 5.07H.316l5.733-6.57L0 .75h5.063l3.495 4.633L12.601.75Zm-.86 13.028h1.36L4.323 2.145H2.865z"></path>
                      </svg>
                    </div>
                    <div>
                      <div class="group-hover:underline">Twitter</div>
                    </div>
                  </div>
                </a>
                <a
                  href="https://www.linkedin.com/in/dr-anant-sardeshmukh-a696ab7/"
                  class="group" target="_blank">
                  <div class="flex gap-4">
                    <div>
                      <svg xmlns="http://www.w3.org/2000/svg" width="25"
                        height="25"
                        fill="currentColor" class="bi bi-linkedin"
                        viewBox="0 0 16 16">
                        <path
                          d="M0 1.146C0 .513.526 0 1.175 0h13.65C15.474 0 16 .513 16 1.146v13.708c0 .633-.526 1.146-1.175 1.146H1.175C.526 16 0 15.487 0 14.854zm4.943 12.248V6.169H2.542v7.225zm-1.2-8.212c.837 0 1.358-.554 1.358-1.248-.015-.709-.52-1.248-1.342-1.248S2.4 3.226 2.4 3.934c0 .694.521 1.248 1.327 1.248zm4.908 8.212V9.359c0-.216.016-.432.08-.586.173-.431.568-.878 1.232-.878.869 0 1.216.662 1.216 1.634v3.865h2.401V9.25c0-2.22-1.184-3.252-2.764-3.252-1.274 0-1.845.7-2.165 1.193v.025h-.016l.016-.025V6.169h-2.4c.03.678 0 7.225 0 7.225z" />
                      </svg>
                    </div>
                    <div>
                      <div class="group-hover:underline">Linkedin</div>
                    </div>
                  </div>
                </a>
                <a
                  href="https://www.youtube.com/@entrepreneurshipenterprise3931"
                  class="group" target="_blank">
                  <div class="flex gap-4">
                    <div>
                      <svg xmlns="http://www.w3.org/2000/svg" width="25"
                        height="25" fill="currentColor"
                        class="bi bi-youtube"
                        viewBox="0 0 16 16">
                        <path
                          d="M8.051 1.999h.089c.822.003 4.987.033 6.11.335a2.01 2.01 0 0 1 1.415 1.42c.101.38.172.883.22 1.402l.01.104.022.26.008.104c.065.914.073 1.77.074 1.957v.075c-.001.194-.01 1.108-.082 2.06l-.008.105-.009.104c-.05.572-.124 1.14-.235 1.558a2.01 2.01 0 0 1-1.415 1.42c-1.16.312-5.569.334-6.18.335h-.142c-.309 0-1.587-.006-2.927-.052l-.17-.006-.087-.004-.171-.007-.171-.007c-1.11-.049-2.167-.128-2.654-.26a2.01 2.01 0 0 1-1.415-1.419c-.111-.417-.185-.986-.235-1.558L.09 9.82l-.008-.104A31 31 0 0 1 0 7.68v-.123c.002-.215.01-.958.064-1.778l.007-.103.003-.052.008-.104.022-.26.01-.104c.048-.519.119-1.023.22-1.402a2.01 2.01 0 0 1 1.415-1.42c.487-.13 1.544-.21 2.654-.26l.17-.007.172-.006.086-.003.171-.007A100 100 0 0 1 7.858 2zM6.4 5.209v4.818l4.157-2.408z"></path>
                      </svg>
                    </div>
                    <div>
                      <div class="group-hover:underline">Youtube</div>
                    </div>
                  </div>
                </a>
              </div>
            </div>

          </div>

          <!-- Footer Bottom -->
          <div class="mt-14 text-center text-sm space-y-2">
            <div>© Inaiways Pvt. Ltd. All rights reserved.</div>

          </div>
        </div>
      </footer>

    </div>
  </body>
</html>
