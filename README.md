<!DOCTYPE html>
<html lang="en">

<head>
  <title>Corona Help Drsk</title>
  <style type="text/css">
    .html {
      scroll-behavior: smooth;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Mulish', sans-serif;
    }

    .nav_style {
      background-color: #a29bfe !important;
    }

    .nav_style a {
      color: white;
    }

    .main_header {
      margin-top: 100;
      height: 350px;
      width: 100%;
    }

    .rightside h1 {
      font-size: 3rem;
    }

    .corona_rot img {
      animation: gocorona 25s linear infinite;
    }

    @keyframes gocorona {
      0% {
        transform: rotate(0);
      }

      100% {
        transform: rotate(360deg);
      }
    }

    .leftside img {
      animation: heartbeat 5s linear infinite;
    }

    @keyframes heartbeat {
      0% {
        transform: scale(.75);
      }

      20% {
        transform: scale(1);
      }

      40% {
        transform: scale(.75);
      }

      60% {
        transform: scale(1);
      }

      80% {
        transform: scale(.75);
      }

      100% {
        transform: scale(.75);
      }
    }

    .corona_update {
      margin: 0 0 30px 0;
    }

    .corona_update h3 {
      color: #ff7675;
    }

    .corona_update h1 {
      font-size: 2rem;
      text-align: center;
    }

    .sub_section {
      background-color: #fbfafd;

    }

    .footer_style {
      background: color #a29bfe !important;
    }

    .footer_style p {
      margin-bottom: 0 !important;
    }

    #myBTN {
      display: none;
      position: fixed;
      bottom: 30px;
      right: 400px;
      z-index: 99;
      border: none;
      outline: none;
      background-color: #00A8FF;
      color: white;
      cursor: pointer;
      padding: 10;
      border-radius: 10px;
    }

    #myBtn:hover {
      background: #00A8FF;
    }
  </style>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/fontawesome.min.css"
    integrity="sha512-OdEXQYCOldjqUEsuMKsZRj93Ht23QRlhIb8E/X0sbwZhme8eUw6g8q7AdxGJKakcBbv7+/PX0Gc2btf7Ru8cZA=="
    crossorigin="anonymous" referrerpolicy="no-referrer" />

  <<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"
    integrity="sha512-iBBXm8fW90+nuLcSKlbmrPcLa0OT92xO1BIsZ+ywDWZCvqsWgccV3gFoRBv0z+8dLJgyAHIhR35VZc2oM/gI1w=="
    crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet"
  href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">

  <script src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/js/fontawesome.min.js"
    integrity="sha512-KCwrxBJebca0PPOaHELfqGtqkUlFUCuqCnmtydvBSTnJrBirJ55hRG5xcP4R9Rdx9Fz9IF3Yw6Rx40uhuAHR8Q=="
    crossorigin="anonymous" referrerpolicy="no-referrer"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</head>

<body>
  <nav class="navbar navbar-expand-lg nav_style p-3 ">
    <a class="navbar-brand pl-5" href="#">Corona Help Desk</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
      aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav ml-auto pr-5 text-capitalize">
        <li class="nav-item active">
          <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#aboutid">about</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#sympid">symptoms</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#preventid">prevention</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#contactid">contact</a>
        </li>
    </div>
  </nav>
  <div class="main_header">
    <div class="row w-100 h-100">
      <div class="col-lg-5 col-md-5 col-12 order-lg-1 order-2 pl-5">
        <div class="leftside">
          <img src="logo.jpg" width="300" hight="300 pl-5 ">
        </div>
      </div>
      <div class="col-lg-7 col-md-7 col-12 order-lg-2 order-1">
        <div class="rightside w-100 h-100  d-flex justify-content-center align-items-center">
          <h1>Let,s Stay Safe & Fight Together <br>Against Cor<span class="corona_rot"><img src="gocorona.png"
                width="100" hight="100"></span>na Virus</h1>
        </div>
      </div>
    </div>
  </div>
  <!********************* corona latest updates *********************************************--->
    <section class="corona_update">
      <div class="mb-4">
        <h3 class="text-uppercase text-center pb-5"> Covid-19 updates</h3>
      </div>
      <div class="d-flex justify-content-around align-items-center">
        <div>
          <h1 class="count">1,869,886</h1>
          <p>Passengers screened at airport</p>
        </div>
        <div>
          <h1 class="count">513</h1>
          <p>corona new cases</p>
        </div>
        <div>
          <h1 class="count">90</h1>
          <p>active covid-19 cases</p>
        </div>
        <div>
          <h1 class="count">3</h1>
          <p>death rate</p>
        </div>
      </div>
    </section>
    <!******************************* about section *********************************---->
      <div class="container-field sub_section pt-5 pb-5 " id="aboutid">
        <div class="section_header text-center mb-5 mt-4">
          <h1>About Covid-19 </h1>
        </div>
        <div class="row">
          <div class="col-lg-5 col-md-6 col-12">
            <iframe width=" 560" height="315" src="https://www.youtube.com/embed/5DGwOJXSxqg"
              title="YouTube video player" frameborder="0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
              allowfullscreen></iframe>
          </div>
          <div class="col-lg-6 col-md-6 col-12">
            <h2> What is COVID-19(Corona-Virus)</h2>
            <p> COVID-19 is the infectious disease caused by the most
              recebtly discovered coronavirus.this new virus and disease
              were unkown before the outbreak began in wuhan, china , in
              December 2019.</p>
            <p>Coronaviruses are a large faily of viruses which may causes
              illness in animals or human .in human ,several Coronaviruses
              are known to cause respiratory infections ranging from the
              common cold to more severe diesease such as Middle East<br>
            <p> The virus that causes COVID-19 is mainly transmitted through
              droplets generated when an infected person
              coughs, sneezes, or exhales. These droplets are too heavy to
              hang in the air, and quickly fall on floors
              or surfaces.</p>
          </div>
        </div>
      </div>
      <!*************************coronavirus symptoms**************--->
        <div class="container-fluid pt-5 pb-5" id="sympid">
          <div class="section_header text-center mb-5 mt-4">
            <h1>Coronavirus symptoms</h1>
          </div>
          <div class="container">
            <div class="row">
              <div class="col-lg-4 col-md-4 col-12 mt-5">
                <figure class="text-center">
                  <img src="cough.png" class="img-fluid" width="120" height="120">
                  <figcaption> cough</figcaption>
                </figure>
              </div>
              <div class="col-lg-4 col-md-4 col-12 mt-5">
                <figure class="text-center">
                  <img src="nose.png" class="img-fluid" width="90" height="90">
                  <figcaption>runny nose</figcaption>
                </figure>
              </div>
              <div class="col-lg-4 col-md-4 col-12 mt-5">
                <figure class="text-center">
                  <img src="fever.png" class="img-fluid" width="120" height="120">
                  <figcaption>fever</figcaption>
                </figure>
              </div>
              <div class="col-lg-4 col-md-4 col-12 mt-5">
                <figure class="text-center">
                  <img src="cold.png" class="img-fluid" width="100" height="100">
                  <figcaption> cold</figcaption>
                </figure>
              </div>
              <div class="col-lg-4 col-md-4 col-12 mt-5">
                <figure class="text-center">
                  <img src="tired.png" class="img-fluid" width="160" height="160">
                  <figcaption> tiredness</figcaption>
                </figure>
              </div>
              <div class="col-lg-4 col-md-4 col-12 mt-5">
                <figure class="text-center">
                  <img src="breath.png" class="img-fluid" width="120" height="120">
                  <figcaption> difficulty breathing(severe cases)</figcaption>
                </figure>
              </div>
            </div>
          </div>
        </div>
        </div>
        </div>
        <!*************************prevention against oronavirus**************--->
          <div class="container-fluid sub_section pt-5 pb-5" id="preventid">
            <div class="section_header text-center mb-5 mt-4">
              <h1> 6-steps prevention against oronavirus</h1>
            </div>
            <div class="container">
              <div class="row">
                <div class="col-lg-4 col-md-4 col-12 mt-5">
                  <div class="row">
                    <div class="col-lg-4 col-md-4 col-12">
                      <figure class="text-center">
                        <img src="handwash.png" class="img-fluid" width="120" height="120">
                        <figcaption> handwash</figcaption>
                      </figure>
                    </div>
                    <div class="col-lg-8 col-md-8 col-12">
                      <p>Wash your hands
                        regularly fro 20 seconds.
                        with soap and water or
                        alcohol-based hand rub
                      </p>
                    </div>
                  </div>
                </div>
                <div class="col-lg-4 col-md-4 col-12 mt-5">
                  <div class="row">
                    <div class="col-lg-4 col-md-4 col-12">
                      <figure class="text-center">
                        <img src="mask.jpg" class="img-fluid" width="120" height="120">
                        <figcaption>wear mask</figcaption>
                      </figure>
                    </div>
                    <div class="col-lg-8 col-md-8 col-12">
                      <p>Cover your nose and mouth with a disposale
                        tissue or flexed elbow when you cough or sneeze</p>
                    </div>
                  </div>
                </div>
                <div class="col-lg-4 col-md-4 col-12 mt-5">
                  <div class="row">
                    <div class="col-lg-4 col-md-4 col-12">
                      <figure class="text-center">
                        <img src="social.png" class="img-fluid" width="120" height="120">
                        <figcaption>Social Distance</figcaption>
                      </figure>
                    </div>
                    <div class="col-lg-8 col-md-8 col-12">
                      <p>Avoid close contact(1
                        meter or 3 feet) with
                        people who are unwell
                      </p>
                    </div>
                  </div>
                </div>
                <div class="col-lg-4 col-md-4 col-12 mt-5">
                  <div class="row">
                    <div class="col-lg-4 col-md-4 col-12">
                      <figure class="text-center">
                        <img src="home.png" class="img-fluid" width="120" height="120">
                        <figcaption>Stay Homes</figcaption>
                      </figure>
                    </div>
                    <div class="col-lg-8 col-md-8 col-12">
                      <p>Stay home and self-isolate from
                        others in the household if you feel
                        unwell
                      </p>
                    </div>
                  </div>
                </div>
                <div class="col-lg-4 col-md-4 col-12 mt-5">
                  <div class="row">
                    <div class="col-lg-4 col-md-4 col-12">
                      <figure class="text-center">
                        <img src="tv.png" class="img-fluid" width="120" height="120">
                        <figcaption>Stay informed</figcaption>
                      </figure>
                    </div>
                    <div class="col-lg-8 col-md-8 col-12">
                      <p>Stay informed by watching news & follow
                        the recommended practices
                      </p>
                    </div>
                  </div>
                </div>
                <div class="col-lg-4 col-md-4 col-12 mt-5">
                  <div class="row">
                    <div class="col-lg-4 col-md-4 col-12">
                      <figure class="text-center">
                        <img src="cold.png" class="img-fluid" width="120" height="120">
                        <figcaption>cold</figcaption>
                      </figure>
                    </div>
                    <div class="col-lg-8 col-md-8 col-12">
                      <p>if you have fever. cough
                        and difficulty breathing
                        seek medical care early</p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <!********************************Contact Us Asap******************************************----->
            <div class="container-fluid  pt-5 pb-5 " id="contactid">
              <div class="section_header text-center mb-5 mt-4">
                <h1> Contact Us ASAP </h1>
              </div>
              <div class="container">
                <div class="row">
                  <div class="col-lg-8 offset-lg-2 col-12">
                    <form>
                      <div class="form-group">
                        <label>Username</label>
                        <input type="name" class="form-control" name="username" placeholder="name" autocomplete="off"
                          required>
                      </div>
                      <div class="form-group">
                        <label>Phone number</label>
                        <input type="NUMBER" class="form-control" name="MOBILE NUMBER" placeholder="Mobile"
                          autocomplete="off" required>
                      </div>
                      <div class="form-group">
                        <label>Email</label>
                        <input type="email" class="form-control" name="email" placeholder="name@example.com" required
                          autocomplete="off">
                      </div>
                      <div class="form-group">
                        <label>Addresss</label>
                        <input type="Address" class="form-control" name="ADDRESS" placeholder="Address"
                          autocomplete="off" required>
                      </div>
                      <div class="form-group">
                        <label>District</label>
                        <input type="name" class="form-control" name="District" placeholder="District"
                          autocomplete="off" required>
                      </div>
                      <div class="form-group">
                        <label>Pin Code</label>
                        <input type="NUMBER" class="Pin-Code" name="Pin-Code" placeholder="Pin-Code" autocomplete="off"
                          required>
                      </div>

                      <!**************************check-box section************************-------->
                        <div class="form-group">
                          <label> Select Symptoms</label> <br>

                          <div class="custom-control custom-checkbox custom-control-inline text-capitalize">
                            <input type="checkbox" class="custom-control-input" id="customcheckboc1" name="coronasym[]"
                              value="cold">
                            <label class="custom-control-label" for="customcheckbox1">Cold</label>
                          </div>

                          <div class="custom-control custom-checkbox custom-control-inline text-capitalize">
                            <input type="checkbox" class="custom-control-input" id="customcheckboc2" name="coronasym[]"
                              value="cold">
                            <label class="custom-control-label" for="customcheckbox2">Fever</label>
                          </div>
                          <div class="custom-control custom-checkbox custom-control-inline text-capitalize">
                            <input type="checkbox" class="custom-control-input" id="customcheckboc3" name="coronasym[]"
                              value="cold">
                            <label class="custom-control-label" for="customcheckbox3">Difficulty in Breath</label>
                          </div>
                          <div class="custom-control custom-checkbox custom-control-inline text-capitalize">
                            <input type="checkbox" class="custom-control-input" id="customcheckboc4" name="coronasym[]"
                              value="cold">
                            <label class="custom-control-label" for="customcheckbox4">Feeling weak</label>
                          </div>
                          <div class="custom-control custom-checkbox custom-control-inline text-capitalize">
                            <input type="checkbox" class="custom-control-input" id="customcheckboc5" name="coronasym[]"
                              value="cold">
                            <label class="custom-control-label" for="customcheckbox5">Cough</label>
                          </div>
                        </div>

                        <div class=" form-group">
                          <label for="exampleFormControlTextarea1">Describe how are feeling</label>
                          <textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
                        </div>
                        <button type="submit" class="btn btn-primary">Submit</button>
                    </form>
                  </div>
                </div>
              </div>
            </div>
            <!**************************** top curser ***********************************->
              <div class="container scrolltop float-right pr-5">
                <i class="fa fa-arrow-up" onclick="topFunction()" id="myBtn"></i>
              </div>
              <!****************************footer******************************----->
                <footer class="mt-5 ">
                  <div class="footer_style text-white text-center container-fluid">
                    <p>Copyright by Satish Arya(small contribute to corona patient)</p>
                  </div>
                </footer>
                <!**************************javascript**************************->
                  <script type="text/javascript">
                    $('.count').counterUp({
                      delay: 10,
                      time: 3000
                    })
                    mybutton = document.getElementById("myBtn");

                    window.onscroll = function () { scrollFunction() };
                    function scrollFunction() {
                      if (document.body.scrollTop > 100 || document.documentElement.scrollTop > 100) {
                        mybutton.style.display = "block";
                      } else {
                        mybutton.style.display = "none";
                      }
                    }
                    function topFunction() {
                      document
                      document.body.scrollTop = 0;

                    }


                  </script>
</body>

</html>

