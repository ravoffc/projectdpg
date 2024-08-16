<template>
  <main>
    <div class="permulaan">
      <b-alert show dismissible>
        Hallo user!!! Udah join belum nih :), note: nyalakan mode desktop jika android karena website masih tahap pengembangan!
      </b-alert>
    </div>
    <Navbar />
    <div class="isi">
      <div class="container">
          <Content />
          <hr>
          <Content0 />
      </div>
      <div class="container">
        <hr>
        <Content1 />
        <hr>
      </div>
    </div>

    <div class="akhiran">
      <LastGllry />
      <div class="container">
        <hr>
      </div>
      <Coment />
    </div>
    <Footer />
  </main>
</template>

<script>
export default {

}
</script>

<style>

</style>
