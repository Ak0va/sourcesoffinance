
<html>
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Raleway">
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
    margin-left: 15%;
    margin-right: 15%;
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

  }

  /*Topic of the lesson*/

  .child0 {
    flex: 1 1 300px;
    background: white;
    text-align: center;

  }

  /*internal finance*/


  .parent {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
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
  }




  .text {

    color: white;
    font-size: 20px;
    position: absolute;
    top: 50%;
    left: 50%;
    -webkit-transform: translate(-50%, -50%);
    -ms-transform: translate(-50%, -50%);
    transform: translate(-50%, -50%);
    text-align: center;
  }

  p {
    font-size: 18px;
    text-align: left;
    padding: 0px 20px;
  }



  .highlightword {
    color: #CD65B3;
    font-weight: bold;

  }


  /*table advantages and disadvantages*/
  table,
  th,
  td {
    border: 1px solid white;
    padding: 15px;
    border-radius: 15px;
    text-align: center;
  }


  .th1 {
    background-color: #ACE2AE;
    border: 2px solid black;
  }

  .th2 {
    background-color: #EFD1EE;
    border: 2px solid black;
  }


  /*Game #1*/



  .boy1 {
    position: relative;
    display: grid;
    place-items: center;
    margin: auto;
    width: 80%;
    height: auto;
    margin-left: 10%;
    margin-top: 5%;

  }


  .answer {
    text-align: center;


  }

  .answer2 {
    margin-left: 10%;
    margin-top: 45%;
    writing-mode: horizontal-tb;

  }

  .parent2 {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    margin: 15px;
  }

  .child2 {

    flex: 1 1 300px;
    border-radius: 58px;
    background-color: #EFD1EE;
    box-shadow: 5px 5px 4px #898989,
      -5px -5px 4px #ffffff;
    border: 2px;
    border-style: solid;
    text-align: center;
    margin: 15px;
    padding: 15px;
  }

  .child3 {

    flex: 1 1 300px;
    border-radius: 58px;
    background-color: #CE73CA;
    box-shadow: 5px 5px 4px #898989,
      -5px -5px 4px #ffffff;
    border: 2px;
    border-style: solid;
    text-align: center;
    margin: 15px;
    padding: 15px;
  }

  .child4 {

    flex: 1 1 300px;
    border-radius: 58px;
    background-color: #65CD80;
    box-shadow: 5px 5px 4px #898989,
      -5px -5px 4px #ffffff;
    border: 2px;
    border-style: solid;
    text-align: center;
    margin: 15px;
    padding: 15px;
  }

  .text1 {
    background-color: #ffffff;
    display: inline-block;
    border-radius: 20px;
    margin: 15px;
    padding: 15px;
    justify-content: center;


  }

  .picboy1 {
    background-color: #ffffff;
    display: inline-block;
    border-radius: 100px;
    margin: 15px;
    padding: 15px;
    justify-content: center;


  }

  /*Quiz*/


  .costs {
    margin-left: 10px;
  }

  #quiz {

    background: #EFD1EE;
    padding: 10px 20px 10px 30px;
    width: auto;
    border-radius: 58px;
    box-shadow: 5px 5px 4px #898989,
      -5px -5px 4px #ffffff;
    border-style: solid;
    margin: 20px;


  }

  input {
    margin-bottom: 20px;
    display: inline;
    margin-left: 15px;
  }

  #textbox {
    height: 25px;
    font-size: 16px;
    border-radius: 5px;
    border: none;
    padding-left: 5px;
  }


  #button {
    background: #72db77;
    border: none;
    border-radius: 5px;
    padding: 10px;
    color: white;
    font-size: 16px;
    transition-duration: .5s;
    margin-top: 15px;
  }



  #button:hover {
    background: white;
    border: 1px #ACE2AE;
    color: black;
    cursor: pointer;

  }

  #after_submit {
    visibility: hidden;
    background: #ff5459;
    padding: 10px 20px 10px 20px;
    width: 400px;
    border-radius: 20px;
    float: left;
    margin-left: 40%;
    margin-top: 20px;
    font-size: 30px;


  }

  #picture {
    width: 375px;
    height: 245px;
  }



  #mc {
    display: inline;
  }









  /*Free response*/
  textarea {
    width: 90%;
    height: 150px;
    padding: 12px 20px;
    box-sizing: border-box;
    border: 2px solid black;
    border-radius: 15px;
    background-color: #f8f8f8;
    font-size: 16px;
    resize: none;
    margin-left: -4%;

  }

  .child5 {
    flex: 1 1 300px;
    border-radius: 55px;
    background: white;
    box-shadow: 5px 5px 4px #898989,
      -5px -5px 4px #ffffff;
    border: 2px;
    border-style: solid;
    text-align: center;
    margin: 5% 3%;
    padding: 3%
  }

  /**/
</style>

<body>

  <ul class="highlight">
    <li class="highlight2"><a class="active" href="#home">Home</a></li>
    <li class="highlight2"><a href="javascript:if(window.print)window.print()">Print</a></li>
    <li class="highlight2"><a href="mailto:aleksandra.kovaleva.97@gmail.com">Contact Teacher</a></li>
    <li class="highlight2"><a href="#about">Vocabulary</a></li>
  </ul>



  <div class="child0">
    <h4 style="font-weight: bold; font-size:280%; text-align: center;"> PLANNING. <p></p>
      INTERNAL FINANCE </h4>
    <h5 style="font-weight: bold; font-size:180%; text-align: center;"> §23-25 </h5>
  </div>




  <p>Internal sources of finance</p>
  <p>Internal sources of finance refer to money that comes from within a business. There are several internal methods a business can use, including owners capital, retained profit and selling assets.</p>



  <div class="parent">
    <div class="child">
      <img src="https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/240/apple/271/money-bag_1f4b0.png" alt="Avatar" class="image">
      <p style="text-align:center;">Owners capital refers to money invested <span class="highlightword"> by the owner </span> of a business. This often comes from their personal savings. Personal savings is money that has been saved up by an
        entrepreneur. </p>
    </div>



    <div class="child"><img src="https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/240/apple/271/credit-card_1f4b3.png" alt="Avatar" class="image">
      <p style="text-align:center;">Retained profit is when a <span class="highlightword"> business makes a profit </span>, it can leave some or all of this money in the business and reinvest it in order to expand. </p>
    </div>




    <div class="child"><img src="https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/240/apple/271/office-building_1f3e2.png" alt="Avatar" class="image">
      <p style="text-align:center;">Selling assets involves <span class="highlightword"> selling products owned by the business </span> (for example, machinery, equipment, and excess stock). This may be used when either a business no longer has a use
        for the product or they need to raise money quickly.</p>
    </div>
  </div>


  <p> </p>


  <table style="width:100%">
    <tr>
      <th class="th1">Advantages</th>
      <th class="th2">Disadvantages</th>
    </tr>
    <tr>
      <td>The capital is available immediately - there is no time delay between identifying a need to finance and obtaining it. For instance, retained profit will be in the bank account ready and waiting. Assets can be sold quickly if the price is
        competitive. </td>
      <td>Internal finance is cheap - there are no interest payments, which means that costs will be lower and profit higher. Also there are no administration costs.</td>
    </tr>
    <tr>
      <td>Internal finance can be limited - a business may not be sufficiently profitable to use retained profit or may not have unwanted assets to sell. Also, the current owners may not have any personal resources to contribute. </td>
      <td>Internal sources of finance cannot be subtracted from business profits to reduce tax owed. If external finance is used, the interest paid on a loan or leasing charges for assets, for example, can be treated as a business cost and subtracted
        from business profits to reduce tax owed.</td>
    </tr>
  </table>

  <p></p>




  <p> Now let's play a game! Try to identify which one of the finance source the entrepreneur used in one's business </p>



  <div class="parent2">
    <div class="child2">
      <div class="picboy1"> <img class="boy1" src="https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/240/apple/271/man-office-worker-light-skin-tone_1f468-1f3fb-200d-1f4bc.png"> </div>
      <div class="text1">
        <p> Mr John:</p>
        <p> Hello! I'm plannig to open a bakery. That's why I want to sell my car to invest in the business. I hope $300,000 will be enough... Wish me luck!</p>
      </div>
      <input id="button" type="button" name="answer" value="Show the answer" onclick="showDiv()" />
      <div id="welcomeDiv" style="display:none;margin-top: 15px;" class="answer_list"> Owner's capital </div>
    </div>


    <div class="child3">
      <div class="picboy1"> <img class="boy1" src="https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/240/apple/271/woman-raising-hand-light-skin-tone_1f64b-1f3fb-200d-2640-fe0f.png"> </div>
      <div class="text1">
        <p> Mrs Helen:</p>
        <p> Hi guys! Recently my hairdressing salon was popping. After lockdown ladies came back to get pretty. Gotta buy some new equipment and two leather chairs. </p>
      </div>
      <input id="button" type="button" name="answer" value="Show the answer" onclick="showDiv2()" />
      <div id="welcomeDiv2" style="display:none;margin-top: 15px;" class="answer_list"> Retained profit </div>
    </div>


    <div class="child4">
      <div class="picboy1"> <img class="boy1" src="https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/240/apple/271/man-judge-medium-light-skin-tone_1f468-1f3fc-200d-2696-fe0f.png"> </div>
      <div class="text1">
        <p> Mr Bob:</p>
        <p> Hey there! Business hasn't been successful because of covid... Clients are not coming back in my local cafe. Gotta sell all the equipment to pay my staff.</p>
      </div>
      <input id="button" type="button" name="answer" value="Show the answer" onclick="showDiv3()" />
      <div id="welcomeDiv3" style="display:none;margin-top: 15px;" class="answer_list"> Selling assets </div>
    </div>

  </div>




  <form id="quiz" name="quiz">


    <p class="questions">Significant benefits of a retained profit are</p>
    <input id="textbox" type="text" name="question1"> <span class="costs"> costs </span>
    <br>
    <input id="textbox" type="text" name="question2"> <span class="costs"> flexibility </span>

    <p class="questions">Which one is an example of an internal source of finance?</p>
    <input type="radio" id="mc" name="question3" value="Mortgage"> Mortgage<br>
    <input type="radio" id="mc" name="question3" value="Government grant"> Government grant<br>
    <input type="radio" id="mc" name="question3" value="Sale of surplus assets"> Sale of surplus assets<br>
    <input type="radio" id="mc" name="question3" value="Leasing"> Leasing<br>

    <p class="questions">What is a meaning of retained profit?</p>

    <input type="radio" id="mc" name="question4" value="Profit paid to shareholders"> Profit paid to shareholders<br>
    <input type="radio" id="mc" name="question4" value="Profit made by the business"> Profit made by the business<br>
    <input type="radio" id="mc" name="question4" value="Profit reinvested in the business"> Profit reinvested in the business<br>


    <input id="button" type="button" value="I'm finished!" onclick="check();">


  </form>

  <!--
<div id = "after_submit">
<p id = "number_correct"></p>
<p id = "message"></p>
<img id = "picture">
</div> -->

  <div class="child5">
    <img src="https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/240/apple/271/hotel_1f3e8.png" alt="Avatar" class="image">
    <img src="https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/240/apple/271/sun_2600-fe0f.png" alt="Avatar" class="image">
    <img src="https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/240/apple/271/tropical-drink_1f379.png" alt="Avatar" class="image">
    <p> Muscat Interior Design (MID) was set up in 2010 by Qasim AI-Saadi. He worked for a top interior design company in New York for 10 years. However, the US company he worked for was taken over, and the integration of the two businesses meant
      that Qasim’s services were no longer required. He received a very attractive redundancy package and decided to return home to Oman. Indeed his ambition was always to return to the Middle East and start his own design business. Qasim is a
      talented designer and invested OMR 15,000 of his own money to set up the venture. The first few years were difficult. However, Qasim and his small team of highly skilled decorators eventually earned the reputation in the city of Muscat for
      producing high-quality interior designs and installation. The company specialized in bedroom designs and started it to win some highly profitable contracts from hotel developers </p>
    <p>
      In 2017, MID won a contract to refit 30 rooms in a city hotel development. The contract was accepted by Qasim but he knew that the business would need to raise a further OMR 25,000 to find the purchase of some specialist equipment and some
      high-quality imported raw materials. He would also need to meet the cost of recruiting another six or seven employees. Qasim was very keen to raise the funds internally even if it meant selling one or two vehicles owned by the business. Qasim
      didn't want to the company to go into debt, owing money to investors and creditors. He wanted the business to be self-financing. </p>
    <p>
      Figure 1 shows the profit made by the business between 2010 and 2016. Qasim is considering the use of some retained profit to finance the new contract.
    </p>
    <p>a) Define internal finance. <span style="font-weight: bold;">(2 marks)</span></p>
    <form>
      <textarea>Some text...</textarea>
    </form>
    <p> </p>
    <p> b) Explain how Qasim might have raised the initial capital to start the business in 2010. <span style="font-weight: bold;">(4 marks)</span>
    </p>
    <form>
      <textarea>Some text...</textarea>
    </form>
    <p> </p>
    <p>c) Explain the opportunity cost to MID of using retained profit for financing business activity. <span style="font-weight: bold;">(4 marks)</span></p>
    <form>
      <textarea>Some text...</textarea>
    </form>
    <p> </p>
    <p>d) Assess Qasim’s decision to use internal finance to fund the new contact in this case. <span style="font-weight: bold;">(10 marks)</span> </p>
    <form>
      <textarea>Some text...</textarea>
    </form>
    <p> </p>


  </div>






  <script>
    function check() {

      var question1 = document.quiz.question1.value;
      var question2 = document.quiz.question2.value;
      var question3 = document.quiz.question3.value;
      var question4 = document.quiz.question4.value;
      var correct = 0;


      if (question1 == "lower") {
        correct++;
      }
      if (question2 == "higher") {
        correct++;
      }
      if (question3 == "Sale of surplus assets") {
        correct++;
      }
      if (question4 == "Profit reinvested in the business") {
        correct++;
      }

      var pictures = ["🤩", "🧐", "🧐", "🤪"];
      var messages = ["Great job!", "That's just okay", "That's just okay", "You really need to do better"];
      var score;

      if (correct == 0) {
        score = 3;
      }

      if (correct > 1 && correct < 2) {
        score = 2;
      }

      if (correct > 2 && correct < 3) {
        score = 1;
      }

      if (correct == 4) {
        score = 0;
      }

      document.getElementById("after_submit").style.visibility = "visible";

      document.getElementById("message").innerHTML = messages[score];
      document.getElementById("number_correct").innerHTML = "You got " + correct + " correct.";
      document.getElementById("picture").src = pictures[score];
    }

    /*********/
    function showDiv() {
      document.getElementById('welcomeDiv').style.display = "block";
    }

    function showDiv2() {
      document.getElementById('welcomeDiv2').style.display = "block";
    }

    function showDiv3() {
      document.getElementById('welcomeDiv3').style.display = "block";
    }
  </script>

  <p> But there are many more sources of external finance </p>


</body>

</html>
