<template>
<footer>
    <div class="footer-content">
        <div class="footer-bottom">
            <p>copyright &copy;2022 <a href="#about-me">Zharne Desember</a>  </p>
            <div class="footer-menu">
            <ul class="f-menu">
                <li><a href="#home">Home</a></li>
                <li><a href="#testimonials">Testimonials</a></li>
                <li><a href="#contact">Contact</a></li>
                <li><a target href="https://docs.google.com/document/d/1BNq0GgOnKe2GsPqXlD5l_oy9zYZPytQMoJMmDJ7Hpfc/edit">Resume</a></li>
            </ul>
            </div>

        </div>

    </div>
</footer>
</template>

<script>
export default {

}
</script>

<style scoped>
 *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body{
    background: #504136;
    font-family: sans-serif;
}

.footer-content{
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    text-align: center;
    /* margin-left:200px */
}
.footer-content h3{
    font-size: 2.1rem;
    font-weight: 500;
    text-transform: capitalize;
    line-height: 3rem;
}
.footer-content p{
    max-width: 450px;
    margin: 10px auto;
    line-height: 28px;
    font-size: 14px;
    color: #feffff;
}

.footer-bottom{
    background: #C3A995;
    width: 100%;
    padding: 20px;
    padding-bottom: 40px;
    text-align: center;
    /* margin-left: 186px; */
}
.footer-bottom p{
   float: left;
   font-size: 14px;
   word-spacing: 2px;
   text-transform: capitalize;
}
.footer-bottom p a{
  color:#6F5E53;
  font-size: 16px;
  text-decoration: none;
}
.footer-bottom span{
    text-transform: uppercase;
    opacity: .4;
    font-weight: 200;
}
.footer-menu{
  float: right;
}

.footer-menu ul{
  display: flex;
}

.footer-menu ul li{
padding-right: 10px;
display: block;
}

.footer-menu ul li a{
  color: #6F5E53;
  text-decoration: none;
}

.footer-menu ul li a:hover{
  color: #feffff;
}
@media (max-width:500px) {
.footer-menu ul{
  display: flex;
  margin-top: 10px;
  margin-bottom: 20px;
}
}
</style>