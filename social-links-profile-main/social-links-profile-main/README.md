# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![Screenshot]([social-links-profile-main/social-links-profile-main/Screenshots/SocialLinkScreenshot.png](https://github.com/JordanAMWedderburn/FrontendMentor-Social-Links-Profile/blob/12235b519f7235a1cff49ba097470ce46052b1a7/social-links-profile-main/social-links-profile-main/Screenshots/SocialLinkScreenshot.png))
<img width="1280" height="720" alt="SocialLinkScreenshot" src="https://github.com/user-attachments/assets/c0503ce7-c72b-4cda-9318-3eeda5bf42ca" />


### Links

- Live Site URL: (http://127.0.0.1:5500/social-links-profile-main/index.html)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow
- [Styled Components](https://styled-components.com/) - For styles

### What I learned

I learned about pseudo classes and pseudo elements. 

For classes, [:root] selects the document's root elements. It is commonly used for defining global CSS variables that can then be inherited and used throughout the document. This allows for centralized management of design tokens like colors, fonts, and spacing.

The below code establishes the colors, fonts, and sizes for the document:

```
:root {
    --clr-Green: hsl(75, 94%, 57%);
    
    --clr-White: hsl(0, 0%, 100%);
    --clr-Grey700: hsl(0, 0%, 20%);
    --clr-Grey800: hsl(0, 0%, 12%);
    --clr-Grey900: hsl(0, 0%, 8%);

    --ff: 'Inter', sans-serif;
    --fs-body: 14px;
    --fs-heading: 22px;
    --fw-400: 400;
    --fw-600: 600;
    --fw-700: 700;

}
```

For elements, [::before] and [::after] allow you to add stylistic or decorative content, such as icons, generated text, or visual elements, directly within the CSS right before or after the content respectively.

Additionally, the use of * being able to select all elements within the document is useful.

The below code is how the elements align properly regardless of the browser: 

```
*,
*::before,
*::after{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
```

### Continued development

Something that I want to learn more about is how to get the buttons to work. It was out of scope for this challenge but it is important to have things work in practice.

### Useful resources

- [W3schools](https://www.w3schools.com/) - This helped me with understanding what certain elements, class, and functions did in detail. I would just need to search a term and I would likely find it there.

- [Stack Overflow](https://stackoverflow.com/questions) - This website has a lot of users giving input and simplier explanations for why and how things work. I'd recommend it to anyone who has questions about coding.

## Author

- Frontend Mentor - [@JordanAMWedderburn](https://www.frontendmentor.io/profile/JordanAMWedderburn)

## Acknowledgments

Tutorial Video 1 - [Brown](https://youtu.be/av6JRW2lCWE?si=XHHojmwOrPYKPH1I)

Tutorial Video 2 - [Hayden Kerr](https://youtu.be/7rnFJ7aGPmc?si=Sy3I9caC9Qm3EQop)

I watched both videos as I went through building this program. I also tried to make my own changes to make it my own and understand how to create it in my own way.
