<p align="center"><img width=12.5% src="https://github.com/ScorchingShade/Pinch/blob/master/img/pinch_logo.png"></p>


<p align ="center"> A Minimalistic css Library for quickly bootstrapping your project</p>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![Python](https://img.shields.io/badge/python-v3.6+-blue.svg)
[![GitHub Issues](https://img.shields.io/github/issues/ScorchingShade/Pinch.svg)](https://github.com/ScorchingShade/Pinch/issues)
![Contributions welcome](https://img.shields.io/badge/contributions-welcome-orange.svg)

## Basic Overview
No need to code your own css mini-library to get-rid of hefty frameworks like bootstrap whenever starting a small project!
<br>
PinchX takes care of your basic web design building a beautiful simplistic design in minutes!
<br>
Written in SCSS/SASS, the generated css is comprehensive, simple and minimal!

<p align="center"><img src="https://github.com/ScorchingShade/Pinch/blob/master/img/pinch_main.jpg"></p>

### An All New Grid System
PinchX introduces a 15 way grid sytem to have greater flexibility when designing your web-page
<br>
Using class "col-x", where x is numbered from 1-15 you can create a grid with 15 valid points.
```html
<div class="row">
            <div class="col-15">15</div>
            <div class="col-14">14</div>
            <div class="col-1">1</div>
            <div class="col-13">13</div>
            <div class="col-2">2</div>
            <div class="col-12">12</div>
            <div class="col-3">3</div>
            <div class="col-11">11</div>
            <div class="col-4">4</div>
            <div class="col-10">10</div>
            <div class="col-5">5</div>
            <div class="col-9">9</div>
            <div class="col-6">6</div>
            <div class="col-8">8</div>
            <div class="col-7">7</div>
            <div class="col-6">6</div>
            <div class="col-9">9</div>
            <div class="col-7">7</div>
</div>
```

<p align="center"><img src="https://github.com/ScorchingShade/Pinch/blob/master/img/pinch_grid.jpg"></p>

<br>
<br>


## Beautiful Engaging Cards
PinchX gives three beautiful cards to choose from.
- Basic Card
- Fluid Card
- Product Card
<br>
With PinchX, you can quickly create a card that suits your needs!<br>

### Basic Card
This simplistic card is perfect for displaying your data in a cool minimalistic way!
<br>

```
            <div class="card-basic ">
                <div class="card-title">
                    This is a basic card
                </div>
                <div class="card-subtitle">
                    This is a subtitle
                </div>
                <div class="card-body">
                    This is a body
                </div>
                <div class="card-footer">
                    A card footer
                </div>
            </div>

```
<br>
Set your class to "card-basic" to start using a basic card. <br>
The class "card-title" provides a bold title to the card.<br>
The class "card-subtitle" provides a subtitle text to the card.<br>
I recommend using "card-body" to make sure you get a defined, non overflowing, card body.<br>
The class "card-footer" allows to set a detailed footer for the basic card.<br>

<br>
<p align="center"><img src="https://github.com/ScorchingShade/Pinch/blob/master/img/pinch_basic_card.jpg"></p>
<br>

### Fluid Card
The fluid card works similar to the basic card, with just the difference that it can occupy the width of the parent element its placed in!
<br>

```
 <div class="card-fluid ">
            <div class="card-title">
                This is a Fluid card
            </div>
            <div class="card-subtitle">
                This card type takes the width of the container
            </div>
            <div class="card-body">
                This is a body
            </div>
            <div class="card-footer">
                A card footer
            </div>
        </div>
```
<br>
Use the class "card-fluid" to use the Fluid Card.
<br>
<p align="center"><img src="https://github.com/ScorchingShade/Pinch/blob/master/img/pinch_fluid_card.jpg"></p>
<br>

### Product Card
The product card is a special card that helps in creating a cool new unique way of diplaying elements as a showcase.

```
            <div class="card">
                <div class="card-image">
                    <img src="https://psmag.com/.image/t_share/MTI5MzkwNTAwMTcwOTk2MTkw/watch-dmjpg.jpg" alt="img">
                </div>
                <div class="card-prime">
                </div>
                <div class="card-info">
                    <div class="card-icon">
                        <img src="https://www.shareicon.net/data/2016/04/26/755602_apple_512x512.png" alt="icon"> Watches
                    </div>
                </div>
                <div class="card-name">
                    This is a product card
                </div>
            </div>
```
The class "card" helps you use the Product card.<br>
You can also set the image for the card using class "card-image" and then providing an image as a source.<br>
The class "card-prime" is optional to use, but when used in a div, provides a unique diagonal background object to style the card.<br>
The class "card-info" plays the role of defining the card body elements.<br>
The class "card-icon" can be used to set a small preferably, png icon to the body.<br>
The class "card-name" give the information to about the product card's descriptive name.<br>
<br>
<p align="center"><img src="https://github.com/ScorchingShade/Pinch/blob/master/img/pinch_product_card.jpg"></p>
<br>

---

## The Angel and Dracula Elements - Navbar
PinchX provides two theme options - **Dracula** and **Angel**.<br><br><br>
Checkout the simplest way to build a navbar, with the PinchX Dracula and Angel themed navbar!

```
<div class="container-ex nav-dracula">
        <header>
            <img class="logo" src="https://cdn4.iconfinder.com/data/icons/social-icon-4/842/facebook-512.png" alt="logo">
            <nav>
                <ul class="nav_link">
                    <li><a href="#">Link 1</a></li>
                    <li><a href="#">Link 2</a></li>
                    <li><a href="#">Link 3</a></li>

                </ul>

            </nav>
            <a class="cta" href="#"><button class="btn-nav">Contact</button></a>
        </header>

    </div>
```

<br>
<br>
<p align="center"><img src="https://github.com/ScorchingShade/Pinch/blob/master/img/pinch_navs.jpg"></p>
<br>
You can change the theme of the navbar using the class "nav-dracula" or "nav-angel" in the parent div.<br>
To specify a logo use the class "logo", supports images currently. <br>
The class "nav_link" takes care of arranging all your links in a neatly arranged manner.<br>
Optionally you can add a navbar button using class "btn-nav" to further enhance the navbar.<br>
<br>
<br>

## The Angel and Dracula Elements - Footer
A goot footer must contain all the necessary contact info, links and a message form all in itself. Using this info, PinchX gives you a complete template to create a **comprehensive footer from scratch!**

```
    <div>
        <div id="changeDiv" class="footer-angel">
            <div class="footer-content">
                <div class="footer-section about">
                    <h1 class="logo-text"><span>Pinch</span>Footer</h1>

                    <p>
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    </p>
                    <div class="contact">

                        <span><i class="fas fa-phone"></i>&nbsp; 123-456-789</span><br>
                        <span><i class="fas fa-envelope"></i>&nbsp; ankushors789@gmail.com</span>

                    </div>

                    <div class="socials">

                        <a href=""><i class="fab fa-facebook"></i></a>
                        <a href=""><i class="fab fa-instagram"></i></a>
                        <a href=""><i class="fab fa-twitter"></i></a>
                        <a href=""><i class="fab fa-youtube"></i></a>

                    </div>
                </div>
                <div class="footer-section links">

                    <h2>Quick Links</h2>
                    <br>
                    <ul>
                        <a href="#">
                            <li>Events</li>
                        </a>
                        <a href="#">
                            <li>Team</li>
                        </a>
                        <a href="#">
                            <li>Mentors</li>
                        </a>
                        <a href="#">
                            <li>Gallery</li>
                        </a>
                        <a href="#">
                            <li>Terms</li>
                        </a>
                    </ul>

                </div>
                <div class="footer-section contact-form">

                    <h2>Contact us</h2>
                    <br>
                    <form action="index.html" method="post">
                        <input type="email" name="email" class="text-input contact-input disp-xs" placeholder="Your Email Address....."><br><br>
                        <textarea name="message" class="text-input contact-input disp-xs" placeholder="Your Message...."></textarea><br><br>
                        <button type="submit" class="btn-nav contact-btn">
                        <i class="fas fa-envelope"></i>
                        Send</button>

                    </form>

                </div>
            </div>

            <div class="footer-bottom">
                powered by <a href="https://github.com/ScorchingShade/Pinch">ScorchingShade</a>

            </div>
        </div>
    </div>
```

<br>
Understanding all the elements of this footer is easy too! 


