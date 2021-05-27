# SHAPEAI WEB DEV WITH BOOTSTRAP BOOTCAMP
Hi I made this project during the 7 Days Free Bootcamp, conducted by <b> SHAPEAI
</b>.
The instructor during the session was Mr. Shaurya Sinha (Data Analyst Intern at Jio). I got to
learn a lot during these 7 days and it was an amazing experience learning with SHAPEAI.
<br><br>Here's the link for you to watch the sessions as well<br>
<a href="https://www.youtube.com/playlist?list=PL7zl8TDRnbumsiEeX4lkDw5D_NZ1WVEy3"> <img src="https://github.com/ShapeAI/PYTHON-AND-DATA-ANALYTICS/blob/main/YOUTUBE%20THUMBNAIL.png"> </a>
<br>I got to have hands on experience on:
<li>HTML
<li>CSS
<li>BOOTSTRAP
<br>during these 7 days, and everything was explained from the very basics so that
anyone with zero experience on programming can learn.
I enjoyed these 7 days, you can as well. To register for next free 7 days bootcamp, visit:
www.shapeai.tech
or follow SHAPEAI on:
<li><a href=
"https://in.linkedin.com/company/shapeai">LinkedIn</a>
<li><a href=
"https://www.instagram.com/shape.ai/?hl=en">Instagram</a>
<li><a
href=
"https://www.youtube.com/channel/UCTUvDLTW9meuDXWcbmISPdA">YouTu
be</a>
<li><a href=
"https://github.com/shapeai">GitHub</a>


<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-+0n0xVW2eSR5OomGNYDnhzAbDsOXxcvSN1TPprVMTNDbiYZCxYbOOl7+AMvyTG2x" crossorigin="anonymous">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" integrity="sha512-iBBXm8fW90+nuLcSKlbmrPcLa0OT92xO1BIsZ+ywDWZCvqsWgccV3gFoRBv0z+8dLJgyAHIhR35VZc2oM/gI1w==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>

<body>
    <!-- Navbar  -->
    <nav class="navbar sticky-top navbar-expand-lg navbar-dark bg-primary ">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">Deep Jaha</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false"
                aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#hero">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#skills">My Skills</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#works">MyWorks</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#contact">Contactme</a>
                    </li>
                </ul>

            </div>
        </div>
    </nav>


    <main class="container mt-3">

        <section id="hero" class="d-flex justify-centre flex-column-reverse align-items-center justify-content-md-evenly justify-content-sm-center gap-3 flex-md-row ">

            <!--  Hero  -->
            <div class="d-flex justify-content-sm-center align-items-center flex-column align-items-md-start">
                <h5>Hi!👋</h5>
                <h1>I'm Deep Jaha</h1>
                <p>Fulll stack Web-developer!</p>
                <button class="btn btn-primary btn-sm">My Cool Resume</button>
            </div>
            <div class="d-md-none h-50 w-50 ">
                <img src="https://media.istockphoto.com/photos/portrait-of-smiling-handsome-man-in-blue-tshirt-standing-with-crossed-picture-id1045886560?k=6&m=1045886560&s=612x612&w=0&h=hXrxai1QKrfdqWdORI4TZ-M0ceCVakt4o6532vHaS3I=" alt="Deep Jaha" class=" h-100 w-100 rounded-circle">
            </div>
            <div class="d-none d-md-block h-25 w-25 ">
                <img src="https://media.istockphoto.com/photos/portrait-of-smiling-handsome-man-in-blue-tshirt-standing-with-crossed-picture-id1045886560?k=6&m=1045886560&s=612x612&w=0&h=hXrxai1QKrfdqWdORI4TZ-M0ceCVakt4o6532vHaS3I=" alt="Deep Jaha" class=" h-100 w-100 rounded-circle">
            </div>
            </section>

        <section id="skills" class="mt-5 p-4">
        <!-- My Skills-->

        <h1 class="text-primary text-center">My Skill-Set</h1>
        <div class="mt-4 d-md-none d-flex justify-content-evenly">
            <i class="fab fa-html5 fa-3x" style="color: #f4470b;"></i>
            <i class="fab fa-css3-alt fa-3x text-primary"></i>
            <i class="fab fa-bootstrap fa-3x" style="color: #730fef;"></i>
        </div>
        <div class="mt-4 d-none d-md-flex justify-content-evenly">
            <i class="fab fa-html5 fa-7x" style="color: #f4470b;"></i>
            <i class="fab fa-css3-alt fa-7x text-primary"></i>
            <i class="fab fa-bootstrap fa-7x" style="color: #730fef;"></i>
        </div>
    </section>
    <section id="works" class="mt-5 p-4">
            <!-- My Works-->
            <h1 class="text-primary text-center">My Works</h1>
            
            <div class="d-flex flex-column flex-md-row justify-content-md-evenly gap-3">  
                <div class="card mb-2">
                <img src="https://images.unsplash.com/photo-1488590528505-98d2b5aba04b?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=750&q=80" class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title">Portfolio</h5>
                  <p class="card-text">Built an amazing website using bootstrap, css, and html </p>
                  <a href="#" class="btn btn-dark">View Source <i class="fab fa-github"></i></a>
                </div>
              </div> 

              <div class="card mb-2">
                <img src="https://images.unsplash.com/photo-1488590528505-98d2b5aba04b?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=750&q=80" class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title">Portfolio</h5>
                  <p class="card-text">Built an amazing website using bootstrap, css, and html </p>
                  <a href="#" class="btn btn-dark">View Source <i class="fab fa-github"></i></a>
                </div>
              </div> 

              <div class="card mb-2">
                <img src="https://images.unsplash.com/photo-1488590528505-98d2b5aba04b?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=750&q=80" class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title">Portfolio</h5>
                  <p class="card-text">Built an amazing website using bootstrap, css, and html </p>
                  <a href="#" class="btn btn-dark">View Source <i class="fab fa-github"></i></a>
                </div>
              </div>
            </div> 

    </section>
        <section id="contact" class="mt-4 py-4">
            <!-- Contact me -->
            <h1 class="text-primary text-center">Contact Form</h1>
            <div class="row">
                <div class="col-sm col-md-8">
            <form>
                <div class="mb-3">
                    <label for="exampleFormControlInput1" class="form-label">Email address</label>
                    <input type="email" required class="form-control" id="exampleFormControlInput1" placeholder="name@example.com">
                  </div>
                  <div class="mb-3">
                    <label for="exampleFormControlTextarea1" class="form-label">Your Message</label>
                    <textarea class="form-control" id="exampleFormControlTextarea1" required placeholder="Enter your messege" rows="3"></textarea>
                  </div>
                  <button type="submit" class="btn btn-primary">Submit</button>
            </form>
            </div>
            <div class="col-sm col-md-4">
            <div class="mt-3 ">
                <h4><i class="fas fa-envelope-square"></i>deepjaha@gmail.com</h4>
                <button type="button" class="mt-3 btn btn-outline-primary btn-link">
                    <a href="https://github.com/"><i class="fab fa-github fa-2x"></i></a>
                </button>
            </div>
        </div>
        </section>
    </main>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-gtEjrD/SeCtmISkJkNUaaKMoLD0//ElJ19smozuHV6z3Iehds+3Ulb9Bn9Plx0x4"
        crossorigin="anonymous"></script>
</body>

</html>
