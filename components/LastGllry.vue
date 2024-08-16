<template>
  <main>
    <div class="container">
      <div class="testimonial-box">
        <div class="testimonial">
          <i class="fa fa-quote-right" aria-hidden="true"></i>
          <span class="testimonial-text">
            <p class="font-italic">Setiap bahasa pemrograman itu unik dan itu yang membuatnya menarik untuk dipelajari, tetapi jika hanya meniru dan mengubah kita akan kesulitan untuk mencari hal yang membuat kita unik sebagai seorang programmer.</p>
            <br>
          </span>
          <div class="testimonial-user">
            <img src="~/static/assets/pbc/img.png" alt="user-img" class="user-img">
            <div class="user-info">
              <span class="user-name">ravoffc</span>
              <div class="user-job-details">
                <div class="mr-auto">
                  <span class="user-job">
                    <button type="button" class="btn btn-outline-light btn-sm" data-toggle="tooltip" data-placement="bottom" title="Artistic & Programmer">
                      Job
                    </button>
                  </span>
                  <span class="user-post">
                    <button type="button" class="btn btn-outline-light btn-sm" data-toggle="tooltip" data-html="true" data-placement="bottom" title="Orang yang melanggar aturan ialah sampah,
tapi orang yang tak menghargai teman itu lebih buruk dari sampah.">
                      Motto
                    </button>
                  </span>
                </div>
              </div>
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
.container{
	width: 80%;
	height: 80%;
	display: grid;
	justify-content: center;
	align-content: center;

	.testimonial-box{
		position: relative;
		width: 500px;
		height: 300px;

		&::before{
			content: '';
			position: absolute;
			top: 10px;
			left: -100px;
			width: 200px;
			height: 200px;
			border-radius: 50%;
			background:  linear-gradient(to top, #a18cd1 0%, #fbc2eb 100%) , rgba(255, 255, 255, 0.8);
			box-shadow: -5px 5px 10px rgba(0,0,0,.3);
			z-index: -1;
		}
			&::after{
			content: '';
			position: absolute;
			bottom: 10px;
			right: -100px;
			width: 200px;
			height: 200px;
			border-radius: 50%;
			background: linear-gradient(to top, #a18cd1 0%, #fbc2eb 100%) , rgba(255, 255, 255, 0.8);
			box-shadow: 5px 5px 10px rgba(0,0,0,.3);
			z-index: -1;
		}

		.testimonial{
			display: grid;
			grid-template-rows: 1.3fr 0.7fr;
			box-shadow: 0 0 5px rgba(0,0,0,.5);
			width: 100%;
			height: 100%;
			background-image: linear-gradient(120deg, #e0c3fc 0%, #8ec5fc 100%);
			padding: 10px 20px;
			position: relative;

			.fas{
				position: absolute;
				top: 0;
				right: 0;
				padding: 10px;
				font-size: 25px;
				color: #222;
			}

			.testimonial-text{
				font-size: 16px;
				line-height: 25px;
				text-align: center;
				padding: 25px 15px;
				width: 100%;
			}

			.testimonial-user{
				display: flex;
				align-items: center;

				.user-img{
					box-shadow: 0 0 10px rgba(0,0,0,.5);
					width: 60px;
					height: 60px;
					border-radius: 50%;
				}

				.user-info{
					margin: 0 20px;
					display: grid;
					grid-template-rows: 1fr 1fr;

					.user-name{
						font-weight: 800;
					}

					.user-job-details{
            margin-top: -2px;
					}
				}
			}
		}
	}
}


.support{
	position: absolute;
	right: 10px;
	bottom: 10px;
	padding: 10px;
	display: flex;
}
a{
	margin: 0 10px;
	color: #fff;
	font-size: 1.5rem;
	transition: all 400ms ease;
}

a:hover{
	color: #222;
}
</style>
