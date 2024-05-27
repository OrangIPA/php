<template>
  <div class="flex min-h-screen items-center justify-center">
    <main
      class="grid grid-cols-[minmax(0px,_11fr)_10px_minmax(0px,_3fr)] gap-x-9"
    >
      <div class="flex cursor-default flex-col items-end">
        <div class="flex">
          <div
            class="rotate-180 pl-4 pt-5 text-start text-2xl text-neutral-200 [writing-mode:vertical-rl]"
          >
            Hi, i'm
          </div>
          <div
            class="text-[11rem] leading-none text-teal-500 decoration-8 underline-offset-8 hover:underline"
          >
            Alan
          </div>
        </div>
        <div class="text-3xl text-neutral-200">
          And i'm a
          <span
            class="text-4xl text-teal-500 decoration-4 underline-offset-4 hover:underline"
            >Software developer</span
          >
        </div>
      </div>
      <div class="bg-neutral-200"></div>
      <div class="flex w-fit flex-col items-start justify-center gap-2">
        <a
          href="https://www.linkedin.com/in/alanbahana/"
          class="text-2xl text-neutral-200 hover:text-teal-500 hover:underline"
          >Linkedin</a
        >
        <a
          href="https://github.com/OrangIPA"
          class="text-2xl text-neutral-200 hover:text-teal-500 hover:underline"
          >Github</a
        >
        <a href="/" class="text-2xl text-neutral-200 hover:line-through"
          >About</a
        >
        <a href="/" class="text-2xl text-neutral-200 hover:line-through"
          >Blogs</a
        >
      </div>
    </main>
  </div>
</template>
