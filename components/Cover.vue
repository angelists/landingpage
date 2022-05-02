<template>
  <section class="pt-24 h-auto pb-12">
    <div
      class="px-3 flex flex-col items-center w-full"
    >
      <!--Left Col-->
      <div
        class="px-3 flex flex-col items-center justify-center w-full py-32"
      >
        <!--Right Col-->
        <div class="flex w-full justify-center items-center py-6 text-center">
          <img class="w-full md:w-1/5" src="~/assets/logos/angelists_transparent.png" alt />
        </div>
        <div class="flex flex-col w-full justify-center items-center py-6 text-center">
          <h1>Angelists</h1>
          <p class="w-full">The Community Driven Angel</p>
        </div>

        <div class="flex justify-center items-center w-full text-white">
          <a
            class="mx-auto lg:mx-0 hover:underline font-bold rounded-full my-2 py-4 px-2 flex items-center"
            href="https://www.linkedin.com/company/angelists/"
            target="_blank"
            >
            <Linkedin class="mr-4"/>
          </a>
          <!-- <a
            class="mx-auto lg:mx-0 hover:underline font-bold rounded-full my-2 py-4 px-2 flex items-center"
            href="https://discord.gg/7uP2SQ2t5F"
            target="_blank"
            >
            <Discord class="mr-4"/>
          </a> -->
          <a
            class="mx-auto lg:mx-0 hover:underline font-bold rounded-full my-2 py-4 px-2 flex items-center"
            href="https://twitter.com/AngelistsCap"
            target="_blank"
            >
            <Twitter class="mr-4"/>
          </a>
          <a
            class="mx-auto lg:mx-0 hover:underline font-bold rounded-full my-2 py-4 px-2 flex items-center"
            href="https://github.com/angelists"
            target="_blank"
            >
            <Github class="mr-4"/>
          </a>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import Telegram from '~/assets/svgs/telegram.svg'
import Linkedin from '~/assets/svgs/linkedin.svg'
import Discord from '~/assets/svgs/discord.svg'
import Github from '~/assets/svgs/github.svg'
import Twitter from '~/assets/svgs/twitter.svg'

export default {
  components: {
    Telegram,
    Linkedin,
    Discord,
    Github,
    Twitter
  }
}
</script>
