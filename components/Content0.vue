<template>
  <main>
    <div class="container h-100">
      <div class="row align-middle">
        <div class="col-md-6 col-lg-4 column">
          <div class="card gr-1">
            <div class="txt">
              <h1>Let's Join <br> Membership</h1>
              <p>Ayo jadi bagian dari kami!!!</p>
            </div>
            <a href="https://ln.run/c5zZD">join us</a>
            <div class="ico-card">
            <i class="fa fa-rebel"></i>
          </div>
          </div>
        </div>
        <div class="col-md-6 col-lg-4 column">
          <div class="card gr-2">
            <div class="txt">
              <h1>Design And <br> Creation</h1>
              <p>Mari Tingkatkan kretifitas dan karyamu.</p>
            </div>
            <a href="#">more</a>
          <div class="ico-card">
            <i class="fa fa-codepen"></i>
          </div>
          </div>
        </div>
        <div class="col-md-6 col-lg-4 column">
          <div class="card gr-3">
            <div class="txt">
              <h1>Program  In<br> Your Hand</h1>
              <p>Jadilah dari sebagian developer/programmer handal.</p>
            </div>
            <a href="#">more</a>
          <div class="ico-card">
            <i class="fa fa-empire"></i>
          </div>
          </div>
        </div>
      </div>


    </div>
  </main>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css?family=Oswald:300,400,500,700');

@import url('https://fonts.googleapis.com/css?family=Open+Sans:300,400,600,700,800');

$gr-1:linear-gradient(170deg, #01E4F8 0%, #1D3EDE 100%);
$gr-2:linear-gradient(170deg, #B4EC51 0%, #429321 100%);
$gr-3:linear-gradient(170deg, #C86DD7 0%, #3023AE 100%);

.gr-1{background: $gr-1;}
.gr-2{background: $gr-2;}
.gr-3{background: $gr-3;}

*{transition: .5s;}

.h-100{height: 100vh !important;}
.align-middle{
  position: relative;
  top:50%;
  transform:translateY(-50%);
}

.column{
  margin-top:2rem;
  padding-left:3rem;
  &:hover{
    padding-left:0;
    .card .txt{
      margin-left:1rem;
      h1, p{
        color:rgba(255,255,255,1);
        opacity:1;
      }
    }
    a{
      color:rgba(255,255,255,1);
      &:after{
      width: 10%;
      }
    }
  }
}
.card{
  min-height:170px;
  margin: 0;
  padding: 1.7rem 1.2rem;
  border: none;
  border-radius: 0;
  color:rgba(0,0,0,1);
  letter-spacing: .05rem;
  font-family: 'Oswald', sans-serif;
  box-shadow: 0 0 21px rgba(0,0,0,.27);
  .txt{
    margin-left:-3rem;
    h1{
      font-size:1.5rem;
      font-weight: 300;
      text-transform: uppercase;
    }
    p{
      font-size:.7rem;
      font-family: 'Open Sans', sans-serif;
      letter-spacing: 0rem;
      margin-top:33px;
      opacity:0;
      color:rgba(255,255,255,1);
    }
  }
  a{
    z-index:3;
    font-size: .7rem;
    color:rgba(0,0,0,1);
    margin-left:1rem;
    position:relative;
    bottom: -.5rem;
    text-transform: uppercase;
    &:after {
      content:"";
      display: inline-block;
      height: 0.5em;
      width: 0;
      margin-right: -100%;
      margin-left: 10px;
      border-top: 1px solid rgba(255,255,255,1);
      transition: .5s;
    }
  }
  .ico-card{
    position:absolute;
    top: 0;
    left:0;
    bottom:0;
    right: 0;
    width: 100%;
    height: 100%;
    overflow: hidden;
  }
  i{
    position: relative;
    right: -50%;
    top:60%;
    font-size: 12rem;
    line-height: 0;
    opacity: .2;
    color:rgba(255,255,255,1);
    z-index: 0;
   }
}
</style>
