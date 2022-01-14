# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)

- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)

- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](/Users/brianrichardson/Downloads/nft-preview-card-component-main/nftScreenshot.png)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it.

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [Styled Components](https://fontawesome.com/) - For styles

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

This challenge was especially fun for me to attempt. I came out knowing a few more tricks and gaining a bit more confidence in my ability to complete a goal after setting out to do it. The crucial things I picked up while doing this challenge were the ":hover" feature in CSS, using max height and width on a flex element in order to maintain mobile first design, using mobile first design, and also taking advantage of flex box justify and align. In particular with the  ":hover" feature, I learned to use the image as the hover background and to over lay a gradient over top of that image, to simulate just the gradient alone covering the image. Also using the hover feature only on the text by wrapping the html in a span.  

To see how you can add code snippets, see below:

```html
<section class="crypto">
  <i class="fab fa-ethereum"></i>
  0.041ETH
</section>
<section class="days">
  <i class="fas fa-clock fa-xs"></i>
  3 days left
</section>
```
```css
.image:hover{
  background-image: linear-gradient(to bottom, rgba(245, 246, 252, 0.0), rgba(112, 245, 256, 0.5)), url(../images/image-equilibrium.jpg);
  background-repeat: no-repeat;
  background-size: contain;
  background-position: center;
  transition-duration: 5000ms;
}
```
### Continued development

In future projects, I'd like to begin implementing the Javascript that I've started to learn. I was able to use the ":hover" function in CSS effectively for this challenge, and I'm proud of that. Also, for my continued development, will be using flex grid as well as flex box.  

## Author

- Twitter - [@Brich804](https://www.twitter.com/brich804)
