# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./images/screenshot.jpg)


### Links

- Solution URL: (https://github.com/Nikkaburger/3-column-preview-card-component)
- Live Site URL: (https://stunning-clafoutis-38a1fe.netlify.app/)

## My process

Responsive design using mobile first  workflow, HTML and CSS

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Creating a 3 card component preview.

```html
<body>
    <div class="container">
        <div class="card1">
            <img src="images/icon-sedans.svg" alt="sedans">
            <h1>
                SEDANS
            </h1>
            <p>
                Choose a sedan for its affordability and excellent fuel economy. Ideal for cruising in the city or on your next road trip.
            </p>
            <button class="botton1">Learn More</button>
        </div>
        <div class="card2">
            <img src="images/icon-suvs.svg" alt="sedans">
            <h1>
                SUVS
            </h1>
            <p>
                Take an SUV for its spacious interior, power, and versatility. Perfect for your next family vacation and off-road adventures.
            </p>
            <button class="botton2">Learn More</button>
        </div>
        <div class="card3">
            <img src="images/icon-luxury.svg" alt="sedans">
            <h1>
                LUXURY
            </h1>
            <p>
                Cruise in the best car brands without the bloated prices. Emjoy the enhanced comfort of a luxury rental and arrive in style.
            </p>
            <button class="botton3">Learn More</button>
        </div>
    </div>
</body>
```
```css
body {
    width: 375px;
    overflow-x: hidden;
}

.container {
    border-radius: 10px;
    height: auto;
    width: 255px;
    margin: 60px 20px;
    display: flex;
    flex-direction: column;
}

.card1 {
    background-color: hsl(31, 77%, 52%);
    width: 100%;
    padding: 40px;
    border-top-left-radius: 10px;
    border-top-right-radius: 10px;
    border-bottom-left-radius: 0px;
}

.card2 {
    background-color: hsl(184, 100%, 22%);
    width: 100%;
    padding: 40px;
}


.card3 {
    background-color: hsl(179, 100%, 13%);
    width: 100%;
    padding: 40px;
    border-bottom-left-radius: 10px;
    border-bottom-right-radius: 10px;
    border-top-right-radius: 0px;
}

p {
    font-size: 16px;
    margin-bottom: 30px;
}
}
```

### Continued development

My focus is on mastering modern web design techniques through continuous learning, experimentation, and a willingness to adapt to the ever-changing web landscape. 
By focusing on responsive design using, HTML5, CSS3, JavaScript, and PHP, to be adequately equipped to create visually stunning and user-friendly websites. Embrace new technologies, stay curious, and push the boundaries of my creativity to unlock endless possibilities in the world of web development. 


### Useful resources

- [#CSSMediaQuery](https://courses.webdevsimplified.com) - This helped me to understand and fix media query for the mobile version of my design, the tutorial was direct and explanatory. I really liked this pattern and will use it going forward.
- [#HTMLFullCourseforBeginners](https://courses.davegray.codes/) - This is an amazing course which helped me finally understand the functionality of #HTML5 tags. I'd recommend it to anyone still learning this concept.
-[#CSSTutorialFullCourseforBeginners](https://courses.davegray.codes/) - This is an amazing course which helped me finally understand CSS tags, syntax and their functionalities. I'd recommend it to anyone still learning this concept.

## Author

- Website - [Oluwaseun Akeju](https://www.fluxverge.com)
- Frontend Mentor - [@nikkaburger](https://www.frontendmentor.io/profile/nikkaburger)
- Twitter - [@fluxverge](https://www.twitter.com/fluxverge)

## Acknowledgments

Special thanks to Almighty God for the completion of this task, my profound gratitude to Dave Gray, Omolade Sunday, Akinola Akeem and Webdevsimplified for their immense contributions.
