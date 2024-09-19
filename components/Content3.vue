<template>
  <main>
    <a class="link" href="#" target="_blank">Top View</a>
<div class="movie_card" id="bright">
  <div class="info_section">
    <div class="movie_header">
      <img class="locandina" src="~/static/assets/kss/cv2.png"/>
      <h1>Selotip</h1>
      <h4>2023, PusaranKata</h4>
      <span class="minutes">14 min</span>
      <p class="type">short movie</p>
    </div>
    <div class="movie_desc">
      <p class="text">
        Semua orang pasti punya masalah, namun banyak yang enggan menceritakannya, karena ada sebuah stigma seolah jika seseorang bercerita tentang masalahnya mereka akan di cap sebagai orang yang payah dan tak dewasa.
      </p>
    </div>
    <div class="movie_social">
      <ul>
        <li><i class="material-icons"><a href="https://youtu.be/p-0elnB5c_8?si=HxQgIFNi3HdlTRmC" class="link">Wacth</a></i></li>
        <li><i class="material-icons"><a href="#" class="link"></a></i></li>
        <li><i class="material-icons"><a href="#" class="link"></a></i></li>
      </ul>
    </div>
  </div>
  <div class="blur_back bright_back"></div>
</div>

<div class="movie_card" id="tomb">
  <div class="info_section">
    <div class="movie_header">
      <img class="locandina" src="~/static/assets/kss/cv4.png"/>
      <h1>Sabar</h1>
      <h4>2023, PusaranKata</h4>
      <span class="minutes">14 min</span>
      <p class="type">Short Movie</p>
    </div>
    <div class="movie_desc">
      <p class="text">
        Sabar itu bukan hanya diam ketika di timpa masalah, namun keteguhan hati dalam menghadapi masalah serta menjadi jalan untuk lebih dekat kepada Allah SWT, Film ini kami dedikasikan untuk mereka yang berjuang dalam hidup menuju kehidupan yang lebih baik.
      </p>
    </div>
    <div class="movie_social">
      <ul>
        <li><i class="material-icons"><a href="https://www.youtube.com/watch?v=8AWcQjkS650" class="link">Wacth</a></i></li>
        <li><i class="material-icons"><a href="#" class="link"></a></i></li>
        <li><i class="material-icons"><a href="#" class="link"></a></i></li>
      </ul>
    </div>
  </div>
  <div class="blur_back tomb_back"></div>
</div>

<div class="movie_card" id="ave">
  <div class="info_section">
    <div class="movie_header">
      <img class="locandina" src="~/static/assets/kss/cv3.png"/>
      <h1>TFQ</h1>
      <h4>2024, Natzyv</h4>
      <span class="minutes">33 sec</span>
      <p class="type">Story, Animation, Fantasy</p>
    </div>
    <div class="movie_desc">
      <p class="text">
        Ini ialah kisah dari mereka yang yakin akan kebenaran ditengah fananya dunia, disaat tuhan dan harapan menjadi pertanyaan di seluruh bumi dan langit.
      </p>
    </div>
    <div class="movie_social">
      <ul>
        <li><i class="material-icons"><a href="https://youtu.be/zpunLuRbDUY?si=SjezecbLwps7O1hm" class="link">Wacth</a></i></li>
        <li><i class="material-icons"><a href="#" class="link"></a></i></li>
        <li><i class="material-icons"><a href="#" class="link"></a></i></li>
      </ul>
    </div>
  </div>
  <div class="blur_back ave_back"></div>
</div>
  </main>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>

.link{
  display: block;
  text-align: center;
  color: #777;
  text-decoration: none;
  padding: 0px;
}

.movie_card{
  position: relative;
  display: block;
  width: 800px;
  height: 350px;
  margin: 80px auto;
  overflow: hidden;
  border-radius: 10px;
  transition: all 0.4s;
  box-shadow: 0px 0px 120px -25px rgba(0,0,0, 0.5);
  &:hover{
    transform: scale(1.02);
    box-shadow: 0px 0px 80px -25px rgba(0,0,0, 0.5);
    transition: all 0.4s;
  }
  .info_section{
    position: relative;
    width: 100%;
    height: 100%;
	  background-blend-mode: multiply;
    z-index: 2;
    border-radius: 10px;
    .movie_header{
      position: relative;
      padding: 25px;
      height: 40%;
      h1{
        color: black;
        font-weight: 400;
      }
      h4{
        color: #555;
        font-weight: 400;
      }
      .minutes{
        display: inline-block;
        margin-top: 15px;
        color: #555;
        padding: 5px;
        border-radius: 5px;
        border: 1px solid rgba(0,0,0,0.05);
      }
      .type{
        display: inline-block;
        color: #959595;
        margin-left: 10px;
      }
      .locandina{
        position: relative;
        float: left;
        margin-right: 20px;
        height: 120px;
        box-shadow: 0 0 20px -10px rgba(0,0,0,0.5);
      }
    }
    .movie_desc{
      padding: 20px;
      height: 50%;
      .text{
        color: #545454;
      }
    }
    .movie_social{
      height: 10%;
      padding-top: -10px;
      padding-left: 10px;
      padding-bottom: 25px;
      ul{
        list-style: none;
        padding: 0;
        li{
          display: inline-block;
          color: rgba(0,0,0,0.3);
          transition: color 0.3s;
          transition-delay: 0.15s;
          margin: 0 10px;
          &:hover{
            transition: color 0.3s;
            color: rgba(0,0,0,0.7);
          }
          i{
            font-size: 19px;
            cursor: pointer;
          }
        }
      }
    }
  }
  .blur_back{
    position: absolute;
    top: 0;
    z-index: 1;
    height: 100%; right: 0;
    background-size: cover;
    border-radius: 11px;
  }
}

@media screen and (min-width: 768px) {
  .movie_header{
    width: 65%;
  }

  .movie_desc{
    width: 50%;
  }

  .info_section{
    background: linear-gradient(to right, #e5e6e6 50%, transparent 100%);
  }

  .blur_back{
    width: 80%;
    background-position: -100% 10% !important;
  }
}

@media screen and (max-width: 768px) {
  .movie_card{
    width: 95%;
    margin: 70px auto;
    min-height: 350px;
    height: auto;
  }

  .blur_back{
    width: 100%;
    background-position: 50% 50% !important;
  }

  .movie_header{
    width: 100%;
    margin-top: 85px;
  }

  .movie_desc{
    width: 100%;
  }

  .info_section{
    background: linear-gradient(to top, #e5e6e6 50%, transparent 100%);
    display: inline-grid;
  }
}


.bright_back{
  background: url("~/static/assets/kss/pst(1).jpg");
}

.tomb_back{
  background: url("~/static/assets/kss/pst(2).jpg");
}

.ave_back{
    background: url("~/static/assets/kss/cv1.png");
}
</style>
