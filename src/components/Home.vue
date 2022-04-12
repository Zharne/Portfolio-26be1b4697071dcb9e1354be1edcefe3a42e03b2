<template>
  <div id="home">
    <div class="container"><br><br><br><br>
        <div class='img-box'>
            <img src="https://i.postimg.cc/Gp5rLhQK/me-shot-min.jpg" style="border-radius:50%">
        </div><br>
            <h1>ZHARNÉ DESEMBER</h1> 
        <br>
        <div class="button">
             <div class="slide-btn mt-10" data-v-e4caeaf8="">
                <a class="rf-btn" target="_blank" href="https://docs.google.com/document/d/1BNq0GgOnKe2GsPqXlD5l_oy9zYZPytQMoJMmDJ7Hpfc/edit" data-v-e4caeaf8="">Download CV</a>
            </div>
        </div> 
        <div class="socials">
            <!-- <ul>
                <li>
                    <a href="#">
                    <i class="fab fa-facebook-f icon"></i>    </a>
                </li>
                <li>
                    <a href="#"><i class="fab fa-twitter icon"></i></a>
                </li>
                <li>
                    <a href="https://www.linkedin.com/in/zharné-desember-795b8416b" target="_blank"><i class="fab fa-linkedin-in icon"></i></a></li>
                <li>
                    <a href="#"><i class="fab fa-google-plus-g icon"></i></a></li>
            </ul> -->
        </div>            
    </div>   
  </div>   
</template>

<script>


</script>

<style scoped>
.container{
    background-color:  #C3A995;
    height: 100vh;
    margin-left: 150px;
    width: 80%;
    border-radius:10px;
    box-shadow: 0 15px 35px rgba(0, 0, 0, 0.5);
} 

h1{
    color:#6F5E53;
    text-shadow: 2px 2px 5px gray;
}
.img-box {
	width: 200px;
	height: 200px;
	margin: 0 auto;
	padding: 5px;
	border: 1px solid #ddd;
	border-radius: 50%;
    
}
.img-box img {
	width: 100%;
	height: 100%;
	display: block;
	border-radius: 50%;
}
.button{
    margin-top: 13%;
}
.rf-btn {
    display: inline-block;
    padding: 10px 30px;
    height: 50px;
    border-radius: 50px;
    font-size: 16px;
    font-weight: 500;
    text-transform: uppercase;
    transition: .3s ease-in-out;
    color: #fff !important;
    /* background: ; */
    border: 2px solid white;
    box-shadow: 0 5px 20px -5px rgba(0,0,0,.05);
    font-weight: bold;
    position: relative;
}

.rf-btn:hover  {
    color: white;
    background: #6F5E53;
}



/* 
@keyframes img-box {
  0%,
  49% {
    background: black;
  }
  50%,
  100% {
    background: white;
  }
} */

/* When the screen is less than 600 pixels wide, hide all links, except for the first one ("Home"). Show the link that contains should open and close the topnav (.icon) */
@media screen and (max-width: 800px) {
.container{ width: 40%;
}
ul li a {
  width: 40px;
  height: 40px;
  background-color: #fff;
  text-align: center;
  line-height: 80px;
  font-size: 35px;
  margin: 0 10px;
  display: block;
  border-radius: 50%;
  position: relative;
  overflow: hidden;
  border: 3px solid #fff;
  z-index: 1;
}
.ul{
    transform: translate(-20%, -263%);
}
}

/* The "responsive" class is added to the topnav with JavaScript when the user clicks on the icon. This class makes the topnav look good on small screens (display the links vertically instead of horizontally) */
@media screen and (max-width: 600px) {
  .container{ width: 50%;
}
ul li a {
  width: 20px;
  height: 20px;
  background-color: #fff;
  text-align: center;
  line-height: 80px;
  font-size: 35px;
  margin: 0 10px;
  display: block;
  border-radius: 50%;
  position: relative;
  overflow: hidden;
  border: 3px solid #fff;
  z-index: 1;
}
/* .ul{
    margin-left: 80%;
} */
}
</style>