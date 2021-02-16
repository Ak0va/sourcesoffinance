<!DOCTYPE html>
<html>
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Raleway">
  <body>
    <style>
      body,
  h1,
  h2 {
    font-family: "Raleway", sans-serif
  }

  body,
  html {
    height: 100%
  }

  body {
    margin-left: 5%;
    margin-right: 5%;
  }


input {
  border-radius: 55px;
      text-align: center;
}

select {
border-radius: 55px;
border: solid 2px;
}

.parent {
  display: flex;
  flex-wrap: wrap;
}

.child {
  flex: 1 1 300px;
  border-radius: 55px;
    background: white;
    box-shadow: 5px 5px 4px #898989,
      -5px -5px 4px #ffffff;
    border: 2px;
    border-style: solid;
    text-align: center;
    margin: 15px;
  padding:15px;
}

.child2 {
  flex: 1 1 50px;
  border-radius: 55px;
    background: white;
    box-shadow: 5px 5px 4px #898989,
      -5px -5px 4px #ffffff;
    border: 2px;
    border-style: solid;
    text-align: center;
    margin: 15px;
  padding:15px;
}



.child3 {
  flex: 1 1 15px;
  border-radius: 55px;
    background: white;
    box-shadow: 5px 5px 4px #898989,
      -5px -5px 4px #ffffff;
    border: 2px;
    border-style: solid;
    text-align: center;
    margin: 15px;
  padding:15px;
}

.childquiz {
  flex: 1 1 300px;
  border-radius: 55px;
    background: white;
    box-shadow: 5px 5px 4px #898989,
      -5px -5px 4px #ffffff;
    border: 2px;
    border-style: solid;
    text-align: left;
    margin: 15px;
  padding:25px;
}

.yaxis{
  height:300px;
  width:5px;
    border-radius: 55px;
    background: black;
    border: 2px;
    border-style: solid black;
    text-align: center;
    margin: 40px;
}


.xaxis{
  height:5px;
  width:300px;
    border-radius: 55px;
    background: black;
    border: 2px;
    border-style: solid black;
    text-align: center;
    margin: 40px;
  margin-top:-40px;
}

#revenue, #vcost, #fcost{
  height:5px;
  width:280px;
    border-radius: 55px;
    background: #e9b0df;
    border: 2px;
    border-style: solid #e9b0df;
    text-align: center;
    margin: 40px;
  margin-top:-50px;
    margin-left:45px;
  transform: rotate(-45deg);
  transform-origin: 0 100%;
   position:relative;
}

.revenueimg {
  width:55%;
  height:95%;
}

.revenueimg2 {
  width:15%;
  height:85%;
}

#fcost {
 background: #CD65B3;
   transform: rotate(0deg);
 bottom: 40px;
}

#vcost {
 background: #52C770;
   transform: rotate(-30deg);
bottom: 0px;

}


#bepoint {
 background: black;
bottom: 160px;
left: 158px;
width:10px;
height:10px;
position:relative;
border-radius: 100px;

}

#bedashline {
background: white;
bottom: 160px;
left: 160px;
width:0px;
height:115px;
position:relative;
border-style: dashed;
border-radius: 55px;

}
#bepanswer {
bottom: 150px;
left: 135px;
position:relative;
border-style: dashed;
border-radius: 55px;
text-align: center;
  width:50px;
}


#bedashline2 {
background: white;
bottom: 170px;
left: 150px;
width:115px;
height:15px;
position:relative;
border-left: dashed;
border-bottom: dashed;
border-right: dashed;

}

#bepanswer2 {
bottom: 175px;
left: 235px;
position:relative;
border-style: dashed;
border-radius: 55px;
text-align: center;
  width:50px;
}


#bepanswer3 {
bottom: 160px;
left: 155px;
position:relative;
border-style: dashed;
border-radius: 55px;
text-align: center;
  width:100px;
   background: #52C770;
}


button {
  border-radius: 55px;
border: solid 2px;
  background: #52C770;
}


input {
  border-radius: 55px;
      text-align: center;
      width:auto;
}




  .child0 {
    flex: 1 1 300px;
    background: white;
    text-align: center;

  }

.yaxis2{
  height:300px;
  width:5px;
    border-radius: 55px;
    background: black;
    border: 2px;
    border-style: solid black;
    text-align: center;
    margin: 40px;
}


.xaxis2{
  height:5px;
  width:300px;
    border-radius: 55px;
    background: black;
    border: 2px;
    border-style: solid black;
    text-align: center;
    margin: 40px;
  margin-top:-40px;
}

#revenue2, #vcost2, #fcost2{
  height:5px;
  width:280px;
    border-radius: 55px;
    background: #e9b0df;
    border: 2px;
    border-style: solid #e9b0df;
    text-align: center;
    margin: 40px;
  margin-top:-50px;
    margin-left:45px;
  transform: rotate(-45deg);
  transform-origin: 0 100%;
   position:relative;
}


#fcost2 {
 background: #CD65B3;
   transform: rotate(0deg);
 bottom: 40px;
}

#vcost2 {
 background: #52C770;
   transform: rotate(-30deg);
bottom: 0px;

}

/**/

.overlay {
  position: fixed;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  background: rgba(0, 0, 0, 0.7);
  transition: opacity 500ms;
  visibility: hidden;
  opacity: 0;
  overflow: scroll;
}
.overlay:target {
  visibility: visible;
  opacity: 1;

}

.popup {
  margin: 70px auto;
  padding: 20px;
  background: #fff;
  border-radius: 5px;
  width: 80%;
  position: relative;
  transition: all 5s ease-in-out;

}

.popup h2 {
  margin-top: 0;
  color: #333;
  font-family: Tahoma, Arial, sans-serif;
}
.popup .close {
  position: absolute;
  top: 20px;
  right: 30px;
  transition: all 200ms;
  font-size: 30px;
  font-weight: bold;
  text-decoration: none;
  color: #333;
}
.popup .close:hover {
  color: #06D85F;
}
.popup .content {
  max-height: 30%;
  overflow: auto;
}

@media screen and (max-width: 700px){
  .box{
    width: 70%;
  }
  .popup{
    width: 70%;
  }
}


.highlight{
  color:#CD65B3;
}

.people {
  margin-left:35%;
}

.plus{
  color:#52C770;
  font-weight:bold;
  font-size:100%;
}

.minus{
   color:#CD65B3;
  font-weight:bold;
  font-size:100%;

}


/*Nav bar*/

.highlight {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    background-color: #52C770;
    border-radius: 58px;

  }

  .highlight2 {
    float: left;
  }

  .highlight2 a {
    display: block;
    color: #ffffff;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
  }

  li a:hover:not(.active) {
    background-color: #CD65B3;
  }

  .active {
    background-color: #CD65B3;
  }



    </style>
  <ul class="highlight">
    <li class="highlight2"><a class="active" href="#home">Home</a></li>
    <li class="highlight2"><a href="javascript:if(window.print)window.print()">Print</a></li>
    <li class="highlight2"><a href="mailto:aleksandra.kovaleva.97@gmail.com">Contact Teacher</a></li>
    <li class="highlight2"><a href="#about">Vocabulary</a></li>
  </ul>



     <div class="child0">
    <h4 style="font-weight: bold; font-size:280%; text-align: center;"> PLANNING. <p></p>
      BREAK-EVEN ANALYSIS </h4>
    <h5 style="font-weight: bold; font-size:180%; text-align: center;"> §30 </h5>
  </div>
<div class="parent">
  <div class="child">
     <div class="TR" >
     <span class="TR" style="position:relative; left:-40%; font-weight: bold; top:25px;"> TR </span>
     <div class="yaxis"> </div>
      <div class="xaxis"> </div>
      <div id="revenue"> </div>
      <span class="TR" style="position:relative; font-weight: bold; top:-15px;"> Number of units</span>
     <br>
<input type="range" id="rotaterev" min="0" max="90" value="7" oninput="rotaterev()" />  <span>Price</span>
       </div>
  </div>
  <div class="child">
  <p style="color:#e9b0df; font-weight:900;">
Revenue
</p>
<p>
Revenue is the value of output sold by a business. For example, the money a shoe retailer makes from selling its shoes before accounting for any expenses is its revenue. The formula of total revenue (TR) is pretty simple:   </p><p style="color:#e9b0df; font-weight:900;">
  TR = P * Q
  </p>

  <p> A total revenue curve is the relation between the total revenue a firm receives from production and the quantity of output produced. That's why on the y-axis we have TR and on the x-axis we have Q.
    </p>
   <p> Since producers can sell all they produce, and the price is fixed, revenue will increase with each good sold at a constant rate. That explains the shape of the Total Revenue curve (TR). If the price per unit sold increases, TR also increases its slope, because for each unit sold a seller receives more money!   </p> <br>
    Try to change the slider (on the left) and see what will happen with a curve ↩️
  </div>
</div>
 <p style="text-align:center; padding-left:10%; padding-right:10%;"> When you become a businessman or businesswoman, the most important question that you will ask yourself is how to BOOST your sales? How to attract more customers? How to improve sales revenue? All of those can be chieved in a anumber of ways...
</p> <p style="text-align:center; padding-left:10%; padding-right:10%;">
If business has some unused capacity, it will try to improve sales volume. Once again Volume is literally how much a business sells, so Q of units. The formula of TR is still P*Q, so if you want to increase TR, always start with Q. So what can potentially increase Q?
</p>
<p style="text-align:center; padding-left:10%; padding-right:10%;"> Click on the picture to see: </p>
<div class="parent">
  <div class="child2">
     <a href="#popup1">
    <img  class="revenueimg" src="https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/240/apple/271/megaphone_1f4e3.png"> </a></div>
    <div class="child2">
       <a href="#popup2">
    <img class="revenueimg" src="https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/240/apple/271/wrapped-gift_1f381.png"> </a> </div>
        <div class="child2">
              <a href="#popup3">
    <img class="revenueimg" src="https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/240/apple/271/direct-hit_1f3af.png"> </a></div>
   <div class="child2">
         <a href="#popup4">
     <img class="revenueimg" src="https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/240/apple/271/shopping-bags_1f6cd-fe0f.png"> </a>  </div>
   <div class="child2">
         <a href="#popup5">
     <img class="revenueimg" src="https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/240/apple/271/heart-with-ribbon_1f49d.png"> </a>
   </div>
  </div>

 <!--Popups-->
   <div id="popup1" class="overlay">
<div class="popup">
<h2>Advertisement</h2>
<a class="close" href="#">&times;</a>
<div class="content">
Advertisement helps raise brand awareness so that more people will get to know about the company and products it makes. So, the sales volume may potentially increase!
</div>
</div>
</div>
   <div id="popup2" class="overlay">
<div class="popup">
<h2>Promotion</h2>
<a class="close" href="#">&times;</a>
<div class="content">
Businesses can choose from a wide range of different methods of promotion to increase sales volume. Examples might be coupons, sponsorship, free gifts, loyalty cards, merchandising and direct mailing.
</div>
</div>
</div>
   <div id="popup3" class="overlay">
<div class="popup">
<h2>Improved targeting</h2>
<a class="close" href="#">&times;</a>
<div class="content">
Businesses are likely to increase sales volumes if their advertising and promotion is more targeted. That means that it should be aimed more accurately at the people who are most likely to purchase the product. For example, placing cosmetics commercial in a woman magazine, e.g. Vogue or Cosmopolitan.
</div>
</div>
</div>
   <div id="popup4" class="overlay">
<div class="popup">
<h2>Extend product range</h2>
<a class="close" href="#">&times;</a>
<div class="content">
Incresing the range of products for sale may also increase sales volume. For example, a chips manufacturer like "Lays" always tries to attract new customers with new flavours (like caviar or vasabi)
</div>
</div>
</div>
   <div id="popup5" class="overlay">
<div class="popup">
<h2>Develop relationship with customers</h2>
<a class="close" href="#">&times;</a>
<div class="content">
By engaging more with customer, businesses might be able to improve customers retention and encourage repeat purchases. This will increase Q. To do this a business has to communicate effectively with customers, learn as much as possible about their clients, response effectively to complaints, build trust and stay in regular touch.
</div>
</div>
</div>
   <!--Popups-->
   <p style="text-align:center; padding-left:10%; padding-right:10%;"> All of those methods may increase Q of products sold... However, TR can be also increased with price change. Click on these pictures to investigate them!
</p>
 <div class="parent">
  <div class="child3">
     <a href="#popup6">
    <img  class="revenueimg2" src="https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/240/apple/271/p-button_1f17f-fe0f.png"> </a></div>
    <div class="child3">
       <a href="#popup7">
    <img class="revenueimg2" src="https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/240/apple/271/package_1f4e6.png"> </a> </div>
  </div>
    <div id="popup6" class="overlay">
<div class="popup">
<h2>Price change</h2>
<a class="close" href="#">&times;</a>
<div class="content">
A business can increase revenue by raising price if demand is inelastic. However, if demand is elastic, a business will decrease the price but increase TR.
</div>
</div>
</div>
<div id="popup7" class="overlay">
<div class="popup">
<h2>Complements</h2>
<a class="close" href="#">&times;</a>
<div class="content">
A business can generate higher revenue if it also persuades customers to buy additional services or products that are related to the core product. For example, shoe store also selling shoe-cleaning materials and other footwear accessories.
</div>
</div>
</div>



<div class="parent">
  <div class="child">
     <div class="TR">
     <span class="TR" style="position:relative; left:-40%; font-weight: bold; top:25px;"> VC </span>
     <div class="yaxis"> </div>
      <div class="xaxis"> </div>
      <div id="vcost"> </div>
      <span class="TR" style="position:relative; font-weight: bold; top:-15px;"> Number of units</span>
     <br>
<input id="rotatevc" type="range" min="0" max="90" value="7" oninput="rotatevc()"  /> <span>VC per unit</span>
       </div>
  </div>
  <div class="child">

  <p style="color:#52C770; font-weight:900;">
    Variable cost </p><p>
Variable costs increase directly as output rises. For example, a baker will require more flour if more bread is produced. Raw materials are just one example of variable cost. Others might include packaging, fuel and wages. If the firm doesn't produce anything then VC is zero.
</p>
<p>
    <p style="color:#52C770; font-weight:900;">
  TVC = VC per unit * Q
  </p>
    Try to change the slider (on the left) and see what will happen with a curve ↩️
  </div>
</div>


 <div class="parent">
  <div class="child">
     <div class="TR">
     <span class="TR" style="position:relative; left:-40%; font-weight: bold; top:25px;"> FC </span>
     <div class="yaxis"> </div>
      <div class="xaxis"> </div>
      <div id="fcost"> </div>
      <span class="TR" style="position:relative; font-weight: bold; top:-15px;"> Number of units</span>
     <br>
<input type="range" min="0" max="90" value="7" oninput="rotate(this.value)" onchange="rotate(this.value)" /> <span>FC per unit</span>
       </div>
  </div>
  <div class="child">

 <p style="color:#CD65B3; font-weight:900;">
    Fixed cost </p> <p>
Fixed costs are expenses that remain the same regardless of production output. Whether a firm makes sales or not, it must pay its fixed costs, as these costs are independent of output.
</p>
Given that total fixed costs (TFC) are constant as output increases, the curve is a horizontal line on the cost graph.<p>
So that's why if production is 0, total fixed cost is $3. If  production is 10, total fixed cost is $3. If production is boosted to a billion, then total fixed cost is still $3.
</p>
    Try to change the slider (on the left) and see what will happen with a curve ↩️
  </div>
</div>


<div class="parent">
<div class="childquiz">
<h2 style="text-align:center;">Matching exercise</h2>
<p>Listed below are various terms describing fixed and variable costs. Consider whether each term is most likely to describe fixed costs or variable costs.</p>
<form name="Q1Form" action="dummy">
<table class="qinput" cellpadding="4" summary="Layout table" dir="ltr">
<tr>
<td width="4%" valign="top">a)</td>
<td width="62%" valign="top"><label for="Q1Combo1">
  Raw materials, direct labor, delivery on purchased goods</label></td>
<td width="34%" valign="top"><select name="Q1Combo1" id="Q1Combo1" onchange="check1()"><option>Choose...</option>
<option value="fc">Fixed costs</option>
<option value="vc" >Variable costs</option></select>
  <input type="text" id="res1" size="auto">
</td>
</tr>
<tr>
<td width="4%" valign="top">b)</td>
<td width="62%" valign="top"><label for="Q1Combo2">
  These costs are represented by a sloping line on the total cost graph</label></td>
<td width="34%" valign="top"><select name="Q1Combo2" id="Q1Combo2" onchange="check2()"><option>Choose...</option>
<option value="fc">Fixed costs</option>
<option value="vc" >Variable costs</option></select>
  <input type="text" id="res2" size="auto">
</td>
</tr>
<tr>
<td width="4%" valign="top">c)</td>
<td width="62%" valign="top"><label for="Q1Combo3">
  The additional cost of producing an additional unit will be exactly the same as for all the previous units of production</label></td>
<td width="34%" valign="top"><select name="Q1Combo3" id="Q1Combo3" onchange="check3()"><option>Choose...</option>
<option value="fc">Fixed costs</option>
<option value="vc" >Variable costs</option></select>
  <input type="text" id="res3" size="auto">
</td>
</tr>
<tr>
<td width="4%" valign="top">d)</td>
<td width="62%" valign="top"><label for="Q1Combo4">
  Production overheads</label></td>
<td width="34%" valign="top"><select name="Q1Combo4" id="Q1Combo4" onchange="check4()"><option>Choose...</option>
<option value="fc">Fixed costs</option>
<option value="vc" >Variable costs</option></select>
  <input type="text" id="res4" size="auto">
</td>
</tr>
<tr>
<td width="4%" valign="top">e)</td>
<td width="62%" valign="top"><label for="Q1Combo5">
  These costs are represented by a horizontal line on the total costs graph</td>
<td width="34%" valign="top"><select name="Q1Combo5" id="Q1Combo5" onchange="check5()"><option>Choose...</option>
<option value="fc">Fixed costs</option>
<option value="vc" >Variable costs</option></select>
  <input type="text" id="res5" size="auto">
</td>
</tr>
<tr>
<td width="4%" valign="top">f)</td>
<td width="62%" valign="top"><label for="Q1Combo6">
 Internet, telephone bills and electricity</label></td>
<td width="34%" valign="top"><select name="Q1Combo6" id="Q1Combo6" onchange="check6()"><option>Choose...</option>
<option value="fc">Fixed costs</option>
<option value="vc" >Variable costs</option></select>
  <input type="text" id="res6" size="auto">
</td>
</tr>
<tr>
<td width="4%" valign="top">g)</td>
<td width="62%" valign="top"><label for="Q1Combo7">
  Increase or decrease directly in line with rises and falls in production</label></td>
<td width="34%" valign="top"><select name="Q1Combo7" id="Q1Combo7" onchange="check7()"><option>Choose...</option>
<option value="fc">Fixed costs</option>
<option value="vc" >Variable costs</option></select>
  <input type="text" id="res7" size="auto">
</td>
</tr>
<tr>
<td width="4%" valign="top">h)</td>
<td width="62%" valign="top"><label for="Q1Combo8">
 Steel included in an automobile or timber used to construct a house</label></td>
<td width="34%" valign="top"><select name="Q1Combo8" id="Q1Combo8" onchange="check8()"><option>Choose...</option>
<option value="fc">Fixed costs</option>
<option value="vc" >Variable costs</option></select>
  <input type="text" id="res8" size="auto">
</td>
</tr>
<tr>
<td width="4%" valign="top">i)</td>
<td width="62%" valign="top"><label for="Q1Combo9">
Taxes and insurance </label></td>
<td width="34%" valign="top"><select name="Q1Combo9" id="Q1Combo9" onchange="check9()"><option>Choose...</option>
<option value="fc">Fixed costs</option>
<option value="vc" >Variable costs</option></select>
  <input type="text" id="res9" size="auto">
</td>
</tr>
<tr>
<td width="4%" valign="top">j)</td>
<td width="62%" valign="top"><label for="Q1Combo10">
  Do not change when the number of units produced changes  </label></td>
<td width="34%" valign="top"><select name="Q1Combo10" id="Q1Combo10" onchange="check10()"><option>Choose...</option>
<option value="fc">Fixed costs</option>
<option value="vc" >Variable costs</option></select>
  <input type="text" id="res10" size="auto"></td>

</tr>

</table>

</form>
</td>
</tr></table>
     </div>

</div>
<p></p>
<p style="text-align:center; padding-left:10%; padding-right:10%;">Now let's plot all curves on one graph...</p>
<div class="parent">
  <div class="child">
         <div class="TR">
     <span class="TR" style="position:relative; left:-40%; font-weight: bold; top:25px;"> TR, TC </span>
     <div class="yaxis2"> </div>
      <div class="xaxis2"> </div>
      <div id="revenue2" style="display:none;"> </div>
      <div id="vcost2" style="display:none;"> </div>
      <div id="fcost2" style="display:none;"> </div>
      <div id="bepoint" style="display:none;"> </div>
       <div id="bedashline" style="display:none;"> </div>
      <div id="bepanswer" style="display:none;"> 500 </div>
       <div id="bepanswer2" style="display:none;"> 700 </div>
<div id="bedashline2" style="display:none;"> </div>
 <div id="bepanswer3" style="display:none;"> MOS = 200 </div>
      <p class="TR"> Number of units</p>
     <br>

       </div>
 </div>
   <div class="child">
  <p id="1">  First, let's plot Fixed Cost curve because before starting selling the most delicious shaurma in Moscow, we need to find a perfect place and pay for rent. Click the button to get the curve on the graph! <br><br>
       <button type="button" onclick="showfcost()">Let's do it!</button> <br> </p>
<p id="2" style="display:none;"> Now much better! What else do we need? Probably some pita, veggies and of course meat from... Nobody actually knows what it's made from... Anyway, let's also buy our key ingredients! Since the amount of ingredients that we are gonna buy heavily depends on the amount of shaurmas sold, apparently it will be our variable cost...  <br>
First, let's plot Variable Cost curve  <br><br>
   <button type="button" onclick="showvcost()">Let's plot it!</button> <br> </p>
<p id="3" style="display:none;"> Now we have two curves in front of us: Variable Cost Curve and Fixed Cost Curve... Do you remember the formula of TC? Exactly! TC=FC+VC. So in order to plot our total cost curve we need to do move VC curve (green curve) to the point where FC starts. Why? Because Total Cost curve shows us how  <br> <br>
   <button type="button" onclick="movevcost()">Let's do it!</button>  </p>
 <p id="4" style="display:none;">   And then you start dreaming about how much money you are gonna make... How you're buying a BMW, eat cookies from Laduree and drink extra-berry smoothies... The time will come and this is gonna happen, but for now need to define how much of shaurmas you actually need to sell per month to at least not incur losses. Let's plot TR curve and see how it goes...  <br> <br>
   <button type="button" onclick="showrevenue()">Let's do it!</button>  </p>
  <p id="5" style="display:none;">
Alright... The good news is that at lest at some point our TR and TC intersect, that's already nice. Can you calculate what is breakeven point for our business if we know the following:<br><br>

FC = 30,000<br><br>
VC = 85 <br><br>
P = 145 (I literally googled average price for shaurma in Moscow...Don't judge me!)<br><br>

Forget about all the curves anf graphs! thibk like a real businessman. How many shaurmas do you need to sell to get zero profit  <br><br>
 <input type="text" id="answer">
 <button type="button" onclick="checkanswer()">Check!</button> </p>
 <p id="6" style="display:none;">
   Now let's assume the best case scenario - you are selling much more than you expected. Say, 700 shaurmas... God! That's a lot! And now you want to calculate the amount of shaurmas by which your company's sales could decrease before you will have no profit - simply saying, you want to calculate Margin of Safety (MOS). Remember to have profit equal to zero, you need to sell 500 shaurmas and you've sold 700 shaurmas.  To calculate MOS you need to substract your BEP from the amount of units sold in reality. How much would that be?  <br><br>
 <input type="text" id="answer2">
 <button type="button" onclick="checkanswer2()">Check!</button></p>

 </div>
</div>
<script>
  function rotaterev() {
  var z = document.getElementById("rotaterev").value;
  document.getElementById('revenue').style.transform="rotate(" + -z + "deg)";
}

function rotatevc() {
  var z = document.getElementById("rotatevc").value;
  document.getElementById('vcost').style.transform="rotate(" + -z + "deg)";
}


function showvcost() {
   document.getElementById('vcost2').style.display = "block";
   document.getElementById('3').style.display = "block";
}

function showfcost() {
   document.getElementById('fcost2').style.display = "block";
   document.getElementById('2').style.display = "block";
}

function movevcost() {
 document.getElementById('vcost2').style.top="-45px";
  document.getElementById('4').style.display = "block";
}

function showrevenue() {
   document.getElementById('revenue2').style.display = "block";
    document.getElementById('5').style.display = "block";
}

function checkanswer() {
   document.getElementById('6').style.display = "block";
   document.getElementById('bepoint').style.display = "block";
   document.getElementById('bedashline').style.display = "block";
   document.getElementById('bepanswer').style.display = "block";
}

function checkanswer2() {
   document.getElementById('bepanswer2').style.display = "block";
   document.getElementById('bedashline2').style.display = "block";
   document.getElementById('bepanswer3').style.display = "block";
}

function check1() {
 var val = document.getElementById('Q1Combo1').value;
 if(val=='vc') {
  document.getElementById('res1').value = "Correct";
 } else {
  document.getElementById('res1').value = "Incorrect";
 }
}

function check2() {
 var val = document.getElementById('Q1Combo2').value;
 if(val=='vc') {
  document.getElementById('res2').value = "Correct";
 } else {
  document.getElementById('res2').value = "Incorrect";
 }
}

function check3() {
 var val = document.getElementById('Q1Combo3').value;
 if(val=='fc') {
  document.getElementById('res3').value = "Correct";
 } else {
  document.getElementById('res3').value = "Incorrect";
 }
}

function check4() {
 var val = document.getElementById('Q1Combo4').value;
 if(val=='fc') {
  document.getElementById('res4').value = "Correct";
 } else {
  document.getElementById('res4').value = "Incorrect";
 }
}

function check5() {
 var val = document.getElementById('Q1Combo5').value;
 if(val=='fc') {
  document.getElementById('res5').value = "Correct";
 } else {
  document.getElementById('res5').value = "Incorrect";
 }
}

function check6() {
 var val = document.getElementById('Q1Combo6').value;
 if(val=='fc') {
  document.getElementById('res6').value = "Correct";
 } else {
  document.getElementById('res6').value = "Incorrect";
 }
}

function check7() {
 var val = document.getElementById('Q1Combo7').value;
 if(val=='vc') {
  document.getElementById('res7').value = "Correct";
 } else {
  document.getElementById('res7').value = "Incorrect";
 }
}

function check8() {
 var val = document.getElementById('Q1Combo8').value;
 if(val=='vc') {
  document.getElementById('res8').value = "Correct";
 } else {
  document.getElementById('res8').value = "Incorrect";
 }
}

function check9() {
 var val = document.getElementById('Q1Combo9').value;
 if(val=='fc') {
  document.getElementById('res9').value = "Correct";
 } else {
  document.getElementById('res9').value = "Incorrect";
 }
}

function check10() {
 var val = document.getElementById('Q1Combo10').value;
 if(val=='fc') {
  document.getElementById('res10').value = "Correct";
 } else {
  document.getElementById('res10').value = "Incorrect";
 }
}



</script>
</body>
</html>
