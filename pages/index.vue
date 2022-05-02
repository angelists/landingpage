<template>
  <div>
    <Cover class="w-full cover"/>
    <Features id="about" class="w-full about"/>
    <HowItWorks id="howitworks"/>
    <Tokenomics id="tokenomics"/>
    <Roadmap id="roadmap" class="w-full roadmap"/>
    <div class="bg-gray-100 text-gray-800">
      <Community id="community"/>
    </div>
  </div>
</template>

<script>
export default {
}
</script>

<style>

.cover {
    background: url('../assets/imgs/cloudsCover.png') no-repeat top center;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
}

.about {
  background: url('../assets/imgs/cloudsAbout.png') no-repeat center center;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
}

.roadmap {
  background: url('../assets/imgs/cloudsRoadmap.png') no-repeat bottom center;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
}

</style>
