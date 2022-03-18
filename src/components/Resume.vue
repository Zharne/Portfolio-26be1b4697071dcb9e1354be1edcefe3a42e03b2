<template>
  <div id='resume'>
    <div class="container">
    <div class="row">
        <div class="col-md-12">
            <div class="main-timeline">
                <div class="timeline">
                    <a href="#" class="timeline-content">
                        <div class="timeline-year">2015</div>
                        <div class="timeline-icon"><i class="fa fa-globe"></i></div>
                        <h3 class="title">National Senior Certificate(Matric)</h3>
                        <h5>Oude Molen Technical High School</h5>
                        <p class="description">
                          Afrikaans, English, Life Science, Mathematics, Life Orientation, Mechanical Technology, Business Studies.
                        </p>
                    </a>
                </div>
                <div class="timeline">
                    <a href="#" class="timeline-content">
                        <div class="timeline-year">2016</div>
                        <div class="timeline-icon"><i class="fa fa-rocket"></i></div>
                        <h3 class="title">Internship</h3>
                        <h5>Martin & East Pty(Ltd)</h5>
                        <p class="description">  
                           I completed a 1 year internship as a workshop trainee and an aspiring mechanical engineer. 
                        </p>               
                    </a>
                </div>
                <div class="timeline">
                    <a href="#" class="timeline-content">
                        <div class="timeline-year">2017</div>
                        <div class="timeline-icon"><i class="fa fa-rocket"></i></div>
                        <h3 class="title">N1-N3 Engineering Welding</h3>
                        <h5>False Bay TVET College</h5>
                        <p class="description">
                            I did not complete my Nated 3 diploma because I decided to do my BCom degree the following year.
                        </p>
                    </a>
                </div>
                <div class="timeline">
                    <a href="#" class="timeline-content">
                        <div class="timeline-year">2018-2020</div>
                        <div class="timeline-icon"><i class="fa fa-rocket"></i></div>
                        <h3 class="title">Bachelors of Commerce(Gen)</h3>
                        <h5>Pearson Institute of Higher Learning</h5>
                        <p class="description">
                              I completed my degree 
                        </p>
                    </a>
                </div>
                  <div class="timeline">
                    <a href="#" class="timeline-content">
                        <div class="timeline-year">2021-2022</div>
                        <div class="timeline-icon"><i class="fa fa-rocket"></i></div>
                        <h3 class="title">Web development</h3>
                        <h5>Life Choices Coding Academy</h5>
                        <p class="description">
                              I am currently completing my coding course at Life Choices. 
                        </p>
                    </a>
                </div>
            </div>
        </div>
    </div>
</div>
  </div>
</template>

<script>

</script>

<style scoped>
#resume{
  height: 200vh;
  background-color:  #111;
  margin-left: 250px;
  width: 80%;
  border-radius:10px
}

.main-container {
  margin-top: 2rem;
  display: flex;
  width: 100%;
  justify-content: center;
  align-items: center;
}
.row{
  margin: 2rem;
  width: 75%;
  display: flex;
  justify-content: center;
  align-items: center;
}
#content {
  margin-top: 50px;
  text-align: center;
  margin-left: 300px;
}

/* Timeline */

.main-timeline{
    font-family: 'Poppins', sans-serif;
    padding: 15px 0;
}
.main-timeline:after{
    content: '';
    display: block;
    clear: both;
}
.main-timeline .timeline{
    width: calc(50% + 1px);
    padding: 15px 0 0 15px;
    margin: 0 0 20px 5px;
    float: right;
    position: relative;
    z-index: 1;
}
.main-timeline .timeline-content{
    color: #777;
    background-color: #E4EEF0;
    min-height: 120px;
    padding: 35px 15px 15px 80px;
    border-radius: 20px;
    box-shadow: 0 5px 10px rgba(0,0,0,0.2);
    display: block; 
    position: relative;
}
.main-timeline .timeline-content:hover{ text-decoration: none; }
.main-timeline .timeline-content:before{
    content: '';
    background-color: #B330C0;
    height: 80%;
    width: calc(100% + 15px);
    border-radius: inherit;
    position: absolute;
    left: -15px;
    top: -15px;
    z-index: -1;
}
.main-timeline .timeline-year{
    color: #fff;
    background-color: #B330C0;
    font-size: 20px;
    font-weight: 600;
    padding: 5px 5px 7px;
    border-radius: 0 0 10px 10px;
    position: absolute;
    left: 10px;
    top: 0;
}
.main-timeline .timeline-icon{
    color: #777;
    font-size: 40px;
    transform: translateY(-50%);
    position: absolute;
    left: 20px;
    top: 50%;
}
.main-timeline .title{
    color: #333;
    font-size: 22px;
    font-weight: 600;
    letter-spacing: 0.5px;
    text-transform: uppercase;
    margin: 0 0 3px;
}
.main-timeline .description{
    font-size: 14px;
    font-weight: 500;
    letter-spacing: 1px;
    line-height: 23px;
    margin: 0;
}
.main-timeline .timeline:nth-child(even){
    padding: 15px 15px 0 0;
    margin: 0 5px 20px 0;
    float: left;
}
.main-timeline .timeline:nth-child(even) .timeline-content{ padding: 35px 80px 15px 15px; }
.main-timeline .timeline:nth-child(even) .timeline-content::before{
    left: auto;
    right: -15px;
}
.main-timeline .timeline:nth-child(even) .timeline-icon{
    left: auto;
    right: 20px;
}
.main-timeline .timeline:nth-child(even) .timeline-year{
    left: auto;
    right: 10px;
}
.main-timeline .timeline:nth-child(4n+2) .timeline-content::before,
.main-timeline .timeline:nth-child(4n+2) .timeline-year{
    background-color: #CB246E;
}
.main-timeline .timeline:nth-child(4n+3) .timeline-content::before,
.main-timeline .timeline:nth-child(4n+3) .timeline-year{
    background-color: #FB7E05;
}
.main-timeline .timeline:nth-child(4n+4) .timeline-content::before,
.main-timeline .timeline:nth-child(4n+4) .timeline-year{
    background-color: #00A8D7;
}
@media screen and (max-width:767px){
    .main-timeline .timeline,
    .main-timeline .timeline:nth-child(even){
        width: 100%;
        margin: 0 0 40px;
    }
}
@media screen and (max-width:576px){
    .main-timeline .timeline-content,
    .main-timeline .timeline:nth-child(even) .timeline-content{
        padding: 65px 15px 15px 15px;
    }
    .main-timeline .timeline-icon{
        transform: translateY(0);
        top: 5px;
        left: auto;
        right: 15px;
    }
    .main-timeline .timeline:nth-child(even) .timeline-icon{
        transform: translateY(0);
        top: 5px;
        right: auto;
        left: 15px;
    }
}

</style>