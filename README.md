<p align="center"><img width=12.5% src="https://github.com/ScorchingShade/Pinch/blob/master/img/pinch_logo.png"></p>


<p align ="center"> A Minimalistic css Library for quickly bootstrapping your project</p>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![Python](https://img.shields.io/badge/python-v3.6+-blue.svg)
[![GitHub Issues](https://img.shields.io/github/issues/ScorchingShade/Pinch.svg)](https://github.com/ScorchingShade/Pinch/issues)
![Contributions welcome](https://img.shields.io/badge/contributions-welcome-orange.svg)

## Basic Overview - Version 0.01
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
<br>
The theme of the footer can be controlled using the class "footer-angel" or "footer-dracula".<br>
The footer has two main areas. **The Bottom area** and **The Content Area**.<br>
You would want to start off by defining these simply using the classes "footer-bottom" and "footer-content" in two separate divs.<br>
The bottom area can simply include links, copyright info etc for the developer/author.<br>
The content area is where everything else goes. For a basic design, you can leave this as is specifying some footer text.<br>
<br>

The content area is further divided into three horizontal grids of different classes and types of data.
- Section about
- Section links
- Section contact form
<br>
<br>

**Section about** - This section contains info like social links, email, contact info, description, title etc. You can use classes as shown in the example above to set these.The About section is aligned to the left and is perfect to showcase import links for contact.<br>
```
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
```
<br>
The class "about" with class "footer-section" creates the about section. Use the above shown h1 tag styling to generate a cool Title for footer in about.<br>
The class "contact" with class "footer-section" creates a styling for your fab-icon spans of contact and email as shown.<br>
The class "socials" allows you to set engaging icons using font-awesome.<br><br>


**Section links** -
As the name suggests this section is all about providing important links to your website! <br>
```
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
```
<br>
The class "links" along with class "footer-section" takes care of all your links. That's it! Its all you need! Use it as shown in the example above!<br>
<br>

**Section contact form** -
This section is aligned to the extreme right and provides a simple form to send a message to the author/developer.<br>
<br>
```
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
```
The key classes to note here are "contact-form", "contact-input" and "text-input".<br>
These when used in a form like the given example can help you create the perfect dynamic form for your footer!<br><br>
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
<p align="center"><img src="https://github.com/ScorchingShade/Pinch/blob/master/img/pinch_angel_typography.jpg"></p>
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

- 📫 How to reach me **ankushors789@gmail.com**

- ⚡ Fun fact **I am burger connoisseur, having eaten 125 different kinds of burgers!**


<p align="center">
<a href="https://linkedin.com/in/ankush-sharma-a9b24a37" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/linkedin.svg" alt="ankush-sharma-a9b24a37" height="20" width="20" /></a>
<a href="https://fb.com/kushuas" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/facebook.svg" alt="kushuas" height="20" width="20" /></a>
<a href="https://instagram.com/the_sitting_traveller" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/instagram.svg" alt="the_sitting_traveller" height="20" width="20" /></a>
<a href="https://medium.com/@ankushsharma_70830" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/medium.svg" alt="@ankushsharma_70830" height="20" width="20" /></a>
</p>



## License
```
Copyright (C) 2020 Ankush Sharma @ AINC

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
