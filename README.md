<!DOCTYPE html>
<html>
<title>LGEGX</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">

<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Raleway">
<style>
body,h1 {font-family: "Raleway", sans-serif;
  background-color:#f3f3f3}

.arrow {
  border: solid #703254;
  border-width: 0 3px 3px 0;
  display: inline-block;
  padding: 30px;
  text-align: center;
 
}

.down {
  transform: rotate(45deg);
  -webkit-transform: rotate(45deg);
}









  
    .img1 {
  rgba(0,0,0,0.30), 0 15px 12px rgba(0,0,0,0.22);
  
  
    
}
 



.rotatingText {
  font-family: "Georgia", serif;
  font-style: italic;
  font-size: 18px;
 
}

.rotatingText-adjective {
  font-family: "Open Sans", sans-serif;
  font-size: 50px;
  font-style: normal;
  font-weight: 700;
  left: 0;
  margin-bottom: 0;
  margin-top: 400px;
  opacity: 0;
  position: absolute;
  right: 0;
  color: #703254;
  text-transform: uppercase;
  top: 0;
}

.rotatingText-adjective:nth-of-type(1) {
  animation-name: rotate;
  animation-duration: 1.5s;
  animation-delay: 0.5s;
}

.rotatingText-adjective:nth-of-type(2) {
  animation-name: rotate;
  animation-duration: 1.5s;
  animation-delay: 1.75s;
}

.rotatingText-adjective:nth-of-type(3) {
  animation-name: rotate-last;
  animation-duration: 1.5s;
  animation-delay: 3s;
  animation-fill-mode: forwards;
}

@keyframes rotate {
  0% {
    opacity: 0;
    transform: translate3d(0, 50px, 0);
  }
  
  20%, 80% {
    opacity: 1;
    transform: translate3d(0, 0, 0);
  }
  
  100% {
    opacity: 0;
    transform: translate3d(0, -25px, 0);
  }
}

@keyframes rotate-last {
  0% {
    opacity: 0;
    transform: translate3d(0, 50px, 0);
  }
  
  50%, 100% {
    opacity: 1;
    transform: translate3d(0, 0, 0);
  }
}


.arrow-container {
  width: 60px;
  /* cubic-bezier-easing = sine / mehr Beispiele: https://easings.net/ */
  animation: bounce 1600ms infinite cubic-bezier(0.445, 0.05, 0.55, 0.95);
  cursor: pointer;
  height: 20px;
  left: 50%;
  position:absolute;
  padding-top:30px;
}

.arrow-down {
  height: 6px;
  background: rgb(198, 123, 165);
  transform: rotate(45deg);
  transform-origin: 0% 0%;
  border-radius: 5px;
}
.arrow-down:after {
  content: '';
  position: absolute;
  width: 100%;
  height: 100%;
  bottom: 0;
  left: 100%;
  border-radius: 5px;
  background: rgb(198, 123, 165);
  transform: rotate(-90deg);
  transform-origin: 0% 100%;
}

@keyframes bounce {
50% {
    transform: translateY(-15px);
  }
}





  
  /* .bgimg {
  background-image: url('https://www.plantemoran.com/-/media/images/insights-images/2018/04/thinking-about-becoming-a-smart-city.jpg?h=704&w=1100&la=en&hash=0F4F54BBECD3E501765A064202A24F8851D74E04');
  height: 1000px;
  background-position: center;
  background-size: cover;
}
  
  
  .w3-display-middle{
     position: absolute;
  top: 50%;
  width: 100%;
  text-align: center;
  font-size: 25px;
   
  }
  
  */
  
 .arrow {
  border: solid #703254;
  border-width: 0 3px 3px 0;
  display: inline-block;
  padding: 30px;
  text-align: center;
 
}

.down {
  transform: rotate(45deg);
  -webkit-transform: rotate(45deg);
}

  /*
.rotatingText {
  font-family: "Georgia", serif;
  font-style: italic;
  font-size: 18px;
  text-align: center;
}

.rotatingText-adjective {
  font-family: "Open Sans", sans-serif;
  font-size: 50px;
  font-style: normal;
  font-weight: 700;
  left: 0;
  margin-bottom: 0;
  margin-top: 50px;
  opacity: 0;
  position: absolute;
  right: 0;
  text-align: center;
  text-transform: uppercase;
  top: 0;
}

.rotatingText-adjective:nth-of-type(1) {
  animation-name: rotate;
  animation-duration: 1.5s;
  animation-delay: 0.5s;
}

.rotatingText-adjective:nth-of-type(2) {
  animation-name: rotate;
  animation-duration: 1.5s;
  animation-delay: 1.75s;
}

.rotatingText-adjective:nth-of-type(3) {
  animation-name: rotate-last;
  animation-duration: 1.5s;
  animation-delay: 3s;
  animation-fill-mode: forwards;
}

@keyframes rotate {
  0% {
    opacity: 0;
    transform: translate3d(0, 50px, 0);
  }
  
  20%, 80% {
    opacity: 1;
    transform: translate3d(0, 0, 0);
  }
  
  100% {
    opacity: 0;
    transform: translate3d(0, -25px, 0);
  }
}

@keyframes rotate-last {
  0% {
    opacity: 0;
    transform: translate3d(0, 50px, 0);
  }
  
  50%, 100% {
    opacity: 1;
    transform: translate3d(0, 0, 0);
  }
} 
  
.container1 {
  position: relative;
}

.rotatingText-adjective {
  position: absolute;
  top: 50%;
  width: 100%;
  text-align: center;
  font-size: 18px;
  color: white;
  text-transform: uppercase;
  font-size: 40px;
}

*/
  
  

  
  
    .img-rounded {
  box-shadow: 0 19px 38px rgba(0,0,0,0.30), 0 15px 12px rgba(0,0,0,0.22);
    border-radius: 25px;
  
    
}
 
 .img-rounded {
  opacity: 0.5;
}

.img-rounded:hover {
  opacity: 1.0;
}
  
  ul  {
  
  color: #a54a7b;
  font-weight: bold; 
  margin-left: 10em;
    line-height:4; 
}
  
/*  span {color: rgb(198, 123, 165); 
    padding:50px;
    width:200px;
  } */
  
 
nav > ul > li > a {
    text-decoration: none;
}

.border{
    position:relative;
}
.border:hover::after{
    content:'';
    position:absolute;
    width: 100%;
    height: 0;    
    left:0;
    bottom:0px; 
    border-bottom: 2px solid #000;  
}
  
  
   
  
  
  
#growContainer{
	display: table;
	width:100%;
	height:35%;
  color:white;
}
.grow{
	display: table-cell;
	height:100%;
	width: 25%;
	-webkit-transition:width 500ms;
	-moz-transition:width 500ms;
	transition:width 500ms;
  position: relative;
}
#growContainer:hover .grow{
	width:20%;
}
#growContainer:hover .grow:hover {
	width:40%;
}
 
  
  .img-list{height:100%;
  width:100%;
  } 
  
  .centre{
   position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
    
}
 
 
  
  .gototest {
    height: 150px;
  }
  
</style>
<body>



<div class="container1" style="text-align: center;">
  <img src="https://www.plantemoran.com/-/media/images/insights-images/2018/04/thinking-about-becoming-a-smart-city.jpg?h=704&w=1100&la=en&hash=0F4F54BBECD3E501765A064202A24F8851D74E04"  width="1000" height="1000" class="img1">
 <p>
  <span class="rotatingText-adjective">Lean Startup</span>
  <span class="rotatingText-adjective">Business Studies</span>
  <span class="rotatingText-adjective">Let's Start 🚀</span>
</p>
</div> 
  


  
    <!-- 
  
<div class="bgimg">
  <div class="w3-display-topleft" style="color:white;">
    LGEG
  </div>
  <div class="w3-display-middle">
    <h1  style="color:white;">Lean Startup</h1>
    <hr  style="margin:auto;width:40%">
    <p >or how to test hypotheses around your business idea</p>
  </div>
</div>
   <div class="center1" >Lean Startup</div>
  
<div class="circle"> </div>   --> 
   
  
<p style="text-align:center; color: rgb(198, 123, 165);"><span>To understand the main principles of
Lean Startup, it's better to start with practice.</span></p>

<p style="text-align:center;color: rgb(198, 123, 165);"><span >You decide to open the first pet-friendly cafe where they serve the same food both for pets and pet-owners.</span></p>
<p><br></p>
<div style="text-align: center;"><img src="https://vanillapup.com/wp-content/uploads/2018/08/RedDot-BrewHouse-Dempsey_Vanillapup@2x.jpeg" class="img-rounded" style="font-family: inherit; width: 469.741885625966px; height: 313px;">&nbsp; &nbsp;
&nbsp;<img src="https://eatbook.sg/wp-content/uploads/2019/11/Pet-Friendly-Cafe-The-Garden-Slug-dog-982x1024.jpg" class="img-rounded" style="width: 295.2300098716683px; height: 308px;"></div>
<p></p>
<p><span style="color: rgb(198, 123, 165);"><br></span></p>
<p style="text-align:center; text-size:20;"><span style="color: rgb(198, 123, 165);">What kind of features will you include in it?</span></p>

  <!-- <div class="bigcircle"> </div> 
   


  

  <nav>
    <ul>
        <li><a class="border" href="#">Special menu </a> <img src="https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/240/apple/271/meat-on-bone_1f356.png" class="img-list" >

        </li>
        <li><a class="border" href="#">City centre location </a><img src="https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/240/apple/271/cityscape-at-dusk_1f306.png" class="img-list" >

        </li>
        <li><a class="border" href="#">Gifts for pets </a><img src="https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/240/apple/271/wrapped-gift_1f381.png" class="img-list">

          </li>
        <li><a class="border" href="#">Pretty Logo </a><img src="https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/240/apple/271/cyclone_1f300.png" class="img-list">
        </li>
    </ul>
</nav>
  <p></p>
  <p></p>
  <p></p>
  <p></p> -->
  
  
  <div id="growContainer">
<div class="grow" style="background-color:#703254;"> <div class="centre"><p>Special Menu</p></div> <img src="https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/240/apple/271/meat-on-bone_1f356.png" class="img-list" > </div>
<div class="grow" style="background-color:#823a61;"><div class="centre"><p>City centre location </p></div> <img src="https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/240/apple/271/cityscape-at-dusk_1f306.png" class="img-list" > </div>
<div class="grow" style="background-color:#a54a7b;"><div class="centre"><p>Gifts for pets</p></div> <img src="https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/240/apple/271/wrapped-gift_1f381.png" class="img-list"></div>
<div class="grow" style="background-color:#c379a1;"> <div class="centre"><p>Logo</p></div> <img src="https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/240/apple/271/cyclone_1f300.png" class="img-list"></div>
</div>
  

 <div class="gototest" style="text-align: center; color: rgb(198, 123, 165);">
   <p> </p>
   <p> Answer the question below in the box</p>

  
  
  
 <div class="arrow-container" >
            <div class="arrow-down" ></div>
        </div>
  
  
</body>
</html>
