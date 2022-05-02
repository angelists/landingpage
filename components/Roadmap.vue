<template>
  <section class="py-8 roadmap">
    <div class="w-full text-center pt-16">
      <h1>Roadmap</h1>
    </div>

    <FeatureLeft
      headline="Fair Launch"
    >
      <div class="" slot="content">
        <p>Fairl Launch incl. Liquidity Provicing on Pinksale</p>
      </div>
      <div class="w-full flex justify-end" slot="svg">
        <h2>May 2022</h2>
      </div>
    </FeatureLeft>

    <div class="w-full flex justify-center">
      <Caret class="w-12 h-12"/>
    </div>

    <FeatureLeft
      headline="NFT Placements"
    >
      <div class="" slot="content">
        <p>Placement Configuration enabled</p>
        <p>NFT Trade enabled</p>
      </div>
      <div class="w-full flex justify-end" slot="svg">
        <h2>June 2022</h2>
      </div>
    </FeatureLeft>

    <div class="w-full flex justify-center">
      <Caret class="w-12 h-12"/>
    </div>

    <FeatureLeft
      headline="DAO"
    >
      <div class="" slot="content">
        <p>Governance enabled</p>
      </div>
      <div class="w-full flex justify-end" slot="svg">
        <h2>July 2022</h2>
      </div>
    </FeatureLeft>

    <div class="w-full flex justify-center">
      <Caret class="w-12 h-12"/>
    </div>

    <FeatureLeft
      headline="Enabling community launchpad"
    >
      <div class="" slot="content">
        <p>First round of project incubation</p>
      </div>
      <div class="w-full flex justify-end" slot="svg">
        <h2>August 2022</h2>
      </div>
    </FeatureLeft>

    <div class="pb-64">

    </div>
  </section>
</template>

<script>
import Caret from '@/assets/svgs/caret-down-solid.svg'

export default {
  components: {
    Caret
  }
}
</script>

<style>
</style>
