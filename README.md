# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview
![Overview](./images/Screenshot%202pc.png)

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![screenshot](./images/Screenshot%201mobile.png)


### Links

- Solution URL: [Add solution URL here](https://www.frontendmentor.io/solutions/order-summary-component-Hkmu0xvX9)
- Live Site URL: [Add live site URL here](https://order-sum.vercel.app/)

### Built with

- Semantic HTML5 markup
- CSS custom properties


### What I learned

-Selectors are pretty important, it makes your work simple and easy wwhen applying the css custom properties and many more

some of my fav code that got me pumped as a beginner,
see below:

```html
 
    <div class="sections">
      <h1 >Order Summary</h1>
    
    <section class="article">
        <p>You can now listen to millions of songs,
      audiobooks and podcasts on any device anywhere you like!</p>
    </section>

    <section class="price-container">
      <div id="icon">
        <img src="./images/icon-music.svg" alt="music">
        </div>

        <div class="column">
        <h2 class="plan">Annual Plan</h2>
        <p class="price">$59.99/year</p>
        </div>
        
        <a href="#" class="change">Change</a>
    </section>

```
```css

@media screen and (max-width:600px) {
    body{
        background: url("./images/pattern-background-mobile.svg");
        background-repeat: no-repeat;
        margin: 90px;
        background-size: contain;
        background-color: rgba(173, 166, 255, 0.2);
        
    }
    .main-container{
        width: 100%;
        border: transparent;
    border-radius: 20px;
    text-align: center;
    background-color: white;
    }
    .sections{
 
```


### Continued development
I would like to focus on the variouse aspects of CSS properties and refine my skill set in further projects.

### Useful resources

- [Css-tricks](https://www.css-tricks.com) - This helped me understand variouse challenges on CSS at whole. I really liked the variouse ways they implement, makesit easier to understand and 0f course i will use it going forward.
- [freecodecampe](https://www.freecodecamp.com) - This is an amazing site which helped me finally understand some basic html and css. I'd recommend it to anyone still learning or a newbie in Web-development.

## Author

- Github - [RoyalYum](https://github.com/RoyalYum)
- Frontend Mentor - [@RoyalYum](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@9aul_umeh](https://www.twitter.com/9aul_umeh)

## Acknowledgments

I would love to  give a hat tip to @codehouze  who introduced me to this program to help me hone my learning skill on programming and web-development and this project too. Thank You So Much.
