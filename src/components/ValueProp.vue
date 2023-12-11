<template>

<div class="bg-white py-28">
  <div class="mx-auto max-w-7xl px-6 lg:px-8">
    <div class="mx-auto max-w-2xl lg:mx-0 lg:max-w-none">
      <h2 class="text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl">What We Do</h2>
      <div class="mt-6 flex flex-col gap-x-8 gap-y-20 lg:flex-row">
        <div class="lg:w-full lg:max-w-2xl lg:flex-auto">
          <p class="text-xl leading-8 text-gray-600">We're a venture studio that works with corporations to realize innovation through new venture creation. If we and our investors believe a problem is worth solving in a big enough market, we'll be the first ones to write a check.</p>
          <p class="mt-10 max-w-xl text-base leading-7 text-gray-700">Corporations hold a unique source of insights that if commercialized with the right team and incentives, magic can happen. But ideas are worthless without execution. So, we're flipping the model
          to make it easier for corporations to launch high-growth technology startups.</p>
          <div class="mt-10 flex items-center gap-x-6">
            <router-link to="/application" class="rounded-md bg-indigo-600 px-3.5 py-2.5 text-sm font-semibold text-white shadow-sm hover:bg-indigo-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600">Submit an Application</router-link>
          </div>
          <p class="mt-4 max-w-xl text-sm italic leading-5 text-gray-500">If you application is selected we'll reach out to put a mutual nondisclosure agreement in place before talking details.</p>
        </div>
        <div class="lg:flex lg:flex-auto lg:justify-center">
          <dl class="w-64 space-y-8 xl:w-80">
            <div class="flex flex-col-reverse gap-y-4">
              <dt class="text-base leading-7 text-gray-600">Time to launch</dt>
              <dd class="text-5xl font-semibold tracking-tight text-gray-900">4-6 Weeks</dd>
            </div>
            <div class="flex flex-col-reverse gap-y-4">
              <dt class="text-base leading-7 text-gray-600">Investment Capital</dt>
              <dd class="text-5xl font-semibold tracking-tight text-gray-900">$1,000,000*</dd>
            </div>
            <div class="flex flex-col-reverse gap-y-4">
              <dt class="text-base leading-7 text-gray-600">Co-Founders</dt>
              <dd class="text-5xl font-semibold tracking-tight text-gray-900">2+</dd>
            </div>
            <p class="mt-4 max-w-xl text-sm italic leading-5 text-gray-500">*Represents total capital invested in a new startup. Hivernate will invest up to $500k with the remaining coming from the corproate partner in exchange for equity.</p>
          </dl>
        </div>
      </div>
    </div>
  </div>
</div>


<div class="relative isolate overflow-hidden bg-gray-900 py-24 sm:py-18">
  <img src="https://images.unsplash.com/photo-1521737604893-d14cc237f11d?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&crop=focalpoint&fp-y=.8&w=2830&h=1500&q=80&blend=111827&sat=-100&exp=15&blend-mode=multiply" alt="" class="absolute inset-0 -z-10 h-full w-full object-cover object-right md:object-center">
  <div class="hidden sm:absolute sm:-top-10 sm:right-1/2 sm:-z-10 sm:mr-10 sm:block sm:transform-gpu sm:blur-3xl">
    <div class="aspect-[1097/845] w-[68.5625rem] bg-gradient-to-tr from-[#ff4694] to-[#776fff] opacity-20" style="clip-path: polygon(74.1% 44.1%, 100% 61.6%, 97.5% 26.9%, 85.5% 0.1%, 80.7% 2%, 72.5% 32.5%, 60.2% 62.4%, 52.4% 68.1%, 47.5% 58.3%, 45.2% 34.5%, 27.5% 76.7%, 0.1% 64.9%, 17.9% 100%, 27.6% 76.8%, 76.1% 97.7%, 74.1% 44.1%)"></div>
  </div>
  <div class="absolute -top-52 left-1/2 -z-10 -translate-x-1/2 transform-gpu blur-3xl sm:top-[-28rem] sm:ml-16 sm:translate-x-0 sm:transform-gpu">
    <div class="aspect-[1097/845] w-[68.5625rem] bg-gradient-to-tr from-[#ff4694] to-[#776fff] opacity-20" style="clip-path: polygon(74.1% 44.1%, 100% 61.6%, 97.5% 26.9%, 85.5% 0.1%, 80.7% 2%, 72.5% 32.5%, 60.2% 62.4%, 52.4% 68.1%, 47.5% 58.3%, 45.2% 34.5%, 27.5% 76.7%, 0.1% 64.9%, 17.9% 100%, 27.6% 76.8%, 76.1% 97.7%, 74.1% 44.1%)"></div>
  </div>
  <div class="mx-auto max-w-7xl px-6 lg:px-8">
    <div class="mx-auto max-w-2xl lg:mx-0">
      <h2 class="text-4xl font-bold tracking-tight text-white sm:text-6xl">Our Approach</h2>
      <p class="mt-6 text-lg leading-8 text-gray-300">We are next generation venture capital firm, with a history of helping corporations overcome the innovator's dilemma. As corporate innovators and entrepreneurs ourselves, we understand how to move quickly while mitigating risk to achieve risk adjusted returns. </p>
    </div>
    <div class="mx-auto mt-16 grid max-w-2xl grid-cols-1 gap-6 sm:mt-20 lg:mx-0 lg:max-w-none lg:grid-cols-3 lg:gap-8">
      <div class="flex gap-x-4 rounded-xl bg-white/5 p-6 ring-1 ring-inset ring-white/10">
        <svg class="h-7 w-5 flex-none text-indigo-400" viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
          <path fill-rule="evenodd" d="M2 3.5A1.5 1.5 0 013.5 2h1.148a1.5 1.5 0 011.465 1.175l.716 3.223a1.5 1.5 0 01-1.052 1.767l-.933.267c-.41.117-.643.555-.48.95a11.542 11.542 0 006.254 6.254c.395.163.833-.07.95-.48l.267-.933a1.5 1.5 0 011.767-1.052l3.223.716A1.5 1.5 0 0118 15.352V16.5a1.5 1.5 0 01-1.5 1.5H15c-1.149 0-2.263-.15-3.326-.43A13.022 13.022 0 012.43 8.326 13.019 13.019 0 012 5V3.5z" clip-rule="evenodd" />
        </svg>
        <div class="text-base leading-7">
          <h3 class="font-semibold text-white">Synthesize</h3>
          <p class="mt-2 text-gray-300">We take promising business challenges and opportunities and quickly determine if there is merit pursuing a new venture. We look for corporate partners who will also be likely first customers.</p>
        </div>
      </div>
      <div class="flex gap-x-4 rounded-xl bg-white/5 p-6 ring-1 ring-inset ring-white/10">
        <svg class="h-7 w-5 flex-none text-indigo-400" viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
          <path fill-rule="evenodd" d="M7.171 4.146l1.947 2.466a3.514 3.514 0 011.764 0l1.947-2.466a6.52 6.52 0 00-5.658 0zm8.683 3.025l-2.466 1.947c.15.578.15 1.186 0 1.764l2.466 1.947a6.52 6.52 0 000-5.658zm-3.025 8.683l-1.947-2.466c-.578.15-1.186.15-1.764 0l-1.947 2.466a6.52 6.52 0 005.658 0zM4.146 12.83l2.466-1.947a3.514 3.514 0 010-1.764L4.146 7.171a6.52 6.52 0 000 5.658zM5.63 3.297a8.01 8.01 0 018.738 0 8.031 8.031 0 012.334 2.334 8.01 8.01 0 010 8.738 8.033 8.033 0 01-2.334 2.334 8.01 8.01 0 01-8.738 0 8.032 8.032 0 01-2.334-2.334 8.01 8.01 0 010-8.738A8.03 8.03 0 015.63 3.297zm5.198 4.882a2.008 2.008 0 00-2.243.407 1.994 1.994 0 00-.407 2.243 1.993 1.993 0 00.992.992 2.008 2.008 0 002.243-.407c.176-.175.31-.374.407-.585a2.008 2.008 0 00-.407-2.243 1.993 1.993 0 00-.585-.407z" clip-rule="evenodd" />
        </svg>
        <div class="text-base leading-7">
          <h3 class="font-semibold text-white">Invest</h3>
          <p class="mt-2 text-gray-300">Business opportunities that have widely-held jobs to be done, a large market, and interested first customer are provided up to $1 million in seed funding.</p>
        </div>
      </div>
      <div class="flex gap-x-4 rounded-xl bg-white/5 p-6 ring-1 ring-inset ring-white/10">
        <svg class="h-7 w-5 flex-none text-indigo-400" viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
          <path fill-rule="evenodd" d="M2 3.5A1.5 1.5 0 013.5 2h9A1.5 1.5 0 0114 3.5v11.75A2.75 2.75 0 0016.75 18h-12A2.75 2.75 0 012 15.25V3.5zm3.75 7a.75.75 0 000 1.5h4.5a.75.75 0 000-1.5h-4.5zm0 3a.75.75 0 000 1.5h4.5a.75.75 0 000-1.5h-4.5zM5 5.75A.75.75 0 015.75 5h4.5a.75.75 0 01.75.75v2.5a.75.75 0 01-.75.75h-4.5A.75.75 0 015 8.25v-2.5z" clip-rule="evenodd" />
          <path d="M16.5 6.5h-1v8.75a1.25 1.25 0 102.5 0V8a1.5 1.5 0 00-1.5-1.5z" />
        </svg>
        <div class="text-base leading-7">
          <h3 class="font-semibold text-white">Recruit</h3>
          <p class="mt-2 text-gray-300">To bring these technology solutions to market, our team reruits world-class founders with a combination of technical and industry-relevant skills to operate the new ventures.</p>
        </div>
      </div>
    </div>
  </div>
</div>

</template>

<script>

export default {
  name: 'ValueProp'
}

</script>

<style>

</style>