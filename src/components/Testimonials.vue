<template>
<section>
	<div id='testimonials'>
		<div class="container-lg my-3">
    <div id="myCarousel" class="carousel slide" data-bs-ride="carousel">
        <!-- Carousel indicators -->
        <ol class="carousel-indicators">
            <li data-bs-target="#myCarousel" data-bs-slide-to="0" class="active"></li>
            <li data-bs-target="#myCarousel" data-bs-slide-to="1"></li>
            <li data-bs-target="#myCarousel" data-bs-slide-to="2"></li>
			<li data-bs-target="#myCarousel" data-bs-slide-to="3"></li>
			<li data-bs-target="#myCarousel" data-bs-slide-to="4"></li>
        </ol>
		<!-- wrapper for carousel -->
		<div class="row justify-content-evenly">
			
		  <div class="carousel-inner">
            <div class="carousel-item active">
                <img src="https://i.postimg.cc/NMgGFJgY/Bongani3.jpg" class="d-block">
                <div class="carousel-caption d-none d-md-block">	
                    <h5>Bongani Nomangola</h5>
                    <p>Zharne is a people's person, approachable, friendly and determined in achieving her every goal no matter what.</p>
					<h5>Colleague at Life Choices</h5>
                </div>
            </div>
            <div class="carousel-item">
                <img src="https://i.postimg.cc/XJ8JgM2p/Amaarah3.jpg" class="d-block" alt="Slide 2">
                <div class="carousel-caption d-none d-md-block">
                    <h5>Ammaarah January</h5>
                    <p>Zharne is a very hard-working individual. She is willing to help others and she is a good team member. Her personality will be a great asset to any work envornment.</p>
					<h5>Colleague at Life Choices</h5>
                </div> 
            </div>
            <div class="carousel-item">
                <img src="https://i.postimg.cc/Znxr3DNc/Kyle3.jpg" class="d-block" alt="Slide 3">
                <div class="carousel-caption d-none d-md-block">
                    <h5>Kyle McBryne</h5>
                    <p>Zharne is a dedicated,hard-working individual striving for greatness.</p>
					<h5>Colleague at Life Choices</h5>
                </div>
            </div>
			<div class="carousel-item">
                <img src="https://i.postimg.cc/CLBMx8wd/hannah.jpg" class="d-block" alt="Slide 4">
                <div class="carousel-caption d-none d-md-block">
                    <h5>Hannah Dalwai</h5>
                    <p>Zharne is a hardworking team player, any team would be lucky to have her on board</p>
					<h5>Colleague at Life Choices</h5>
                </div>
            </div>
			<div class="carousel-item">
                <img src="https://i.postimg.cc/wB8vhZgG/Breda.jpg" class="d-block" alt="Slide 5">
                <div class="carousel-caption d-none d-md-block">
                    <h5>Mogammad Breda</h5>
                    <p>Zharne is very hardworking, kind and is never afraid to ask for help. Great qualities that are needed in her field of work.</p>
					<h5>Colleague at Life Choices</h5>
                </div>
            </div>
        </div>
	</div>

        <!-- Carousel controls -->
        <a class="carousel-control-prev" href="#myCarousel" data-bs-slide="prev">
            <span class="carousel-control-prev-icon"></span>
        </a>
        <a class="carousel-control-next" href="#myCarousel" data-bs-slide="next">
            <span class="carousel-control-next-icon"></span>
        </a>
    </div>
    			
		</div>
	</div>
</section>
</template>

<script>
export default { 
  data() {
    return {
      testimonials: []
    }
  },
  mounted() {
    fetch('https://zharneportfolio.herokuapp.com/testimonials')
      .then(res => res.json())
      .then(data => this.testimonials = data)
      .catch(err => console.log(err.message))
  }
}



</script>

<style scoped>
section{
	height: 100vh;
	margin-top: 50vh;
}

.container-lg my-3{
	margin-left: 120px;
}
.carousel-inner{
	height: 70vh;
}
#myCarousel{
	margin-left: 30px;
	background-color: #C3A995;
	border-radius: 10px;
	box-shadow: 0 15px 35px rgba(0, 0, 0, 0.5);
}
.d-block{
	border-radius: 50%;
	width: 400px;
	height: 400px;
	margin: 20px;
}
.carousel-caption{
	margin-left: 40%;
	margin-bottom: 15%;
}
h5{
	color: #6F5E53;
}
</style>