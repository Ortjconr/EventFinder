# EventFinder
An Event Collector Website that collects links and updates events based on the searched zipcode.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <div class="topnav">


  <title>FED</title>

  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">

  <link rel="stylesheet" href="https://bootswatch.com/4/cyborg/bootstrap.min.css">

  <link rel="stylesheet" href="Home.css">
</head>
<body>

    <!-- NAVBAR -->
    <nav class="navbar navbar-light bg-light">
      <a class="navbar-brand" href="#">Event Finder!</a>
      <div class="navbar-nav">
        <ul>
          <a href="Home.html">Home</a>
          <a href="OurMission.html">Our Mission</a>
          <a href="Events.html">Events Nearby</a>
          <a href="ContactUs.html">Contact Us!</a>
        </ul>
      </div>
    </nav>

  <!-- HERO -->
  <div class="jumbotron text-center hero-background-img">
    <h1><u><b>Welcome to the Event Finder!</b></u></h1>
    <p class="lead">Finding the Best Local Events!</p>
  </div>
</div>


<div class="login-container">
  <form action="/action_page.php">
    <input type="text" placeholder="Username" name="username">
    <input type="text" placeholder="Password" name="psw">
    <button type="submit">Login</button>
  </form>
</div>
<!-- BENEFITS -->
<div class="container mb-5 mt-5">
  <div class="row">
<div class="col-lg-4">
  <h3><u>Welcome!</u></h3>
  <p class="lead"></p>
  <p>
   <ul>
    <li> Our purpose is bring forward events in order to ensure you have the
      up-to-date information on specified events of your choice and in your area! </li>
   </ul>

      <div class="col-lg-4">
        <h3><u>Saved Updates</u></h3>
        <p class="lead"></p>
        <p>
         <ul>
          <li>  Leather Pride Gathering @5:30pm, Folsom St. San Francisco.</li>
          <li>  Pride Parade @9:00am, 12 & 17th Castro, San Francisco.</li>
          <li>  Swap Meet @10:00am, Market St, San Francisco.</li>
          <li>  Queer History Month Celebration @11:00am Union Square, San Francisco.</li>

        </p>
        </div>
        <div class="col-lg-4">
          <h3><u>Cancelled Events.</u></h3>
          <p class="lead"></p>
          <p>
            <ul>
              <li>Flea Market is closed from March 27th-April 3rd. </li>
              <li>Castro Street Fair postponed. </li>
              <li>City Hall Meeting moved to zoom</li>
            </ul>

          </p>
          </div>
        </div>
      </div>

      <!-- CALL TO ACTION-->
      <div class="jumbotron text-center mb-0">
        <p class="lead mb-4">Sign Up for Email Alerts</p>
        <div class="d-flex justify-content-center">
          <form action="#" class='form-inline'>
            <input type="text" class="form-control mb-2 mr-sm-2" placeholder="Email"/>
            <button type="submit" class="btn btn-primary mb-2">Submit</button>
          </form>
        </div>
      </div>
      <!-- FOOTER -->
      <div class="bg-secondary p-5 text-white">
        &copy; 2021 Launch Page INC
      </div>
