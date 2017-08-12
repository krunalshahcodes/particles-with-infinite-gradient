# Particles Background With Infinite Gradient Effect

[![license](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/imkrunal/particles-with-infinite-gradient/LICENSE.md)

## Change Gradient Color

Edit particles-js ID in assets/css/style.css

```
#particles-js {
    width: 100%;
    height: 100%;
    background-color: #c91d61;
    background: linear-gradient(270deg, #01acde, #c5d201, #f59a00, #e30613, #c91d61);
    background-size: 1000% 1000% !important;
    -webkit-animation: changeColors 30s ease infinite;
    -moz-animation: changeColors 30s ease infinite;
    -o-animation: changeColors 30s ease infinite;
    animation: changeColors 30s ease infinite;
    display: block;
}

@-webkit-keyframes changeColors {
    0% {
        background-position: 0 50%;
    }
    50% {
        background-position: 100% 50%;
    }
    100% {
        background-position: 0 50%;
    }
}


```

## Built With

* [Particles.JS](https://github.com/VincentGarreau/particles.js/) - A lightweight JavaScript library for creating particles