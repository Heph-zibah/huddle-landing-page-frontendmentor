# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge
The challenge is to build out this landing page from the designs provided in the starter code.


Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)


### Links

- Solution URL: [Huddle Website Solution URL](frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0/hub/responsing-landing-page-for-huddle-using-html-and-css-HJ__gvxvq)
- Live Site URL: [Huddle Website Live site URL](https://huddle-site-frontendmentor.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox- CSS Grid
- Mobile-first workflow

### What I learned

I learned how to make HTML markup and avoid div soup.

```html
 <main class="main-area">

            <div class="image">
                <img src="img/illustration-mockups.svg" alt="illustration markup">
            </div>
            <div class="page-content">
                <h1>Build The Community Your Fans Will Love</h1>
                <p>Huddle re-imagines the way we build communities. You have a voice, but so does your audience. Create connections with your users as you engage in genuine discussion.</p>
                <button>Register</button>
            </div>
        </main>
```

I learned how to use background image with background color.
```css
body {
    font-family: 'Open Sans', sans-serif;
    font-weight: 400;
    font-size: 16px;
    line-height: 1.6;
    width: 100%;
    background: url("../img/bg-mobile.svg");
    background-repeat: no-repeat;
    background-size: contain;
    background-color: hsl(257, 40%, 49%);
    color: #fff;
}
```

### Continued development

I will sit with learning mobile responsiveness. Following @wellspr codes on github opened my eyes to mobile responsiveness.

### Useful resources

- [Example resource 1](https://github.com/wellspr/huddle-landing-page-with-single-introductory-section/blob/master/css/styles.css) - This helped me for Mobile responsiveness. I really liked this pattern and will use it going forward.



## Author
- Website - [Oluwatosin Abigail Ogundeji](https://medium.com/@oluwatosinhephzibah)
- Frontend Mentor - [@Heph-zibah](https://www.frontendmentor.io/profile/Heph-zibah)
- Twitter - [@undaunted_pen](https://www.twitter.com/undaunted_pen)


## Acknowledgments

I will love to thank @wellspr on github. Her detailed css markup made me understand what mobile responsiveness is and how to go about it.
