# Project 1 Writeup

## What was the most challenging part of this assignment? Did you find HTML and CSS easy or difficult to work with?
The most challenging part was creating interaction while staying completely within HTML and CSS. The crossword needed to support typing, keyboard navigation, touch interaction, and a solution reveal without JavaScript, so I had to rely on native browser behavior and semantic elements rather than scripting. I found the basic HTML straightforward, while CSS became more challenging when I started balancing responsive layout, accessibility, and consistent visual design at the same time.

## How did you build the puzzle grid, and what other options did you consider?
I built the puzzle with CSS Grid and used one-character text inputs for the playable squares. Each input has an accessible name that describes its row, column, and relevant clue, and blocked cells are represented as non-input grid cells with a visually distinct dark background. I considered a CSS checkbox toggle for revealing the answer, but chose the native `details` and `summary` elements because they already support keyboard and touch interaction without extra tricks.

## What did you take into account when designing the site? Is there anything you are particularly proud of?
I started with a small design system: a neutral background and text ramp, one blue accent, a consistent spacing scale, and reusable custom properties. I also limited body text width, used whitespace to group related information, and made the navigation adapt from a sticky desktop header to a fixed bottom navigation on small screens. I am particularly proud that the design remains simple while accessibility features such as skip links, visible focus states, semantic landmarks, and 44-pixel minimum interactive targets are integrated into the visual system.

## Given more time or resources, what would you add?
With more time, I would write a more original mini crossword with a larger set of conventional English clues and create additional visual assets for the arcade. I would also do more usability testing with screen readers and multiple mobile devices rather than relying only on browser emulation and automated checks. As later course projects allow JavaScript and Svelte, I would add richer game feedback while preserving the accessible structure established here.

## How many hours did you spend on this assignment?
I spent approximately **[REPLACE WITH YOUR ACTUAL HOURS] hours** planning, implementing, testing, and refining the project.

## Optional assumptions
I assumed that clean directory URLs such as `/game/`, `/about/`, and `/contact/` satisfy the requested page organization when deployed as folders containing `index.html`. I also assumed that the solution reveal could use the native `details` element, as suggested in the assignment. I treated mobile usability and keyboard accessibility as requirements across every page rather than only on the puzzle page.

## Sources, external code/design, and AI disclosure
I used an AI assistant to help plan, draft, and review portions of the HTML, CSS, puzzle content, and writeup for this assignment. The site does not import any JavaScript or CSS framework; all project styling is contained in the repository. The arcade logo is an original inline SVG asset created for this project, and the puzzle uses the historic Sator Square word pattern as its source material. I reviewed the generated work against the assignment requirements and am responsible for the submitted result.
