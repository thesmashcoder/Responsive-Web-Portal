<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta/css/bootstrap.min.css" integrity="sha384-/Y6pD6FV/Vv2HJnA6t+vslU6fwYXjCFtcEpHbNJ0lyAFsXTsjBbfaDjzALeQsN6M" crossorigin="anonymous">
<style>
    .section-title {
/*max-width: 800px;*/
margin: 80px auto;
padding: 15px;
text-align: center; }
.section-title h1 {
font-size: 24px;
text-transform: uppercase;
color: #0077bc; }
.section-title .divider {
position: relative;
border-bottom: 1px solid #f0f0f0;
margin-bottom: 30px;
margin-top: 30px; }
.section-title .divider:before {
position: absolute;
content: '';
width: 30px;
height: 30px;
border: 1px solid #f0f0f0;
left: 50%;
margin-left: -15px;
top: 50%;
background: #fff;
margin-top: -15px;
-webkit-transform: rotate(45deg);
-moz-transform: rotate(45deg);
-ms-transform: rotate(45deg);
transform: rotate(45deg); }
.section-title .divider:after {
position: absolute;
content: '';
width: 20px;
height: 20px;
border: 1px solid #0077bc;
left: 50%;
margin-left: -10px;
top: 50%;
background: #0077bc;
margin-top: -10px;
-webkit-transform: rotate(45deg);
-moz-transform: rotate(45deg);
-ms-transform: rotate(45deg);
transform: rotate(45deg); }
footer{
  color: white;
}
footer a{
  color: #bfffff;
}
footer a:hover{
  color: white;
}

.footer-middle{
  padding-top: 2em;
  color: white;
}
/**Sub Navigation**/
.subnavigation-container{
  background: #3d6277;
}
.subnavigation .nav-link{
  color: white;
  font-weight: bold;
}
.subnavigation-container{
  text-align: center;
}
.subnavigation-container .navbar{
  display: inline-block;
  margin-bottom: -6px; /* Inline-block margin offffset HACK -Gilron */
}
.col-subnav a{
  padding: 1rem 1rem;
  color: white;
  font-weight: bold;
}
.col-subnav .active{
  border-top:5px solid orange;
 background: white;
  color: black;
}
    a {
    color: #0077bc;
    text-decoration: none;
    background-color: transparent;
    -webkit-text-decoration-skip: objects;
    font-weight:bold;
}
    .card-header {
    padding: .75rem 1.25rem;
    margin-bottom: 0px;
    background-color: #ffffff;
    border-bottom: 1px solid rgba(0, 0, 0, .125);
}

    /*.card-outline-primary{
        color:black;
    }*/

            .bg-deepblue {background-color: #003057;}

    /*.bgimage {
  width:100%;
  height:500px;
  background: url('https://images.unsplash.com/photo-1438109491414-7198515b166b?q=80&fm=jpg&s=cbdabf7a79c087a0b060670a6d79726c');
  background-repeat: no-repeat;
  background-position: center;
  background-size:cover;
  background-attachment: fixed;
}*/

        .bgimage {
  width:100%;
  height:550px;
  background: url('spectrum52.jpg');
  background-repeat: no-repeat;
  background-position:  bottom;
  background-size:cover;
  background-attachment:  fixed;
}

.bgimage h5 {
  color:white;
  text-shadow:2px 2px #333;
}</style></head>
<body>
    <section class="bgimage">
        <div class="container-fluid">
            <!--<div class="row">
                <div class="col-lg-12 col-md-12 col-sm-12 col-xs-12">
                    <h5>Hello, world! Full width Hero-unit header</h5>
                    <p>This is a template for a simple marketing or informational website. It includes a large callout called the hero unit and three supporting pieces of content. Use it as a starting point to create something more unique.</p>
                    <p><a href="#" class="btn btn-primary btn-large">Our Mission</a></p>
                    <p><a href="#" class="btn btn-primary btn-large">Who We Serve</a></p>
                </div>
            </div>-->
            <nav class="navbar navbar-expand-lg navbar-dark bg-deepblue">
                <a class="navbar-brand" href="#"><img src="charter_white_logo.png"></a>
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>

                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav mr-auto">
                        <!--<li class="nav-item active">
                            <a class="nav-link" href="#"style="color:#FFFFFF">Home <span class="sr-only">(current)</span></a>
                        </li>-->
                        <li class="nav-item">
                            <a class="nav-link" href="https://learningsvcs.wufoo.com/forms/z1b7nau10k555mz/"target="_blank"style="color:#0077BC"><img class="float-left" src="requestTraining2.png" alt="Request New Training" height="30"style="padding-right:5px">Request New Training</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="https://learningsvcs.wufoo.com/forms/m1k8ubfj0vltv9u/"target="_blank"style="color:#0077BC"><img class="float-left" src="updateContent2.png" alt="Update Existing Content" height="30"style="padding-right:5px">Update Existing Content</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="https://learningsvcs.wufoo.com/forms/q1c945hx102e4wr/"target="_blank"style="color:#0077BC"><img class="float-left" src="askQuestion2.png" alt="Ask a Question" height="30"style="padding-right:5px">Ask A Question</a>
                        </li>
                    </ul>
                    <div class="form-inline my-2 my-lg-0">
                        <h2 class="my-2 my-sm-0" style="color:#FFFFFF">Learning Services</h2>
                    </div>
                </div>
            </nav>
        </div>

    </section>
    <div class="container-fluid">
        <div class="row" style="padding-top:5px">

            <div class="col-sm-4 col-md-4 col-lg-4">
                <div class="card mx-auto d-block text-center" style="width: inherit;border:none;">
                    <a href="https://learningsvcs.wufoo.com/forms/z1b7nau10k555mz/" target="_blank">
                        <img class="card-img-top img-fluid" src="requestTraining2.png" alt="Request New Training" style="width: 10rem">
                    </a>
                    <div class="card-block">
                        <h5 class="card-title text-center">
                            <a href="https://learningsvcs.wufoo.com/forms/z1b7nau10k555mz/" target="_blank">Request New Training</a>
                        </h5>
                        <p class="card-text">Use this form to engage the Learning Services Team on a new learning design, analytics, technology, or program project</p>
                        <!--<a href="#" class="btn btn-primary">Go somewhere</a>-->
                    </div>
                </div>
            </div>
            <div class="col-sm-4 col-md-4 col-lg-4">
                <div class="card mx-auto d-block text-center" style="width: inherit;border:none;">
                    <a href="https://learningsvcs.wufoo.com/forms/m1k8ubfj0vltv9u/" target="_blank">
                        <img class="card-img-top img-fluid" src="updateContent2.png" alt="Update Existing Content" style="width: 10rem">
                    </a>
                    <div class="card-block">
                        <h5 class="card-title text-center">
                            <a href="https://learningsvcs.wufoo.com/forms/m1k8ubfj0vltv9u/" target="_blank">Update Existing Content</a>
                        </h5>
                        <p class="card-text">Use this form to request an update to existing learning materials, analytics, or other Learning Services content</p>
                        <!--<a href="#" class="btn btn-primary">Go somewhere</a>-->
                    </div>
                </div>

            </div>
            <div class="col-sm-4 col-md-4 col-lg-4">
                <div class="card mx-auto d-block text-center" style="width: inherit;border:none;">
                    <a href="https://learningsvcs.wufoo.com/forms/q1c945hx102e4wr/" target="_blank">
                        <img class="card-img-top img-fluid" src="askQuestion2.png" alt="Ask a Question" style="width: 10rem">
                    </a>
                    <div class="card-block">
                        <h4 class="card-title text-center">
                            <a href="https://learningsvcs.wufoo.com/forms/q1c945hx102e4wr/" target="_blank">Ask a Question</a>
                        </h4>
                        <p class="card-text">Send a question to Learning Services   </p>
                        <!--<a href="#" class="btn btn-primary">Go somewhere</a>-->
                    </div>
                </div>

            </div>
        </div>
        <div class="row">
            <div class="col-sm-12 col-md-12 col-lg-12">
                <!-- Section Title -->
                <div class="section-title">
                    <h1>Our Mission</h1>
                    <div class="divider"></div>
</div>
            </div>
            <div class="col-sm-3 col-md-3 col-lg-3" style="border-right: solid #f0f0f0">
                <ul class="list-group">
                    <li class="list-group-item" style="border: none">Transparently partner with our employees to move smoothly through administrative processes so they can focus on their craft</li>
                </ul>
            </div>
            <div class="col-sm-3 col-md-3 col-lg-3" style="border-right: solid #f0f0f0">
                <ul class="list-group">
                    <li class="list-group-item" style="border: none">Challenge “the way it’s always been done” leading to progressive, results driven solutions</li>
                </ul>
            </div>
            <div class="col-sm-3 col-md-3 col-lg-3" style="border-right: solid #f0f0f0">
                <ul class="list-group">
                    <li class="list-group-item" style="border: none">Drive collaboration and knowledge sharing for the learning teams across the company</li>
                </ul>
            </div>
            <div class="col-sm-3 col-md-3 col-lg-3">
                <ul class="list-group">
                    <li class="list-group-item" style="border: none">Deliver on operational learning needs for our HR and Corporate audiences</li>
                </ul>
            </div>

        </div>
        <div class="row">
            <div class="col-sm-12 col-md-12 col-lg-12"style="padding-bottom:0px">
                <!-- Section Title -->
                <div class="section-title">
                    <h1>Who We Serve</h1>
                    <div class="divider"></div>
                </div>
            </div>
            <div class="col-sm-3 col-md-3 col-lg-3" style="border-right: solid #f0f0f0">
                <ul class="list-group">
                    <li class="list-group-item" style="border: none">Human Resources</li>
                </ul>
            </div>
            <div class="col-sm-3 col-md-3 col-lg-3" style="border-right: solid #f0f0f0">
                <ul class="list-group">
                    <li class="list-group-item" style="border: none">Information Technology</li>
                </ul>
            </div>
            <div class="col-sm-3 col-md-3 col-lg-3" style="border-right: solid #f0f0f0">
                <ul class="list-group">
                    <li class="list-group-item" style="border: none">Legal</li>
                </ul>
            </div>
            <div class="col-sm-3 col-md-3 col-lg-3">
                <ul class="list-group">
                    <li class="list-group-item" style="border: none">Security Product</li>
                </ul>
            </div>
            <div class="col-sm-3 col-md-3 col-lg-3" style="border-right: solid #f0f0f0">
                <ul class="list-group">
                    <li class="list-group-item" style="border: none">Programming</li>
                </ul>
            </div>
            <div class="col-sm-3 col-md-3 col-lg-3" style="border-right: solid #f0f0f0">
                <ul class="list-group">
                    <li class="list-group-item" style="border: none">Strategic Policy Development Communications</li>
                </ul>
            </div>
            <div class="col-sm-3 col-md-3 col-lg-3" style="border-right: solid #f0f0f0">
                <ul class="list-group">
                    <li class="list-group-item" style="border: none">News & Sports Networks</li>
                </ul>
            </div>
            <div class="col-sm-3 col-md-3 col-lg-3">
                <ul class="list-group">
                    <li class="list-group-item" style="border: none">Government Affairs</li>
                </ul>
            </div>
            <div class="col-sm-3 col-md-3 col-lg-3">
                <ul class="list-group">
                    <li class="list-group-item" style="border: none">Business Planning</li>
                </ul>
            </div>

        </div>



        </div>
    <footer class="mainfooter" role="contentinfo"style="padding-top:25px">
        <div class="footer-top p-y-2">
            <div class="container-fluid">
                <div class="row">

                </div>
            </div>
        </div>
        <div class="footer-middle bg-deepblue">
            <div class="container">
                <div class="row">
                    <div class="col-md-3 col-sm-6 float-left">
                        <!--Column1-->
                        <div class="footer-pad ">
                            <h4 style="color:#003057">2017 - For Internal use Only | Learning Services</h4>
                            <address>
                                        <br>
                                        <br>
                                        <br>
                            </address>
                        </div>
                    </div>
                    <div class="col-md-12 col-sm-12">
                        <!--Column1-->
                        <div class="footer-pad">
                        </div>
                    </div>
                    <div class="col-md-3 col-sm-6">
                        <!--Column1-->
                        <div class="footer-pad">
                        </div>
                    </div>
                    <div class="col-md-3 col-sm-6">
                        <!--Column1-->
                        <div class="footer-pad">
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </footer>
    
     <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.11.0/umd/popper.min.js" integrity="sha384-b/U6ypiBEHpOf/4+1nzFpr53nxSS+GLCkfwBdFNTxtclqqenISfwAzpKaMNFNmj4" crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta/js/bootstrap.min.js" integrity="sha384-h0AbiXch4ZDo7tp9hKZ4TsHbi047NrKGLO3SEJAg45jXxnGIfYzk4Si90RDIqNm1" crossorigin="anonymous"></script>

    <script>
        $(document).ready(function () {

            $('.nav-tabs > li').click(function () {
                $(this).find('a').tab('show');
            });
            $('.nav-tabs > li').click(function () {
                $(this).find('a').tab('hide');
            });

        });

    </script>

</body>
</html>