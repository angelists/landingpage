<template>
  <section class="bg-gray-100 text-gray-800 border-b py-8">
    <div class="container max-w-5xl mx-auto m-8">
      <h1
        class="w-full my-2 text-5xl font-bold leading-tight text-center text-gray-800"
      >
        About
      </h1>
      <p class="text-center my-4">Tell us what this is about</p>

      <FeatureRight
        headline="Feature 1"
        content="What do you offer?"
      >
        <img src="~/assets/imgs/image.png?inline" alt slot="svg" />
      </FeatureRight>

      <FeatureLeft
        headline="Feature 2"
        content="What else do you offer?"
      >
        <img src="~/assets/imgs/image.png?inline" alt slot="svg" />
      </FeatureLeft>

    </div>
  </section>
</template>

<script>
export default {
}
</script>
