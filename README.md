# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

##### Desktop

![The desktop screenshot](./images/desktop-screenshot.png)

##### Mobile

![The mobile screenshot](./images/mobile-screenshot.png)

### Links

- Live Site URL: [Here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- Vanilla CSS

### What I learned

```
/* Styling nft image */
.nft-img {
	width: 17rem;
	height: 17rem;
	background: url("./images/image-equilibrium.jpg");
	background-size: 100%;
	border-radius: 7px;

	display: flex;
	align-items: center;
	justify-content: center;
}

.nft-img-inner {
	display: none;
	background-color: rgba(0, 255, 247, 0.5);

	width: 100%;
	height: 100%;
	border-radius: 7px;
}

.nft-img:hover .nft-img-inner {
	display: flex;
	justify-content: center;
	align-items: center;
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

Hi, I'm igafshell, just a dude trying to learn how to code

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/igafshell)
- Github - [igafshell](https://github.com/igafshell)

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
