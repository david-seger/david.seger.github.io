<!DOCTYPE html>
<html lang="en-us">
    <head>
        <meta charset="UTF-8">
        <title>Latitude</title>
        <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" 
        integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container-fluid">
            <div class="navbar-header teal text-center">
                <a class="navbar-brand" href="index.html">
                    <span style="color:white">Latitude</span>
                </a>
            </div>
            <div class="navbar-toggler" type="button" data-toggle="collapse" data-target="#mainNavBar">
                <span class="navbar-toggler-icon"></span>
            </div>
            <div class="collapse navbar-collapse" id="mainNavBar">
                <ul class="nav navbar-nav ml-auto">
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                        Plots
                        </a>
                        <div class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
                            <a class="dropdown-item" href="maximumtemprature.html">Temperature</a>
                            <a class="dropdown-item" href="humidity.html">Humidity</a>
                            <a class="dropdown-item" href="cloudiness.html">Cloudiness</a>
                            <a class="dropdown-item" href="windspeed.html">Wind Speed</a>
                        </div>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="comparison.html">Comparison</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="data.html">Data</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
    <br>
    <br>
    <div class="card md-2">
        <h5 class="card-title">Summary: Lattitude vs X</h5>
        <div class="row no-gutters">
            <div class="col-md-4">
                <img src="Resources/assets/images/Fig1.png" class="card-img" alt="Maximum Temperature">
                <div class="card-body">
                    <p class="card-text">The purpose of this project was to analyze weather changes as you get closer to the equator. To accomplished the 
                        analysis we first pulled data from the OpenWeatherMap API to assemble a dataset on over 500 cities.
                    <br>
                    <br>
                    After assembling the dataset, we used Matplotlib to plot various aspects of the weather vs. lattitude.  Factos we looked at included:
                    temperature, cloudiness, wind speed and humidity.  This site provides the source data and Visualizations created as part of the 
                    analysis as well as explanations and descriptions of any trends and correlations witnessed.
                    </p>
                </div>
            </div>
            <div class="col-md-6">
                <div class="card">
                    <div class="card-body">
                        <h3 class="card-title">Visualizations</h3>
                        <hr>
                        <div class ="text-center">
                            <div>
                                <a href="maximumtemprature.html" >
                                    <img src="Resources/assets/images/Fig1.png" alt="Maximum Temperature" class="img-fluid" height="325" width="325" >
                                </a>
                                <a href="humidity.html" >
                                    <img src="Resources/assets/images/Fig2.png" alt="Humidity" class="img-fluid" height ="325" width="325">
                                </a>
                                <a href="cloudiness.html" >
                                    <img src="Resources/assets/images/Fig3.png" alt="Cloudiness" class="img-fluid" height ="325" width="325">
                                </a>
                                <a href="windspeed.html" >
                                    <img src="Resources/assets/images/Fig4.png" alt="Wind Speed" class="img-fluid" height ="325" width="325">
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
   
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
    </body>
</html>