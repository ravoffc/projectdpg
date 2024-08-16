<template>
  <main>
    <div id="notebook-paper">
      <header>
        <h1>Program Kerja</h1>
      </header>
      <div id="content">
        <div class="hipsum">
            <p><b>1. One Day</b>; dimana proker ini bertujuan untuk setiap kali forum, setiap anggota
              diharuskan mempunyai hasil atau karya nyata setidaknya satu.</p>
            <p><b>2. Showcase Karya</b>; dimana proker ini dimaksudkan setiap karya yang dibuat
            oleh anggota di post atau di <i>share</i> ke beberapa platform, untuk menghasilkan benefit khususnya
            untuk ukm desprog dan umumnya bagi dirinya.</p>
            <p><b>3. Tee Code</b>; dimana proker ini di adakan secara takterduga biasanya disetiap akhir materi
            akan ada sebuah <i>challenge</i> yang menarik jika selesai maka akan mendapat penghargaan dari ketua
            secara simbolis.</p>
            <p><b>4. Team Production</b>; dimana proker ini bertujuan untuk memupuk rasa persaudaraan antara
            anggota desprog lewat kerja sama dalam sebuah tim produksi.</p>
            <p><b>5. Output</b>; dimana proker ini merupakan hasil dari keseluruhan semuanya dan untuk meninjau,
            mengindentifikasi dan mengamati semua buahnya ialah <i>award</i> yang dilakukan sebanyak tiga kali selama
            kepengurusan.</p>
            <p><b>6. Upgrading and Colaboration</b>; proker ini bertujuan untuk melakukan sebuah <i>benchmarking</i> atau perbaikan 
            berkelanjutan baik itu dari segi materi, <i>ultilitas</i> dan hal-hal yang dirasa perlu dirubah, selain itu juga
            membuka jalan untuk kemajuan desprog lewat kolaborasi baik dengan internal maupun eksternal.</p>
        </div>
      </div>
    </div>
  </main>
</template>

<style lang="scss" scoped>
* {
  -webkit-box-sizing:border-box;
  -moz-box-sizing:border-box;
  -ms-box-sizing:border-box;
  -o-box-sizing:border-box;
  box-sizing:border-box;
}

body {
  background: #f1f1f1;
  font-family:helvetica neue, helvetica, arial, sans-serif;
  font-weight:200;
}

#notebook-paper {
  width:960px;
  height:1109px;
  background: linear-gradient(to bottom,white 29px,#00b0d7 1px);
  margin:50px auto;
  background-size: 100% 30px;
  position:relative;
  padding-top:150px;
  padding-left:160px;
  padding-right:20px;
  overflow:hidden;
  border-radius:5px;
  -webkit-box-shadow:3px 3px 3px rgba(0,0,0,.2),0px 0px 6px rgba(0,0,0,.2);
  -moz-box-shadow:3px 3px 3px rgba(0,0,0,.2),0px 0px 6px rgba(0,0,0,.2);
  -ms-box-shadow:3px 3px 3px rgba(0,0,0,.2),0px 0px 6px rgba(0,0,0,.2);
  -o-box-shadow:3px 3px 3px rgba(0,0,0,.2),0px 0px 6px rgba(0,0,0,.2);
  box-shadow:3px 3px 3px rgba(0,0,0,.2),0px 0px 6px rgba(0,0,0,.2);
  &:before {
    content:'';
    display:block;
    position:absolute;
    z-index:1;
    top:0;
    left:140px;
    height:100%;
    width:1px;
    background:#db4034;
  }
  header {
    height:150px;
    width:100%;
    background:white;
    position:absolute;
    top:0;
    left:0;
    h1 {
      font-size:60px;
      line-height:60px;
      padding:127px 20px 0 160px;
    }
  }
  #content {
    margin-top:67px;
    font-size:20px;
    line-height:30px;
    p {
      margin:0 0 30px 0;
    }
  }
}
</style>
