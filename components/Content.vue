<template>
  <main>
    <div class="bagian_tengah mt-2">
        <b-carousel
        id="carousel-1"
        v-model="slide"
        :interval="4000"
        controls
        indicators
        background="#ababab"
        img-width="1024"
        img-height="480"
        style="text-shadow: 1px 1px 2px #333;"
        @sliding-start="onSlideStart"
        @sliding-end="onSlideEnd"
      >
        <!-- Text slides with image -->
        <b-carousel-slide img-src="https://previews.dropbox.com/p/thumb/ACX4PnNak3GQCjhm-U_-gBoLVZiYhmMYatY8XOC0oHczxn4etKnoZF7yx7IagDTNHg0tm5JWO0qrF_TQzPg1eZFominBO0Yr7B9pfabnMWt6VHqo4hi4Q3HmMJev5uFCKD5t4qxBkLwsK9SNag8R7rlZB9_ODJ9IxSlKJ96pQP5_ezIn2W0fVE6IctrEdwx5UfywGO3zy-coOTWtcHP63SL3cBqAgZfhs5-DsM5EET1uRSRnCFiTRoMEBTpESv1ZNrGMcUWLhqheMPEZTmGBelZgkbUSSb8-ZkqmFQD5z0dLaJNCu0Gp40kRq302ZjWUnTLuJko8mNZwCmw3x1lqgjmkFQxMnQds5ilwmFAkoEw7EhraHvjVfy0cxcdiVLZZLuY/p.png"></b-carousel-slide>

        <!-- Slides with custom text -->
        <b-carousel-slide img-src="https://previews.dropbox.com/p/thumb/ACXzvkKwzGOYZt85gvKn-uWr-CtFThlhd2Ri3ThQ0YxFedf6n7msG9v-xYJrOi0MRSXL5PpQGRgjCbKLgOa-4a42lKUZc12eJqBp3ybVAam4JDGNg7E0iD1nY6QJatBaSRrjH74SuyssKH-jwoIrtJ01iZLh8cCcnmpspAF4H1ELZlIG_7v8D2FCD-vBE1LrOioC_3RLrKDWeKmI9hPu9anONHxu1wzp-9eKTYx--9B52gT2mwL2MRxT_-6mpoirUa8cDMCP3kFiOjPnjOhvxqvKMWlsvb3pRWyGFT1w91RR6eQpRMEtbAl7HqFAZX_xirNzJpbrFIiDbeJu_beSpXu8KnYvq_g_BLCg58tq301iuw22pMC0f1yjnjiBBtuoGZ0aH2do5mwiD5EFn_QJ3BbQoINrfgKOXOceqHPCWt4oHAjLhTYhDrfxVsY46mglUPw/p.png">
          <h1>Hello world!</h1>
        </b-carousel-slide>

        <!-- Slide with blank fluid image to maintain slide aspect ratio -->
        <b-carousel-slide caption="Blank Image" img-src="https://previews.dropbox.com/p/thumb/ACWFuH2c2piaHky4qi02cWyuEPut4tqa9Cyf6oyDDpnXVYy038GU86G5HjgFUE2Iam64Dr0VQ1RtxuYba7TLl5QZLwcnbsl8B6cxdwJntcCx4SNAVokpKvjjktTcZW6rL6AdoYKMyyGLKnZbmfJ1zN9-1C1z5Dh5z5mXlZGTgjJ4K32cdekNK9Z2c7GVO87qjUkemyTUZppMFjxgSX1jMJmmFZQ2d2OZnoUOwrV_EO9IubIYPJ6yoj5-f_txDMi5SGfqPjFAKBwMwKFblS0ilEP9-uDa7apJhJlQyvHp_TyJWdi-13in7MB2s5tMkMJXH5Xq_aON0zN5Chv5vEzKkDWQ2aIYHPlzqtFKDa521-ErgfdsSyczJbL2C_DBBOkK2lg/p.png" img-alt="Blank image">
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse eros felis, tincidunt
            a tincidunt eget, convallis vel est. Ut pellentesque ut lacus vel interdum.
          </p>
        </b-carousel-slide>
      </b-carousel>
    </div>
  </main>
</template>

<script>
  export default {
    data() {
      return {
        slide: 0,
        sliding: null
      }
    },
    methods: {
      onSlideStart(slide) {
        this.sliding = true
      },
      onSlideEnd(slide) {
        this.sliding = true
      }
    }
  }
</script>

<style>

</style>
