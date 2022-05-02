<template>
  <div class="m-8">
    <div class="text-center">
      <div class="w-full flex justify-center mb-4 mt-24">
        <img src="~/assets/logos/bend_logo_light.png" alt="">
      </div>
      <h2 class="w-full">Fueled by BEND</h2>
      <p class="w-full text-xl">Bend is an ultimate governance token empowering the future of community angel investments</p>
    </div>


    <div class="w-full flex flex-wrap justify-center items-center mb-12 px-4">
      <div class="w-full md:flex-1 my-12 text-center">
        <div class="flex justify-center py-2 my-8">
          <Store class="w-32" slot="svg"/>
        </div>
        <h3 class="text-3xl font-bold leading-none mb-3">DAO Membership</h3>
        <div class="">
          <p>Automatic whitelisting -</p>
          <p>Governance proposals -</p>
          <p>Voting Power </p>
        </div>
      </div>

      <div class="w-full md:flex-1 my-12 text-center">
        <div class="flex justify-center py-2 my-8">
          <Chart class="w-32" slot="svg" />
        </div>
        <h3 class="text-3xl font-bold leading-none mb-3">Store of Value</h3>
        <div class="">
          <p>Hyper Deflationary</p>
          <p>Premium Utility</p>
        </div>
      </div>
    </div>

  </div>
</template>

<script>
import Chart from '~/assets/svgs/chart-line-solid.svg'
import Store from '~/assets/svgs/landmark-solid.svg'

export default {
  components: {
    Chart,
    Store
  }
}
</script>
