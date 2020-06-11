﻿@{
    ViewData["Title"] = "Nameless Store";
}

<div id="myCarousel" class="carousel slide" data-ride="carousel" data-interval="9000">
    <ol class="carousel-indicators">
        <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
        <li data-target="#myCarousel" data-slide-to="1"></li>
    </ol>
    <div class="carousel-inner" role="listbox">
        <div class="item active">
            <img src="~/images/banner1.svg" alt="ASP.NET" class="img-responsive" />
            <div class="carousel-caption" role="option">
                <p>
                    Buy your own vehicle.
                    <a class="btn btn-default" href="http://localhost:50157/Home/Brands">
                        Click here.
                    </a>
                </p>
            </div>
        </div>
        <div class="item">
            <img src="~/images/banner2.svg" alt="Visual Studio" class="img-responsive" />
            <div class="carousel-caption" role="option">
                <p>
                    Powerful performance parts to build your car.
                    <a class="btn btn-default" href="http://localhost:50157/Home/Performance_Parts">
                        Click here.
                    </a>
                </p>
            </div>
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

<div class="row">
    <div class="col-md-3">
        <h2>Cars Sale</h2>
        <a class="btn btn-success" href="http://localhost:50157/Home/Brands"><img src="~/images/NSDealership.svg" alt="ASP.NET" class="img-responsive" /></a>
    </div>
    <div class="col-md-3">
        <h2>Do it Yourself</h2>
        <ul>
            <li><a class="btn btn-default" href="https://itstillruns.com/install-turbo-car-4802481.html">Installing a Turbocharger.</a></li>
            <li><a class="btn btn-default" href="https://www.popularmechanics.com/cars/how-to/a6008/how-to-clean-an-engine/">Clean your engine.</a></li>
            <li><a class="btn btn-default" href="https://www.hajes-racing.com/en/ecu-remap-guide-for-beginners-how-to-not-destroy-your-car/">ECU Remap</a></li>
            <li><a class="btn btn-default" href="https://www.autopia-carcare.com/inf-cockpit.html">Detailing interiors</a></li>
        </ul>
    </div>
    <div class="col-md-3">
        <h2>Trust &amp; Boost</h2>
        <ul>
            <li><a class="btn btn-default" href="https://educacaoautomotiva.com/2017/08/03/motor-ap-turbinagem/">Best Performance Engine.</a></li>
            <li><a class="btn btn-default" href="https://www.whichcar.com.au/features/wheels-tyre-test-2015-nine-brands-compared">Tyre Test</a></li>
            <li><a class="btn btn-default" href="https://www.digitaltrends.com/cars/fwd-vs-awd-vs-rwd/">FWD vs RWD vs AWD</a></li>
            <li><a class="btn btn-default" href="https://www.howacarworks.com/modifications/installing-a-turbocharger">How a Turbocharger works.</a></li>
        </ul>
    </div>

    <div class="col-md-3">
        <h2>Performance Parts</h2>
        <a class="btn btn-success" href="http://localhost:50157/Home/Performance_Parts"><img src="~/images/PerformanceParts.svg" alt="ASP.NET" class="img-responsive" /></a>

    </div>

    <h2></h2>
    <div class="col-md-4">
        <h2>Cars That You Can Buy</h2>
        <h2></h2>
        <a class="btn btn-success" href="http://localhost:50157/Home/Gol_Promo"><img src="~/images/WhatsApp Image 2019-01-21 at 17.34.42.svg" alt="ASP.NET" class="img-responsive" />Gol 1.6 Plus 1986</a>
        <a class="btn btn-success" href="http://localhost:50157/Home/Omega_Promo"><img src="~/images/omega-cd-41-1998.svg" alt="ASP.NET" class="img-responsive" />Omega CD 4.1 1995</a>
        <h2></h2>
        <h2>Click to See All Brands</h2>
        <a class="btn btn-success" href="http://localhost:50157/Home/Brands"><img src="~/images/Brands.jpg" alt="ASP.NET" class="img-responsive" /></a>

    </div>

    <div class="col-md-4">
        <h2>About Some Cars</h2>
        <h2></h2>
        <a class="btn btn-success" href="https://de.wikipedia.org/wiki/Audi_A8_D2"><img src="~/images/AudiA8.svg" alt="ASP.NET" class="img-responsive" /></a>
    </div>

    <div class="col-md-4">
        <h2>.</h2>
        <h2></h2>
        <a class="btn btn-success" href="https://www.mercedes-amg.com/en/vehicles/c-class/estate/c63.html"><img src="~/images/MBC63AMG.svg" alt="ASP.NET" class="img-responsive" /></a>
        <h2>Sporting Wheels</h2>
        <a class="btn btn-success" href="http://localhost:50157/Wheels/Index"><img src="~/images/Wheels.jpg" alt="ASP.NET" class="img-responsive" /></a>
    </div>
</div>
<img src="~/images/Menu_Nameless_Store.png" alt="ASP.NET" class="img-responsive" />
