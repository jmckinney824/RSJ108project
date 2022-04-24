    <title>Jackie McKinney's Instruction Tips</title>
  <script src="https://thimble.mozilla.org/resources/remix/index.js" type="text/javascript"></script>
</head>
  <body>

    <!--
TASK 1
=======================================================
Replace the header contents: 
- replace logo with an image of your own (100px x 100px and containing transparency). 
- replace 'Firstname Lastname' with your name
- replace 'Name of Site' with a new site name
-->

    <header>          
      <img src="https://flic.kr/p/7Krb1i" width="100" align="right" height="100" alt="KH_monogram">            
      <h1>Jackie McKinney's Instruction Tips</h1>
      <h3>An Instruction Challenge for JOUR108</h3>

    </header>

    <div class="wrapper">

      <article>            
        <!--
TASK 2
=======================================================
Add your introduction to your step-by-step-guide, including a title, time required to complete the activity, and a rating of how awesome the activity is. 
** Be careful to keep all the HTML tags intact when you are changing the text.
-->         
        <div class="introduction">

          <div class="information">
            <h1>How to make an awesome ...</h1>

            <hr>
            <p><b>Assembly time:</b> 30 minutes<br>
              <b>Awesome rating:</b> 10% awesome</p>
            <hr>

            <p>Are you wondering how to make a cool rocket that can easily surpass a baking soda-vinegar rocket? It's really fun to make. Why don't you try to make it yourself? Follow the steps and you'll make a great rocket!</p>

          </div>

          <aside>

            <!--
TASK 3
=======================================================
Add your Things You'll Need. 
** Be careful to keep all the HTML tags intact when you are changing the text.
-->         
            <ul class="list-of-items">
              <li><h2>Things You'll Need</h2></li>
              <li>Bottle</li>
              <li>Cardboard</li>
              <li>Hand pump (bicycle)</li>
              <li>Cork (vintage wines)</li>
              <li>Duct Tape</li>
              <li>Water</li>
            </ul>
          </aside>
        </div>


        <!--
TASK 4
=======================================================
Add your steps. When you need a new step, copy and paste all of the code of an entire step, then edit the contents.
-->         
        <ol class="step-by-step">

          <!-- A new step -->
          <li>
            <div class="content">
              <h3>Invert the bottle and cut three flippers of cardboard.</h3>
              <p>This is necessary to hold the rocket at launch time. Make your best design.</p> 
            </div>
          </li>

          <!-- A new step -->
          <li>
            <div class="content">
              <h3>Tape them all to the bottle at an angle of about 120 degrees between them.</h3>
              <p>Remember, the bottle must be upside down and the flippers must not be taped at the bottle's base.</p>

              <!--
This block contains a photo and has a caption.
We have used a <div> to group and position the flickr photo
with a paragraph to create a photo with a caption.
-->
              <a href="http://www.flickr.com/photos/hucker/132609525/" title="2006-04-22 Yaeum Middle School Rocket Day 19 by Stephen Hucker, on Flickr"><img alt="2006-04-22 Yaeum Middle School Rocket Day 19" height="%" width="%" src="http://farm1.staticflickr.com/52/132609525_8e6452161d.jpg" ></a>
              <p class="caption">Maecenas sed diam eget risus varius blandit sit amet non magna.</p>
            </div>
          </li>

          <!-- A new step -->
          <li>
            <div class="content">
              <h3>Make a hole through the cork so that the bicycle pump can easily fit into it.</h3>
              <p>Fix the pump tube to it with plasticine.</p>


              <iframe width="560" height="315" src="https://www.youtube.com/embed/tntOCGkgt98" frameborder="0" allowfullscreen></iframe>
            </div>

          </li>

          <!-- A new step -->
          <li>
            <div class="content">
              <h3>Invert the bottle and cut three flippers of cardboard.</h3>
              <p>This is necessary to hold the rocket at launch time. Make your best design.</p> 
            </div>
          </li>

          <!-- A new step -->
          <li>
            <div class="content">
              <h3>Invert the bottle and cut three flippers of cardboard.</h3>
              <p>This is necessary to hold the rocket at launch time. Make your best design.</p> 
            </div>
          </li>



        </ol>

      </article>

    </div>

    <!--
TASK 5
=======================================================
Change the text and links in the footer of this page to acknowledge the sources of your images and youtube videos. If you made all your images and videos, then say so here. 
** NOTE: Broken links will be heavily penalized in grading.
-->         

    <footer>
      <p>The original how-to appeared in <a href="http://www.wikihow.com/Hide-Christmas/Birthday-Presents" title="How to Hide Christmas/Birthday Presents: 7 Steps - wikiHow">WikiHow</a>.</p>
      <p>Images are by <a href="http://www.flickr.com/photos/puuikibeach/4655440844/" title="Aquapod™ Water Rocket Launcher in Action by puuikibeach, on Flickr">puuikibeach from Flickr</a></p>
    </footer>

    <!--
TASK 6
=======================================================
Customise the visual style and appearance of your guide.
- The CSS below controls all the colors fonts and positioning on this HTML page.
- Be aware, you can break your page quite easily with this part of CSS.
-->         

    <style media="screen" type="text/css">

      /* STRUCTURAL ELEMENTS */

      html {
        position: relative;
        min-height: 100%;
        min-width: 100%;
        width: 100%;
        margin: 0px;
        padding: 0px;
        overflow-x: hidden; 
      }
      
      body {
        margin:0 0 130px;
        width:100%;
        font-weight:normal;
        font-family:Arial, sans-serif;         /* CHANGE THE FONT HERE */
        color:#555;         /* CHANGE THE FONT COLOR HERE */
      }  

      /* PAGE LAYOUT */

      header, footer {
        padding:5%;
        border:0 10%;
        background-color:#A1D0EB;          /* CHANGE THE HEADER AND FOOTER COLOR HERE */
        width:100%;
        margin:0px;        
      }

      footer {
        width: 100%;
        bottom: 0;
        left: 0;
        position: float;
        height:70px;
      }

      header img {
        padding-right: 10%;
        position: relative;
      }

      .wrapper {
        width:80%;
        max-width:650px;
        margin:0 auto;
        padding:30px;
      }
      
      
      /* BASIC STYLES FOR THE PAGE */
      
      a {
        color:#1593A1;         /* CHANGE THE LINK COLOR HERE */
        font-weight:bold;
      }

      /* Heading styles */
      h1 {
        margin:0;
        width:100%;
        font-weight:bold;
        font-family:Arial, sans-serif;          /* CHANGE THE HEADER FONT HERE */
      }

      h2, h3, h4 {
        margin:0 0 0.5em;
        padding-top: 10px;
        font-weight:normal;
      }

      /* Paragraph Text styles */
      p {
        margin:16px 0;
        line-height:1.4;
        font-weight:normal;
      }

      /* Styles for unordered lists <ul> */
      ul {
        font-family:"Courier New", Courier, monospace;
        box-shadow:0px 2px 10px #ddd;
        background-color: #D3E3E8;          /* CHANGE THE THINGS BACKGROUND COLOR HERE */
        border: 1px solid #555;           /* CHANGE THE THINGS BORDER HERE */
        padding:0;
        margin:2em 0 0;
        position:relative;
        z-index:200;

      }

      /* Styles for unordered list items <li> */
      ul li {
        list-style-type: none;
        border-top: 1px dotted #555; 
        font-size:14px;
        color:#000;
        height: auto;
        padding: 7px 10px 5px 25px;
        list-style-type: square;
        list-style-position: inside;
        color:#333;
      }

      .content {
        background: #fff;          /* CHANGE THE INSTRUCTION BACKGROUND COLOR HERE */
      }

      .step-by-step li:before {
        background: #D3E3E8;          /* CHANGE THE INSTRUCTION NUMBER BACKGROUND COLOR HERE */
        border-top-left-radius: 50px;          /* CHANGE THE INSTRUCTION SHAPE HERE */
        border-bottom-left-radius: 50px;
      }


      /* Object styles */
      .step-by-step img,
      .step-by-step iframe {
        width:100%;
        margin-bottom:10px;
      }

      img.logo {
        width:auto;
        height:100%;
      }


      /* ADVANCED STYLES*/

      /* Styles for the guide introduction wrapper */
      .introduction {
        padding:0px;
        position:relative;
        margin-bottom:40px;
        overflow:hidden;
        background:#fff;
      }

      hr {
        border: 0; 
        height: 0; 
        border-top: 1px solid #D3E3E8; 
      }


      ul li:first-child {
        list-style-type: none;
        border-top: none;
      }


      /* Hover state styles for list items inside unordered list <li> */
      ul li:hover {
        background-color: #eedc9c;
      }


      /* Step by step instructions */
      .step-by-step {  
        padding:0;
        position: relative;
        z-index:0;
        margin-left:40px;
      }
      .step-by-step li {
        position: relative;
        text-align: left;
        list-style-type: decimal;
        margin-bottom:20px;
      }
      .step-by-step li ol {
        margin-top:20px;
      }
      .step-by-step li li {
        list-style-type: lower-alpha;
      }
      .step-by-step .media-content {
        position:relative;
      }
      .step-by-step .media-content img {
        display:block;
        margin:0;
        width:100%;
        height:auto;
      }
      .step-by-step .media-content .caption {
        position:absolute;
        padding:0.5em 1em;
      }
      .step-by-step .media-content iframe {
        display:block;
        margin:0;
      }

      /* Content for each step */
      .content {
        padding: 20px;
        margin-bottom:10px;
        border-radius: 0px 5px 5px 5px;
        box-shadow: 0px 0px 7px 0px rgba(0,0,0,.25);           
      }       

      /* Advanced CSS for item number styling */
      .step-by-step li:before {
        content: "";
        width: 40px;
        height:80px;
        position: absolute;
        top:0;
        left:-40px;
        z-index:-1;
        background: #D3E3E8; 
        border-top-left-radius: 50px;
        border-bottom-left-radius: 50px;
      }

      /* Styles for sub-list item numbering */
      .step-by-step li li:before {
        background: #333; 
      }


      /* Footer credits */
      footer {
        margin-top:50px;
      }
      footer p {
        font-size:12px;
        color:#000;
      }

      a img {
        border:none;
      }
    </style>

  </body>
</html>
