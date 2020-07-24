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
PinchX provides two theme options - **Dracula** and **Angel**.<br>


