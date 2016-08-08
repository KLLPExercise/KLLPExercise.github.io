<!DOCTYPE html>
<html>
	<head lang="en">
    <link rel="stylesheet" href="mystylesheet.css"> 
    <script src="websitescript.js"></script>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
        
        <!-- Latest compiled and minified CSS -->
    <link rel="stylesheet" href="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css">

        <!-- jQuery library -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>

        <!-- Latest compiled JavaScript -->
    <script src="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js"></script>
    <script src="final_project_javascript.js"> </script>
    
  </head>
  <body>
  <h1>
    	KLLP Exercise
      <!-- quote genarator -->  
  </h1>
 <div class="well">
 <title>Quote genarator</title>


<body onload="randquote() ; alertuser();">
<p id="quote"> </p>
</div>  
<!-- tabs --> 
  <ul class="nav nav-pills nav-stacked">
    <li class="active"><a data-toggle="pill" href="#home">Home</a></li>
    <li><a data-toggle="pill" href="#calendar">Calendar</a></li>
    <li><a data-toggle="pill" href="#goaltracker">Goal Tracker</a></li>
    <li><a data-toggle="pill" href="#fitplan">Fit Plan</a></li>
  </ul>
  <!-- home page tab content --> 
    <div class="tab-content">
        <div id="home" class="tab-pane fade in active">
            <div class="container">
  <div class="well">
  <ul class="nav nav-pills">
  <li><a data-toggle="pill" href="#missionstatement">Mission Statement</a></li>
  <li><a data-toggle="pill" href="#aboutus">About Us</a></li>
  </ul>
  <div class="tab-content">
  <div id="missionstatement" class="tab-pane fade">
      <h4>Welcome to KLLP Exercise! We are dedicated to help our users stay motivated when
    working out. We will provide a daily quote everyday to keep a postive mindset for
    our users. We will also have montly goals and when you reach your goal, you will
    be rewarded at the end of the month. Some examples of the rewards would be coupons,
    movie tickets and ect.</h4>
    </div>
    <div id="aboutus" class="tab-pane fade">
      <h4>KLLP was founded Kayla, Lucciana, Lusia, Priscilla. We were part of Girls Who Code 2016 and as a final
    project we all decide we would like to help others stay motivated when working out. Everyone can relate
    that sometimes you have no motivation to work out. So by using our website you can stay postive and look
    forward to your next workout. Also by using our website you don't just get the satisfaction of a fit body
    but you also get a reward for completing your monthly goal.
      </h4>
     </div>
    </div>
  </div>
</div>
</h3>
<!-- alert --> 
<div class="container">
  <h2>Alerts</h2>
  <div class="alert alert-success">
    <strong>Success!</strong> This alert box indicates a successful monthly workout!
  </div>
  	<div class="alert alert-warning">
    <strong>Warning!</strong> This alert box indicates a warning that you are a couple of workouts away from meeting your monthly reward!
  </div>
  <div class="alert alert-danger">
    <strong>Danger!</strong> This alert box indicates you need to pay attention to your monthly workout goals.
  </div>
</div>
    
    <!-- rewards --> 
    <h2> Possible Rewards</h2>
    <div class="well">
    <ul class="nav nav-pills">
  <li><a data-toggle="pill" href="#shopping">Shopping Coupons</a></li>
  <li><a data-toggle="pill" href="#food">Food Coupons</a></li>
  <li><a data-toggle="pill" href="#free">Free Stuff</a></li>
  </ul>
  <div class="tab-content">
  <div id="shopping" class="tab-pane fade">
  <p> Yankee Candle $10 off any purchase </p>
  <p>Express 15% off </p>
  <p> Bed Bath & Beyond 20% off 1 item in-store </p>
  <p> Finish Line $10 off online only </p>
  <p> Aeropostale 30% off one item </p>
  </div>
  <div id="food" class="tab-pane fade">
  <p> Papa Johns 40% off Regular Menu Price Orders </p>
  <p> Ruby Tuesday Buy 1 Get 1 50% off Adult Entree </p>
  <p> Olive Garden $5 Off Any Two Dinner Entrees </p>
  <p> Pizza Hut Any Large Pizza For $11 </p>
  <p> Steak n Shake $1 off Specialty Milkshake </p>
  </div>
  <div id="free" class="tab-pane fade">
  <p> Baskin Robbins Free Waffle Cone With Purchase Of A Double Scoop </p>
  <p> Krispy Kreme Free Original Glazed Doughnut with Any Beverage Purchase </p>
  <p> 7/11 Free Slupree on 7/11 </p>
      </div>
    </div>
  </div>
  </div>
    <!-- other tabs --> 
    <div id="calendar" class="tab-pane fade">
        <h3>Calendar</h3>
    </div>
    <div id="goaltracker" class="tab-pane fade">
      <h3>Goal Tracker</h3>
    </div>
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    <div id="fitplan" class="tab-pane fade">     <!--fitplan start-->
      <h3>Fit Plan</h3>
      <style>
    /* Remove the navbar's default margin-bottom and rounded borders */
    .navbar {
      margin-bottom: 0;
      border-radius: 0;
    }
    
    /* Add a gray background color and some padding to the footer */
    footer {
      background-color: #f2f2f2;
      padding: 25px;
    }
    
  .carousel-inner img {
      width: 100%; /* Set width to 100% */
      margin: auto;
      min-height:200px;
  }

  /* Hide the carousel text when the screen is less than 600 pixels wide */
  @media (max-width: 600px) {
    .carousel-caption {
      display: none;
    }
  }
  </style>
  <div id="myCarousel" class="carousel slide" data-ride="carousel">
    <!-- Indicators -->
    <ol class="carousel-indicators">
      
    </ol>

    <!-- Wrapper for slides -->
    <div class="carousel-inner" role="listbox">
      <div class="item active">
        <img src="https://assets.rbl.ms/3434684/1200x400.jpg" alt="Image">
        <div class="carousel-caption">
          
        </div>
      </div>

      <div class="item">
        <img src="https://irp-cdn.multiscreensite.com/626c49ad/import/base/arrow-home-entertainment-fitness-workout.jpg" alt="Image" width="120" height="40">
        <div class="carousel-caption">
          
        </div>
      </div>
    </div>

    <!-- Left and right controls -->
    <a class="left carousel-control" href="#myCarousel" role="button" data-slide="prev">
      <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="right carousel-control" href="#myCarousel" role="button" data-slide="next">
      <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
      <span class="sr-only">Next</span>
    </a>
</div>
  
<div class="container text-center">
  <h3>Pick Your Plan</h3><br>
  <div class="row">
  
    <div class="col-sm-4">
    
      <img src="http://images.shape.mdpcdn.com/sites/shape.com/files/styles/facebook_og_image/public/story/fielddayspringplaylist_0.jpg?itok=pzUwi038" class="img-responsive" style="width:100%" alt="Image">
    </a>
      <p>Plan A</p>
    </div>
    
    <div class="col-sm-4">
    
      <img src="http://www.gannett-cdn.com/-mm-/eca5b3f03be168c6b3e6ec526067fd90ae7bcfe3/r=x408&c=540x405/local/-/media/USATODAY/GenericImages/2013/05/23/1369341352002-Obstacles-XRT-Splash-Screen-1305231638_4_3.png" class="img-responsive" style="width:100%" alt="Image">
    </a>
      <p>Plan B</p>
       <div class="well">
    <p> Welcome to Plan B </p>
    </div>
     
    
        <h1> Workout Plan B  </h1>
    <div class="well">
    <ul class="nav nav-pills">
  <li><a data-toggle="pill" href="#week1">Week 1</a></li>
  <li><a data-toggle="pill" href="#week2">Week 2</a></li>
  <li><a data-toggle="pill" href="#week3">Week 3</a></li>
  <li><a data-toggle="pill" href="#week4">Week 4</a></li>
  </ul>
  <div class="tab-content">
  <div id="week1" class="tab-pane fade">
  <p> Monday (Arm Day): Dumbbells Curls, Forearm Planks, Chair Dips, Hover Rotation, Push-ups (3 sets, 15 reps) </p>
  <p> Tuesday (Ab Day): Sit-ups, Side abs (swiss ball), Plank, Side Plank, Jack-knife ball (3 sets, 15 reps)  </p>
  <p> Wednesday (Back Day): Arnold Press, Cobra + Swim mat, Pull-down, Dumbbell Row, Dumbbell Push-Up (3 sets, 15 reps) </p>
  <p> Thursday (Legs & Butt Day): Squats with BOSU, Lunges, Quadracep, Doggy Raise, Hip aductors, Machine Thighs (3 sets, 15 reps) </p>
  <p> Friday (Run): 2 miles </p>
  </div>
  <div id="week2" class="tab-pane fade">
  <p> Monday: 20 Squats, 15 Second Plank, 25 Crunches, 35 Jumping Jacks, 15 Lunges, 25 Second Wall Sit, 10 Sit Ups, 10 Butt Kicks, 5 Push Ups </p>
  <p> Tuesday: 10 Squats, 30 Second Plank, 25 Crunches, 10 Jumping Jacks, 25 Lunges, 45 Second Wall Sit, 35 Sit Ups, 30 Butt Kicks, 10 Push Ups </p>
  <p> Wednesday: 15 Squats, 40 Second Plank, 30 Crunches, 50 Jumping Jacks, 25 Lunges, 35 Second Wall Sit, 30 Sit Ups, 25 Butt Kicks, 15 Push Ups </p>
  <p> Thursday: 35 Squats, 30 Second Plank, 20 Crunches, 25 Jumping Jacks, 15 Lunges, 60 Second Wall Sit, 55 Sit Ups, 35 Butt Kicks, 20 Push Ups </p>
  <p> Friday: 25 Squats, 60 Second Plank, 30 Crunches, 55 Jumping Jacks, 60 Lunges, 45 Second Wall Sit, 40 Sit Ups, 40 Butt Kicks, 25 Push Ups </p>
  </div>
  <div id="week3" class="tab-pane fade">
  <p> Monday: Arms (3 sets of 10): Flat Chest Presses, Seated Shoulder Presses, Single Arm Row, Upright Rows, Hammer Curls, Tricep Kickbacks Abs: 100 Standing Crunches, 100 Basic Side Isolations, 100 Bicycle Crunches </p>
  <p> Tuesday: Legs & Abs (3 sets): Squats Down for 10, Front Luges 10 each leg, Plank for 30 seconds, Squats Pulse for 10, Front Lunges 10 each leg, Plank for 60 seconds, Squats Mold for 10, Front Lunges 10 each leg, Plank for 60 seconds </p>
  <p> Wednesday: Arms (3 sets of 10): Flat Chest Files, Lateral Raises, Single Arm Row, Front Raises, Concentration Curis, French Presses. Abs: 50 Crunches (regular and reverse), 50 Oblique Crunches, 100 Bicycle Crunches, 100 Standing Crunches </p>
  <p> Thursday: Legs & Abs (3 sets): Squats Down for 10, Front lunges (10 each leg), Plank for 30 seconds, Squats Pulses for 10, Front Lunges (10 each leg), Squats Pulse for 10, Front Lunges 10 each leg, Plank for 45 seconds, Squats Hold for 10, Front Lunges 10 each leg, Plank for 60 seconds </p>
  <p> Friday: Arms (3 sets of 10): Flat Chest Presses, Seated Shoulder Presses, Single Arm Row, Hammer Curls, Tricep Kickbacks Abs: 100 Standing Crunches, 100 Basic Side Isolations, 100 Bicycle Crunches </p>
      </div>
  <div id="week4" class="tab-pane fade">
  <p> Monday: 150 Jumping Jacks, 50 Crunches, 20 Tricep Dips, 15 Squats, 20 Lunges each leg, 70 Russian Twist, 20 Standing Calf Raises, 5 Push ups, 50 Second Plank, 10 Lunge Split Jumps</p>
  <p> Tuesdays: 80 Jumping Jacks, 50 Vertical Leg Crunches, 20 Sit-Ups, 15 Tricep Dips, 20 Squats, 10 Side Lunges each leg, 10 Leg Lifts each leg, 50 Bicycle, 15 Push Ups, 40 Russian Twists </p>
  <p> Wednesday: 90 Jumping Jacks, 20 Tricep Dips, 10 Sit-Ups, 30 Bird-Dogs, 30 Second Plank, 30 Squats, 40 Crunches, 10 Oblique Crunches each side, 20 Standing Calf Raises </p>
  <p> Thursday: 100 Jumping Jacks, 25 Vertical Leg Crunches, 20 Squats, 20 Push-Ups, 50 Russian Twists, 15 Second Side Plank each side, 10 Lunge Split Jumps, 5 Jump Squats, 40 High Knees </p>
  <p> Friday: 60 Jumping Jacks, 40 Crunches, 10 Sit-Ups, 10 Tricep Dips, 20 slide Lunges, 15 Incline Push-Ups, 10 Oblique Crunches each side, 50 Butt Kicks, 15 Sit-ups </p>
  </div>
  </div>
  </div>
  </div>
    
    </div>
    
    <div class="col-sm-4">
   
      <img src="http://images.shape.mdpcdn.com/sites/shape.com/files/styles/facebook_og_image/public/story/woman-runner-headphones-700x700_0.jpg?itok=CetA_ISE" class="img-responsive" style="width:100%" alt="Image">
    </a>
      <p>Plan C</p>
    </div>
      
    </div>
  </div> <!-- fitplan end-->
  
  
  
  
  
  
  
  
  
  
  
  
</div><br>



<footer class="container-fluid text-center">
  <p>Footer Text</p>
</footer>




    </body>
</html>
