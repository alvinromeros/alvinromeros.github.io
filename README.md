# alvinromeros.github.io
<html>
    <head>
        <title>PT.YOLOTakmau</title>
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css"></a>
        <script src="Jquery.js"></script>
        <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
        
        <script> $(document).ready(function() {
            $(".navbar a, footer a[href='#myPage']").on('click', function(event) {
                if(this.hash !== "") {

                    event.preventDefault();

                    var hash = this.hash;
                    console.log(hash);

                    $('html, body').animate({
                        scrollTop:$(hash).offset().top
                    }, 900);
                }
            });
        }) </script>
        

        <style>
            .jumbotron{ 
                background-color: aqua;
                color: red;
                padding: 100px 25px;
            }
            .bg-grey {
                background-color: aqua;
            }
            .container-fluid {
                padding: 60px 50px;
            }
            .logo {
                font-size: 150px;
            }
            .logo-small {
                background-color: aqua;
                font-size: 50px;
            }
            .carousel-control.right, .carousel-control.left {
                background-image: none;
                color: aqua
            }
            .carousel-indicators li {
                border-color: aqua;
            }
            .carousel-indicators li.active{
                background-color: aqua;
            }
            .item h4 {
                font-size: 19px;
                line-height: 1.37em;
                font-weight: 400px;
                font-style: italic;
                margin: 70px 0;
            }
            .item span {
                font-style: normal;
            }
            .panel { 
                border: 1px solid aqua;
                border-radius: 0;
                transition: box-shadow 0,5s;
            }
            .panel:hover {
                box-shadow: 5px 0px 40px red;
            }
            .panel-footer .btn:hover {
                border: 1px solid aqua;
                background-color: red !important;
                color: aqua;
            }
            .panel-heading {
                color: red;
                background-color: aqua;
                padding: 25px;
                border-bottom: 1px solid transparent;
                border-top-left-radius: 0px;
                border-top-right-radius: 0px;
                border-bottom-left-radius: 0px;
                border-bottom-right-radius: 0px;
            }
            .panel-footer {
                background-color: aqua;
            }
            .panel-footer h3 {
                font-size: 32px;
            }
            .panel-footer h4 {
                color: aqua;
                font-size: 14px;
            }
            .panel-footer .btn {
                margin: 15px 0;
                background-color: aqua
            }

            .navbar li a, .navbar .navbar-brand {
                color: aqua !important;
            }
            .navbar-nav li a:hover, .navbar-nav li.active a {
                color:red !important;
                background-color: aqua !important;
            }
            .navbar-default .navbar-toggle {
                border: 2px;
                border-color: black;
                color: black;
            }
        </style>
    </head>
    <body id="myPage">
        <div class="jumbotron text-center">
        <h1>PT. YOLO</h1>
        <P>Kami adalah perusahaan yang fokus pada pengembangan sistem informasi keuangan</P>
        <form class="form-inline">
            <div class="input-group">
                <input type="email" class="form-control" size="50" placeholder="Email Address" required>
                <div class="input group-btn">
                    <button type="button" class="btn btn-danger">Subscribe</button>
                </div>
            </div>
        </form>
    </div>
    <!-- /////////////////////////////////////////////////////////////////////////////// -->
    <div id="about" class="container-fluid">
            <div class="row">

                    <div class="col-sm-8">
        <h2>About Company Page</h2>
        <h4>Lorem ipsum..</h4>
        <p>Lorem ipsum..</p>
        <button class="btn btn-default btn-lg">Get in Touch</button>
        </div>
        
        <div class="col-sm-4">
        <span class="glyphicon glyphicon-signal logo"></span>
    </div>
        </div>
    </div>
    <!-- /////////////////////////////////////////////////////////////////////// -->
    <div class="container-fluid bg-grey">
        <div class="row">
            <div class="col-sm-8">
        <h2>Our Values</h2>
        <h4><strong>MISSION:</strong> Our mission Lorem ipsum..</h4>
        <p><strong>VISION:</strong> Our vision ipsum..</p>
        <button class="btn btn-default btn-lg">Get in Touch</button>
    </div>
        <div class="col-sm-4">
            <span class="glyphicon glyphicon-globe logo"></span>
        </div>
        </div>
    </div>
<!-- ////////////////////////////////// ///////////////////////////////////////////////// -->
<div id="services"class="container-fluid text-center">
    <h2>SERVICE</h2>
    <h4>What we offer</h4>
<br>

<div class="row">
    <div class="col-lg-4">
            <button class="btn btn-default btn-lg glyphicon glyphicon-off logo-small"></button>
            <h4>POWER</h4>
            <p>Lorem ipsum dolor sit amet..</p>
        </div>
<!-- /////////////////////////////////////////////////////////////////////////////////////////////// -->
        <div class="col-lg-4">
                <button class="btn btn-default btn-lg glyphicon glyphicon-heart logo-small"></button>
                <h4>LOVE</h4>
                <p>Lorem ipsum dolor sit amet..</p>
         </div>
<!-- ////////////////////////////////////////////////////////////////////////////////////////////// -->
            <div class="col-lg-4">
            <button class="btn btn-default btn-lg glyphicon glyphicon-lock  logo-small"></button>
             <h4>JOB DONE</h4>
            <p>Lorem ipsum dolor sit amet..</p>
        </div>
</div>
<br>
<br>
<!-- ///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////// -->
<div class="row">
        <div class="col-lg-4">
                <button class="btn btn-default btn-lg glyphicon glyphicon-leaf logo-small"></button>
                <h4>GREEN</h4>
                <p>Lorem ipsum dolor sit amet..</p>
            </div>
<!-- /////////////////////////////////////////////////////////////////////////////////////////////////////////////////////// -->
        <div class="col-lg-4">
                <button class="btn btn-default btn-lg glyphicon glyphicon-certificate logo-small"></button>
                <h4>CERTIFIED</h4>
                <p>Lorem ipsum dolor sit amet..</p>
            </div>
<!-- /////////////////////////////////////////////////////////////////////////////////////////////-->
        <div class="col-lg-4">
                <button class="btn btn-default btn-lg glyphicon glyphicon-wrench logo-small"></button>
                <h4>HARD WORK</h4>
                <p>Lorem ipsum dolor sit amet..</p>
            </div>
</div>
<!-- ///////////////////////////////////////////////////////////////////////////////////////////////////////////// -->
<div  id="portofolio"class="container-fluid text-center bg-grey">
        <h2>Portofolio</h2>
        <h4>Whhat we have created</h4>
    <div class="row text-center">
      <div class="col-lg-4">
            <div class="thumbnail">
               <a href="lights.jpg" ></a>
              <img src="lights.jpg" alt="lights"> 
              <p><strong>Lights</strong></p>   
              <p>Yes, we built paris</p>
                </div>
              </a>
            </div>

      <div class="col-lg-4">
            <div class="thumbnail">
              <a href="nature.jpg"></a>
                      <img src="nature.jpg" alt="nature"> 
                      <p><strong>Nature</strong></p>   
                      <p>Yes, we built nature</p>
                </div>
              </a>
            </div>
     
            <div class="col-lg-4">
                    <div class="thumbnail">
                      <a href="fjords.jpg"></a>
                        <img src="fjords.jpg" alt="Fjords"  class="img-thumbnail" alt="fjords" >
                        <p><strong>fjords</strong></p>   
                              <p>Yes, we built fjords</p>
                      </div>
                      </a>
                    </div>
            
     
      </div>
    </div>
    <!-- //////////////////////////////////////////////////////////////////////////////////////////////////////////// -->

<div class="container-fluid text-center">
    <h2>What our customer say</h2>
    <div id="myCarousel" class="carousel slide text-center" data-ride="carousel">

            <ol class="carousel-indicators">
                    <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
                    <li data-target="#myCarousel" data-slide-to="1"></li>
                    <li data-target="#myCarousel" data-slide-to="2"></li>
            </ol>

            <div class="carousel-inner" role="list-box">
                    <div class="item active">
                            <h4>"This company is the best. I am so happy with the result!"<br>
                            <span style="font-style:normal;">Michael Roe, Vice President, Comment box</span></h4>
                        </div>

                     <div class="item">
                                <h4>"One word... WOW!!"<br><span style="font-style:normal;">Jhon Doe, Salesman, Rep Inc</span></h4>
                            </div>
                                
                            <div class="item">
                                    <h4>"Could I... BE any more happy with this company?"<br>
                                <span style="font-style: normal;">Chandler Bing, Actor, Friendsalot</span></h4>
                            </div>

                        </div>
                            
       
            

            <a class="left carousel-control" href="#myCarousel" role="button" data-slide="prev">
                <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
                <span class="sr-only">Previous</span>
            </a>

            <a class="right carousel-control" href="#myCarousel" role="button" data-slide="next">
                    <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
                    <span class="sr-only">Next</span>
                </a>

            



</div>
</div>
<!-- ////////////////////////////////////////////////////////////////////////////////////////////////////// -->
<div id="pricing" class="container-fluid">
    <div class="text-center">
        <h2>Pricing</h2>
        <h4>Choose a payment plan that works for you</h4>
    </div>

    <div class="row">

        <div class="col-lg-4">
            <div class="panel panel-default text-center">
                <div class="panel-heading">
                    <h1>Basic</h1>
                </div>
                <div class="panel-body">
                    <p><strong>20</strong>Lorem</p>
                    <p><strong>15</strong>Ipsum</p>
                    <p><strong>5</strong>Dolor</p>
                    <p><strong>2</strong>Sit</p>
                    <p><strong>Endless</strong>Amet</p>
                </div>
                <div class="panel-footer">
                    <h3>$19</h3>
                    <h4>per month</h4>
                    <button class="btn btn-lg">Sign Up</button>
                </div>
            </div>
        </div>
        <!-- /////////////////////////////////////////////////////////////////////////////// -->
        <div class="col-lg-4">
                <div class="panel panel-default text-center">
                    <div class="panel-heading">
                        <h1>Basic</h1>
                    </div>
                    <div class="panel-body">
                        <p><strong>50</strong>Lorem</p>
                        <p><strong>25</strong>Ipsum</p>
                        <p><strong>10</strong>Dolor</p>
                        <p><strong>5</strong>Sit</p>
                        <p><strong>Endless</strong>Amet</p>
                    </div>
                    <div class="panel-footer">
                        <h3>$29</h3>
                        <h4>per month</h4>
                        <button class="btn btn-lg">Sign Up</button>
                    </div>
                </div>
            </div>
    <!-- ////////////////////////////////////////////////////////////////////////////////////////////// -->
    <div class="col-lg-4">
            <div class="panel panel-default text-center">
                <div class="panel-heading">
                    <h1>Basic</h1>
                </div>
                <div class="panel-body">
                    <p><strong>100</strong>Lorem</p>
                    <p><strong>50</strong>Ipsum</p>
                    <p><strong>25</strong>Dolor</p>
                    <p><strong>10</strong>Sit</p>
                    <p><strong>Endless</strong>Amet</p>
                </div>
                <div class="panel-footer">
                    <h3>$49</h3>
                    <h4>per month</h4>
                    <button class="btn btn-lg">Sign Up</button>
                </div>
            </div>
        </div>


    </div>
</div>  
<!-- //////////////////////////////////////////////////////////////////////   -->
<div id="contact" class="container-fluid bg-grey">
    <h2 class="text-center">CONTACT</h2>

    <div class="row">
        <div class="col-lg-5">
        <p>Contact us and we'll get back to you within 24 hours.<p>
            <p><span class="glyphicon glyphicon-map-marker"></span>Chicago</p>
            <p><span class="glyphicon glyphicon-phone"></span>+00 1515151515</p>
            <p><span class="glyphicon glyphicon-envelope"></span>myemail@something.com</p>

        </div>

        <div class="col-lg-7">
            <div class="row">
                <div class="col-lg-6 form-group">
                    <input class="form-control" id="name" name="name" placeholder="Name" type="text" required>
                </div>

                <div class="col-lg-6 form-group">
                    <input class="form-control"  id="email" name="email" placeholder="Email" type="email" required>
            </div>
            </div>
            <textarea class="form-control" id="comments" name="comments" placeholder="Comments" rows="5"></textarea><br>
            <div class="row">
                <div class="col-lg-12 form-group">
                    <button class="btn btn-default pull-right" type="submit">Send</button>
                </div>
            </div>
        </div>
    </div>
</div>
<!-- ////////////////////////////////////////////////////////////////////////////////////////////////////////////////// -->
<nav class="navbar navbar-default navbar-fixed-top">
    <div class="container">
        <div class="navbar-header">
            <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
                <span class="icon-bar"></span>
                <span class="icon-bar"></span>
                <span class="icon-bar"></span>
            </button>
            <a class="navbar-brand" href="#"><img src="yolo.jpg" width="30px" height="30" ></a>
        </div>
        <div class="collapse navbar-collapse" id="myNavbar">
            <ul class="nav navbar-nav navbar-right">
                <li><a href="#about">ABOUT</a></li>
                <li><a href="#services">SERVICE</a></li>
                <li><a href="#portofolio">PORTOFOLIO</a></li>
                <li><a href="#pricing">PRICING</a></li>
                <li><a href="#contact">CONTACT</a></li>
            </ul>
        </div>
    </div>
</nav>
</body>
<footer  data-spy="scroll"  data-target=".navbar"class="container-fluid text-center">
    <a href="#myPage" title="To Top">
        <span class="glyphicon glyphicon-chevron-up"></span>
    </a>
    <p>&copy;2018 PT.YOLO</p>
</footer>
</html>
