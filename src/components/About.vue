<template>
  <div id="about-me">
    <div class='container'>
      <h1>About Me</h1>
      <div class="row">
        <div class="col-6">
          <h4>Personal Details</h4>
          <p>
              Full name: Zharné Desember <br>
              Date of birth: 02/05/1997 <br>
              Gender: Female <br>
              Location: Southern Suburbs <br>
              Phone number: 068 427 0352 <br>
              Email Address: zharnedesember@gmail.com</p>
        
       
          <h4>Where did your passion for coding start:</h4>
          <p>
              What motivated me to get into coding and web development is the independence that it offers and the chance to be creative and collaborate with others. I have always been intrigued by what goes into building websites and web applications, and it has been a joy to create a website and seeing that creation unfold in the process of building it.</p>
        </div>
        <div class="col-3">
          <h5>col2</h5>
          <div class="block">
            <p>put something here</p>
          </div><br>
          <div class="block">
            <p>put something here</p>
          </div>
        </div>
        <div class="col-3">
          <h5>col4</h5>
          <div class="block">
            <p>put something here</p>
          </div><br>
          <div class="block">
            <p>put something here</p>
          </div>
        </div>
      </div>
      <div class="row">
      <section class="section2">
			<div class="section2-1">
				<div class="progress-card progress-vertical">
					<div class="card-title">Front end</div>
					<div class="card-content">
						<div class="group-a">
							<div class="progress-wrapper">
								<div class="skill-name">React</div>
								<div class="skill-progress">
									<div class="inner" style="--value:69%"></div>
								</div>
							</div>
							<div class="progress-wrapper">
								<div class="skill-name">Vue</div>
								<div class="skill-progress">
									<div class="inner" style="--value:50%"></div>
								</div>
							</div>
							<div class="progress-wrapper">
								<div class="skill-name">Flutter</div>
								<div class="skill-progress">
									<div class="inner" style="--value:75%"></div>
								</div>
							</div>
						</div>
						<div class="group-b">
							<div class="progress-wrapper">
								<div class="skill-name">HTML</div>
								<div class="skill-progress">
									<div class="inner" style="--value:95%"></div>
								</div>
							</div>
							<div class="progress-wrapper">
								<div class="skill-name">CSS</div>
								<div class="skill-progress">
									<div class="inner" style="--value:90%"></div>
								</div>
							</div>
							<div class="progress-wrapper">
								<div class="skill-name">Javascript</div>
								<div class="skill-progress">
									<div class="inner" style="--value:70%"></div>
								</div>
							</div>
						</div>
					</div>
				</div>
        </div>
    </section>  
    </div>
    </div>
  </div>
</template>

<style>
#about-me{
  background-color: #C3A995;
  /* padding-bottom: 30px; */
  height: 140vh;
  width: 80%;
  margin-left: 150px;
  margin-top: 50px;
  border-radius: 10px;
  box-shadow: 0 15px 35px rgba(0, 0, 0, 0.5);
}
.container{
    height: 50vh;
    margin-left: 200px;
    /* padding-bottom:30px ; */
}
h4{
  color: #6F5E53;
}
.block{
  height: 150px;
  width: 150px;
  border-radius: 5px; 
  border: solid;
  box-shadow: 0 15px 35px rgba(0, 0, 0, 0.5);

}
.section2-1{
  margin-top: 50px;
  
}
.section2{
  margin-left: 200px;
}
body main.home .section2, body main.home .section3, body main.home .section4 {
  margin-top: 25px;
}
body main.home .section2 {
  display: flex;
  column-gap: 25px;
}
body main.home .section2 > div {
  width: 50%;
  display: flex;
  flex-direction: column;
  row-gap: 25px;
}
body main.home .section2 > div > div {
  width: 100%;
}
body main.home .section2 > div > div .blog {
  width: 100%;
}
.progress-card {
  width: 100%;
  background: #fff;
  border-radius: 7px;
  box-shadow: 2px 2px 10px 0px #3d3b3b21;
  padding: 15px;
  
}
.progress-card .card-title {
  font-size: 14px;
  color: #4F4F4F;
  font-weight: bold;
  text-transform: uppercase;
  letter-spacing: 0.5px;
}
.progress-card .card-content {
  margin-top: 10px;
  display: flex;
  column-gap: 35px;
}
.progress-card .card-content > div {
  flex: 1;
}
.progress-card .card-content .progress-wrapper {
  width: 100%;
  display: flex;
  column-gap: 5px;
  margin: 10px 0px;
  align-items: center;
}
.progress-card .card-content .progress-wrapper .skill-name {
  width: 35%;
  font-size: 11px;
}
.progress-card .card-content .progress-wrapper .skill-progress {
  width: calc(65% - 5px);
  height: 6px;
  background: #C4C4C4;
  border-radius: 10px; 
}
.progress-card .card-content .progress-wrapper .skill-progress .inner {
  border-radius: inherit;
  width: var(--value);
  height: 100%;
  background: #6F5E53;
}

.progress-card.progress-vertical {
  width: 55vw;
  height: 50vh;
  margin: 10px;
}
.progress-card.progress-vertical .card-content {
  margin-top: 20px;
  display: flex;
  flex-direction: column;
  column-gap: unset;
}
.progress-card.progress-vertical .card-content > div:last-of-type {
  margin-top: -10px;
}

</style>