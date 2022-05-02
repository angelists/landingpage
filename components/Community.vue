<template>
  <section class="container mx-auto text-center py-6">
    <div class="flex flex-col w-full justify-center items-center pt-6  text-center">
      <h2>Join the Community</h2>
    </div>

    <div class="flex justify-center items-center w-full mb-16">
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
  </section>
</template>

<script>
import Telegram from '~/assets/svgs/telegram.svg'
import Linkedin from '~/assets/svgs/linkedin.svg'
import Discord from '~/assets/svgs/discord.svg'
import Github from '~/assets/svgs/github.svg'
import Twitter from '~/assets/svgs/twitter.svg'

import Clouds from '~/assets/svgs/clouds.svg'

export default {
  components: {
    Telegram,
    Linkedin,
    Discord,
    Github,
    Twitter,
    Clouds
  }
}
</script>

<style>
</style>
