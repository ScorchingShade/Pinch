<p align="center"><img width=12.5% src="https://github.com/ScorchingShade/Pinch/blob/master/img/pinch_logo.png"></p>


<p align ="center"> A Minimalistic css Library for quickly bootstrapping your project</p>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![GitHub Issues](https://img.shields.io/github/issues/ScorchingShade/Pinch.svg)](https://github.com/ScorchingShade/Pinch/issues)
![Contributions welcome](https://img.shields.io/badge/contributions-welcome-orange.svg)

## Basic Overview - Version 1.02
- Update -> Footer is now Responsive
<br>
No need to code your own css mini-library to get-rid of hefty frameworks like bootstrap whenever starting a small project!
<br>
PinchX takes care of your basic web design building a beautiful simplistic design in minutes!
<br>
Written in SCSS/SASS, the generated css is comprehensive, simple and minimal!

<p align="center"><img src="https://github.com/ScorchingShade/Pinch/blob/master/img/pinch_main.jpg"></p>
<br>
<br>

Live example [here](https://scorchingshade.github.io/Pinch/).


<br>
<br>

## Upcoming and bugs
Responsive support for navbar and footer coming soon. The site is best viewed in Google-Chrome on pc.
<br>
<br>

## Getting Started
Just clone the repo and copy the main.css file in your project folder.<br>
Further use the meta linking to link the stylesheet to your project as - <br>

```
<link rel="stylesheet" href="main.css">
```

<br>
To use the complete functionality of PinchX, it is recommended to also load font-awesome-icons in your project.<br>

```
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" integrity="sha384-wvfXpqpZZVQGK6TAh5PVlGOfQNHSoD2xbE+QkPxCAFlNEevoEH3Sl0sibVcOQVnN" crossorigin="anonymous">

    <script src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.14.0/js/all.min.js" integrity="sha512-YSdqvJoZr83hj76AIVdOcvLWYMWzy6sJyIMic2aQz5kh2bPTd9dzY3NtdeEAzPp/PhgZqr4aJObB3ym/vsItMg==" crossorigin="anonymous"></script>
```
<br>
<br>
<h1 align="center"> Diving into PinchX </h1>
<br>
<br>


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
Now with version update 1.01, navbar supports responsive behaviour as well!
<br>
The dropdown is completely managed using css with no js overhead!

<br>
<br>
Dracula

```
        <div>
            <input type="checkbox" id="check" value="checked">
            <img class="logo_responsive" src="https://cdn4.iconfinder.com/data/icons/social-icon-4/842/facebook-512.png" alt="logo">
            <label class="checkbtn" for="check">
            <i class="fa fa-bars" style="background-color: white;"></i>
            </label>
            <header class="responsive-head">
                <nav>
                    <ul class="nav-responsive">
                        <li><a href="#">Link 1</a></li>
                        <li><a href="#">Link 1</a></li>
                        <li><a href="#">Link 2</a></li>
                        <li><a href="#">Link 3</a></li>
                    </ul>
                </nav>
            </header>
        </div>
```
<br>
<br>

<br>
Angel

```
        <div>
            <input type="checkbox" id="check-angel" value="checked">
            <img class="logo_responsive" src="https://cdn4.iconfinder.com/data/icons/social-icon-4/842/facebook-512.png" alt="logo">
            <label class="checkbtn" for="check-angel">
            <i class="fa fa-bars"></i>
            </label>
            <header class="responsive-head-angel">
                <nav>
                    <ul class="nav-responsive">
                        <li><a href="#">Link 1</a></li>
                        <li><a href="#">Link 1</a></li>
                        <li><a href="#">Link 2</a></li>
                        <li><a href="#">Link 3</a></li>
                    </ul>
                </nav>
            </header>
        </div>
```
<br>


<br>
<p align="center"><img src="https://github.com/ScorchingShade/Pinch/blob/master/img/pinch_responsive_nav_dracula.jpg"></p>
<br>
<br>
<p align="center"><img src="https://github.com/ScorchingShade/Pinch/blob/master/img/pinch_responsive_nav_angel.jpg"></p>
<br>



## The Angel and Dracula Elements - Footer
A good footer contains all the necessary contact info, social media links, and often a message form. PinchX provides you with a complete template to create a **comprehensive footer from scratch.**

```
    <div class="footer__change-theme">
        <h1 class="footer__change-title">Footer</h1>
        <p class="footer__change-text">Simple and elegant with themes that match your Navbar!</p>
        <button class="footer__change-btn">Change Theme of Footer</button>
    </div>
    <footer class="footer">
        <div class="footer__container">

        </div>
        <div class="footer__container">
            <div class="footer__items">
                <div class="footer__item footer__item-about">
                    <h2 class="footer__item-title"><span class="footer__item-subtitle">Pinch</span>Footer</h2>
                    <p class="footer__item-text">
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum ut semper magna, in iaculis arcu. Nunc mollis metus nibh, vel egestas ligula facilisis vehicula.
                    </p>
                    <ul class="footer__list">
                        <li><a class="footer_list-link" href="tel:123-456-789"><i class="fas fa-phone"></i> 123-456-789</a></li>
                        <li><a class="footer_list-link" href="mailto:ankushors789@gmail.com"><i class="fas fa-envelope"></i> ankushors789@gmail.com</a></li>
                        <li class="footer_list-link">
                            <ul class="footer__list footer__sublist">
                                <li><a class="footer__sublist-link" href="#"><i class="fab fa-facebook"></i></a></li>
                                <li><a class="footer__sublist-link" href="#"><i class="fab fa-instagram"></i></a></li>
                                <li><a class="footer__sublist-link" href="#"><i class="fab fa-twitter"></i></a></li>
                                <li><a class="footer__sublist-link" href="#"><i class="fab fa-youtube"></i></a></li>
                            </ul>
                        </li>
                    </ul>
                </div>
                <div class="footer__item footer__item-links">
                    <h2 class="footer__item-title">Quick Links</h2>
                    <ul class="footer__item-list">
                        <li><a class="footer__item-link" href="#">Events</a></li>
                        <li><a class="footer__item-link" href="#">Team</a></li>
                        <li><a class="footer__item-link" href="#">Mentors</a></li>
                        <li><a class="footer__item-link" href="#">Gallery</a></li>
                        <li><a class="footer__item-link" href="#">Terms</a></li>
                    </ul>
                </div>
                <div class="footer__item footer__item-contact">
                    <h2 class="footer__item-title">Contact us</h2>
                    <form class="footer__item-form" action="index.html" method="post">
                        <input class="footer__item-form-email" type="email" name="email" placeholder="Your Email Address....">
                        <textarea class="footer__item-form-msg" name="message" placeholder="Your Message...."></textarea>
                        <button class="footer__item-form-submit" type="submit"><i class="fas fa-envelope"></i> Send</button>
                    </form>
                </div>
            </div>
        </div>
        </div>
        <div class="footer__container footer__copy">
            <p>powered by <a href="https://github.com/ScorchingShade/Pinch">ScorchingShade</a></p>
        </div>
    </footer>
```


Understanding the **footer** elements

The theme of the footer can be switched using the **Change Theme of Footer** button. The code for the button is `<button class="footer__change-btn">`.<br>
The footer contains 3 columns, contained inside `<div class="footer__items">`:
    - <div class="footer__item footer__item-about"> contains contact info and social media links
    - <div class="footer__item footer__item-links"> contains the website's quick links
    - <div class="footer__item footer__item-contact"> contains the contact form

<br>
<br>

**About section**
```
                <div class="footer__item footer__item-about">
                    <h2 class="footer__item-title"><span class="footer__item-subtitle">Pinch</span>Footer</h2>
                    <p class="footer__item-text">
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum ut semper magna, in iaculis arcu. Nunc mollis metus nibh, vel egestas ligula facilisis vehicula.
                    </p>
                    <ul class="footer__list">
                        <li><a class="footer_list-link" href="tel:123-456-789"><i class="fas fa-phone"></i> 123-456-789</a></li>
                        <li><a class="footer_list-link" href="mailto:ankushors789@gmail.com"><i class="fas fa-envelope"></i> ankushors789@gmail.com</a></li>
                        <li class="footer_list-link">
                            <ul class="footer__list footer__sublist">
                                <li><a class="footer__sublist-link" href="#"><i class="fab fa-facebook"></i></a></li>
                                <li><a class="footer__sublist-link" href="#"><i class="fab fa-instagram"></i></a></li>
                                <li><a class="footer__sublist-link" href="#"><i class="fab fa-twitter"></i></a></li>
                                <li><a class="footer__sublist-link" href="#"><i class="fab fa-youtube"></i></a></li>
                            </ul>
                        </li>
                    </ul>
                </div>
```
<br>
The **About** section is defined by the class ```footer__item-about```.
The paragraph element with the class `footer__item-text` contains the website description.
The unordered list with the class `footer__list` contains the phone number and email info both defined by the `footer_list-link` classes.
The unordered list with the class `footer__sublist` is nested inside the previous list, and contains the links for Facebook, Instagram, Twitter, and YouTube. Each item has a class of `footer__sublist-link`.

**Quick Links section**
```
                <div class="footer__item footer__item-links">
                    <h2 class="footer__item-title">Quick Links</h2>
                    <ul class="footer__item-list">
                        <li><a class="footer__item-link" href="#">Events</a></li>
                        <li><a class="footer__item-link" href="#">Team</a></li>
                        <li><a class="footer__item-link" href="#">Mentors</a></li>
                        <li><a class="footer__item-link" href="#">Gallery</a></li>
                        <li><a class="footer__item-link" href="#">Terms</a></li>
                    </ul>
                </div>
```
<br>
The **Quick Links** section is contained inside the `footer__item-links` class. Add or remove the `<li class="footer__item-link">` items as you see fit!
<br>

**Contact Form section**
This section is aligned to the right and provides a simple form to send a message to the author/developer.<br>
<br>
```
                <div class="footer__item footer__item-contact">
                    <h2 class="footer__item-title">Contact us</h2>
                    <form class="footer__item-form" action="index.html" method="post">
                        <input class="footer__item-form-email" type="email" name="email" placeholder="Your Email Address....">
                        <textarea class="footer__item-form-msg" name="message" placeholder="Your Message...."></textarea>
                        <button class="footer__item-form-submit" type="submit"><i class="fas fa-envelope"></i> Send</button>
                    </form>
                </div>
```

Note that all 3 columns are defined by `footer_item` class.
The footer is fully responsive, and the 3 footer elements collapse into mobile-friendly columns when viewed from a mobile device.
<br>
<p align="center"><img src="https://github.com/ScorchingShade/Pinch/blob/master/img/pinch_dracula_footer.jpg"></p>
<br>
<br>
<br>
<p align="center"><img src="https://github.com/ScorchingShade/Pinch/blob/master/img/pinch_angel_footer.jpg"></p>
<br>
<br>

## Futuristic Typography, a new way to write
There are 5 different classes providing you a great new way to define your text! Simple and futuristic, the typography is sure to give a pleasing appeal to your page!
<br>
<br>
```
        <p class="disp-xl">Extra Large Text Display</p>
        <p class="disp-lg">Large Text Display</p>
        <p class="disp-md">Medium Text Display</p>
        <p class="disp-sm">Small Text Display</p>
        <p class="disp-xs">Extra Small Text Display</p>
```
The classes are "disp-xl", "dis-lg", "disp-md", "disp-sm" and "disp-xs" which give enough options to diplay different kinds of text!<br>
<br>
<p align="center"><img src="https://github.com/ScorchingShade/Pinch/blob/master/img/pinch_typography.jpg"></p>
<br>

## Author
<h1 align="center">Hi 👋, I'm Ankush</h1>
<h3 align="center">A geek , a coder, a boxer, an explorer</h3>

- 🔭 I’m currently working on [PinchX framework](https://github.com/ScorchingShade/Pinch)

- 👯 I’m looking to collaborate on [React](https://github.com/facebook/react)

- 🤔 I’m looking for help with [Pinch framework](https://github.com/ScorchingShade/Pinch)

- 👨‍💻 All of my projects are available at [https://github.com/ScorchingShade](https://github.com/ScorchingShade)

- 📝 I regulary write articles on [https://medium.com/@ankushsharma_70830](https://medium.com/@ankushsharma_70830)

- 💬 Ask me about **React, angular, java, springboot, restapi**

- 📫 How to reach me - **ankushors789@gmail.com**

- ⚡ Fun fact **I am a burger connoisseur, having eaten 125 different kinds of burgers!**


<p align="center">
<a href="https://linkedin.com/in/ankush-sharma-a9b24a37" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/linkedin.svg" alt="ankush-sharma-a9b24a37" height="20" width="20" /></a>
<a href="https://fb.com/kushuas" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/facebook.svg" alt="kushuas" height="20" width="20" /></a>
<a href="https://instagram.com/the_sitting_traveller" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/instagram.svg" alt="the_sitting_traveller" height="20" width="20" /></a>
<a href="https://medium.com/@ankushsharma_70830" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/medium.svg" alt="@ankushsharma_70830" height="20" width="20" /></a>
</p>



## License
```
Copyright (C) 2020 Ankush Sharma @ AINC, creating code

This program is free software: you can redistribute it and/or modify
it under the terms of the MIT License as it is published.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
MIT License for more details.

You should have received a copy of the Mit License
along with this program.  
```

<br>


## Shout-out
A Huge shout out to Kevin Powell for all his amazing SCSS tutorials. Do check him out on YouTube!
