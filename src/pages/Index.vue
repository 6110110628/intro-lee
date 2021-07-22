<template>
  <Layout>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css" />
    <!-- Learn how to use images here: https://gridsome.org/docs/images -->
    <g-image alt="profile" src="~/alee1.jpg" width="300" />

    <h1 style="letter-spacing: 4px">Hello, Everyone!</h1>

    <div class="w3-container w3-pale-blue">
      <p>
        Abdulloh Alee <br />
        computer engineering<br />
        DOB: April 9, 1999 <br />
        Age: 22 years <br />
        Gender: Male <br />
        Marriage: Single <br />
        Height: 160 cm <br />
        Weight: 62 kg <br />
        Nationality: THAILAND <br />
        Religion: Islam <br />
        Military: None <br />
        Hometown: (Hat yai)
      </p>
    </div>

    <p class="home-links">
      <a href="https://github.com/6110110628" target="_blank" rel="noopener"
        >GitHub</a
      >
    </p>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "Hello, world!",
  },
};
</script>

<style>
.home-links a {
  margin-right: 1rem;
}
</style>
