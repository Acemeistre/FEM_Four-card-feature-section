# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
    - [Achievements](#achievements)
    - [Challenges](#challenges)
    - [Continued development](#continued-development)
  - [AI Collaboration](#ai-collaboration)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![Screenshot](./images/tablet-screenshot.jpg)

### Links

- Solution URL: [GitHub repo](https://github.com/Acemeistre/FEM_Four-card-feature-section/)
- Live Site URL: [Live site](https://acemeistre.github.io/FEM_SFour-card-feature-section/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

#### Achievements

- Using DevTools to discern why some things are working/not working is helping move away from AI use.
- Built the HTML structure with very little help, using a `<ul>` of `<li>` cards, since they're a list of parallel items.
- Used one `box-shadow` with two parts for the cards: an `inset` shadow for the coloured top strip, and a soft outer drop shadow.
- Rearranged the cards into the staggered 1-2-1 tablet and desktop layout using explicit grid placement.

#### Challenges

- The page background colour wasn't in the style guide, so I had to find it in Figma's selection colours.
- `order` did nothing on grid items with explicit row and column positions, because it only affects auto-placed items.
- Needed AI help to figure out how to set a custom property (`--accent`) on each `.card:nth-child()`, so the accent colour is applied once in the shared card rule.
- The card shadow's exact values (x, y, blur, spread and colour) was in Figma's effect styles, which took some time to figure out.

#### Continued development/help

- Get more comfortable with grid placement (rows and columns, `grid-template-rows` and auto-created rows) without looking it up.
- Keep reading values from Figma's Design panel and Dev Mode.

## AI Collaboration

- Tools used - Claude.
- Used for - debugging and brainstorming solutions.