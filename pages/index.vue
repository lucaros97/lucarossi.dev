<template>
  <div class="h-full text-black antialiased bg-black bg-no-repeat bg-top bg-contain">
    <div class="bg-black">
      <header class="relative max-w-screen-xl mx-auto h-24 p-5 md:flex md:justify-between md:items-center">
          <!-- logo -->
          <a href="/" title="back to homepage" class="logo">
            <svg class="dark:text-white transform scale-75" width="52" height="52" xmlns="http://www.w3.org/2000/svg" fill="#fff" xmlns:v="https://vecta.io/nano">
            <path d="M52 39a13.02 13.02 0 0 1-13-13 13.02 13.02 0 0 1 13-13v26zM26 13L13 26l13 13V13z"></path>
            <path d="M13 39L0 52V13L13 0V39Z"></path>
            </svg>
          </a>
          <nav class="hidden md:block py-1">
            
            <ul class="text-right">
              <li class="inline-block mr-5">
                <a href="/about/" class="font-bold transition-colors dark:hover:text-yellow-200 hover:text-black
                dark:text-white text-gray-200 ">about</a>
              </li>
              <li class="inline-block mr-5">
                <a href="/works/" class="font-bold transition-colors dark:hover:text-yellow-200 hover:text-black
                dark:text-white text-gray-200 ">works</a>
              </li>
              <li class="inline-block mr-5">
                <a href="/posts/" class="font-bold transition-colors dark:hover:text-yellow-200 hover:text-black
                dark:text-white text-gray-200 ">blog</a>
              </li>
              <li class="inline-block">
                <a href="mailto:hello@lucarossi.dev?subject=Contact from lucarossi.dev&amp;" title="get in touch" target="_blank" rel="noreferrer" class="text-gray-800 dark:text-yellow-300 py-2 px-5 rounded-full font-bold border-2 border-gray-900 dark:border-yellow-100 border-opacity-20 transition-colors hover:border-opacity-100"><span>Get in touch</span>
                </a>
              </li>
            </ul>
          </nav>
      </header>
    </div>
    <section class="pt-8 md:pt-32 bg-black">
      <div class="max-w-screen-xl m-auto px-5">
          
          <img src="https://res.cloudinary.com/kailoon/image/upload/c_scale,dpr_auto,q_auto,w_64/v1610896577/kailoon.com/avatar_ce8dgk.webp" class="rounded-full w-16 h-16 mb-5" alt="my avatar" width="64" height="64">

          <div class="font-black grid grid-cols-12 gap-5">
            <div class="col-start-1 col-end-12 lg:col-end-10">
              <h1 class="text-5xl md:text-7xl tracking-tighter font-bold md:mb-3 bg-clip-text bg-gradient-to-br text-transparent from-orange-400 to-pink-600">Hi, I’m Luca. I’m a full-stack web developer and digital entrepreneur </h1>
              
            </div>
          </div>
      </div>
    </section>
    <main id="content" role="main">
    
  <section id="works" class="pb-24 md:pb-36">
      <div class="px-5 max-w-screen-xl lg:mx-auto">
        <div class="py-10 grid gap-x-2 gap-y-5 sm:gap-y-2 grid-cols-1 md:grid-cols-2 md:grid-flow-row-dense">
          <div class="md:col-span-3">
            <span class="block text-xl tracking-tight text-gray-700 dark:text-gray-300 mb-10 md:w-2/3">
            Over the years, I have the honour to collaborate with clients range from startups to SME, some of them has grown successfully or being acquired. Below are some of the works I've involved with.
            </span>
          </div>

          <a href="#" title="Momento" class="flex flex-col justify-between post bg-gray-800 relative md:transform md:hover:-translate-y-2 md:transition-transform">
            <article style="background-color: #D1FAE5">
            <header class="p-5 lg:p-8">
              <span class="text-gray-800 text-3xl tracking-tighter font-bold block">Momento</span>
              <span class="text-gray-600 text-base font-normal">Domain monitoring</span>
            </header>
            <picture class="block p-5 lg:p-8">
            <img src="https://d1d55ef3n2qmx.cloudfront.net/1da312e9-f48c-4aca-8e48-69e0aef7f56d/images/landing-dashboard.png" alt="Momento" height="200" sizes="100vw">
            </picture>
            </article>
          </a>
        
      
        
          <a href="https://kailoon.com/works/envato-marketplaces-logo/" title="view Envato Marketplaces" class="flex flex-col justify-between post bg-gray-800 relative md:transform md:hover:-translate-y-2 md:transition-transform">
            <article style="background-color: #FFF">
            <header class="p-5 lg:p-8 h-24 md:h-48">
              <span class="text-gray-800 text-3xl tracking-tighter font-bold block">Envato Marketplaces</span>
              <span class="text-gray-600 text-base font-normal">Logo Design</span>
            </header>
            <picture class="block">
            <img src="~/assets/motionwall.png" alt="Momento" height="200" sizes="100vw">
            </picture>
            </article>
          </a>
        </div>
      </div>
    </section>
  </main>
  </div>
</template>

<script>
export default {}
</script>
<style>
  body, #__nuxt, #__layout {
    width: 100%;
    height: 100%;
    margin: 0;
    padding: 0;
  }
</style>