# Project 1 Writeup

## What was the most challenging part of this assignment? Did you find HTML and CSS easy or difficult to work with?

The most challenging part for me was building the crossword game without using JavaScript. I needed to make sure users could type in the boxes, use the keyboard, and reveal the answer with only HTML and CSS. HTML was not very difficult for me, but CSS was more challenging because I needed to make the website look good on both desktop and mobile.

## How did you build the puzzle grid, and what other options did you consider?

I used CSS Grid to build the 5 by 5 crossword puzzle. For the squares that users can type in, I used input elements with a maximum length of one character. At first, I thought about using a checkbox to show the solution, but I decided to use the `details` and `summary` elements because they are simple and can work without JavaScript.

## What did you take into account when designing the site? Is there anything you are particularly proud of?

When I designed the website, I wanted it to be simple, clean, and easy to use. I used blue as the main color and tried to keep the same spacing, buttons, navigation, and style on all four pages. I am especially proud of the mobile version because the navigation moves to the bottom of the screen and the crossword can still be used on a small screen.

## Given more time or resources, what would you add?

If I had more time, I would add more crossword puzzles and make the game more interesting. I would also test the website on more phones and with more accessibility tools. In future projects, when JavaScript or Svelte is allowed, I would like to add features such as checking answers, scores, and better game feedback.

## How many hours did you spend on this assignment?

I spent approximately **10 hours** working on this assignment.

## Optional assumptions

I assumed that using folders with `index.html` files for `/game/`, `/about/`, and `/contact/` was acceptable for the page organization. I also assumed that using the native `details` element was acceptable for showing the puzzle solution. I tried to make all four pages work well on both desktop and mobile.

## Sources, external code/design, and AI disclosure

I used an AI assistant to help me with some parts of planning, writing, and reviewing the HTML, CSS, puzzle content, and writeup. I reviewed and tested the code before submitting the project. I did not use any JavaScript or CSS framework. The arcade logo is an SVG made for this project, and the crossword is based on the Sator Square word pattern.
