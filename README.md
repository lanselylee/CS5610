# Sudokool — Sudoku Mock Site (HTML + CSS)

- **Live site (GitHub Pages):** https://lanselylee.github.io/CS5610/
- **Repository:** https://github.com/lanselylee/CS5610
- **Collaborator:** [None] 

---

## Walkthrough Video (≤ 5 min)
- Video link: [paste your video URL here]

## Writeup

### 1) Most challenging parts & time
Organizing the multi-page folder structure and relative paths was the most error-prone part.
In addition, building a 9×9 Sudoku grid (81 inputs) without using JavaScript required a lot of patience — I had to copy and adjust many lines manually! 😄
Before this assignment, I had built a personal homepage using MUI for UI design, which made styling much easier.
However, this project does not allow using MUI or JavaScript, so I had to write all the layouts and styles by hand.
It was more time-consuming to handle spacing, alignment, and responsiveness manually, but it also helped me understand how HTML and CSS actually work behind those frameworks.
Overall, HTML and CSS themselves were not difficult, but ensuring semantic structure, consistent styling, and mobile responsiveness took some planning.
In total, this assignment took me about 30 hours to complete.

### 2) Mobile-friendly decisions
made the navigation bar stick to the top on desktop and move to the bottom on mobile using @media.
This helps save space on small screens.
I used clamp() to make text resize automatically and made buttons and clickable areas larger.
For the Sudoku grid, I used bigger minmax() cells on mobile so it’s easier to tap.
Overall, I used flex and grid to keep the layout simple and responsive.

### 3) Design choices & what I’m proud of
I used a warm color theme in the final version.
At first, I tried a dark blue tech style, but it didn’t feel relaxing when I looked at the page.
I think a game should make people feel happy, so I changed it to warm colors and added a cute little emoji — “Just do it 😄”.
Now the page feels more friendly and fun to play with, and that’s the part I’m happiest about.

### 4) What I’d add with more time
Real Sudoku logic (checking rules, candidate numbers, and highlighting same numbers / rows / boxes)

A working timer with pause, difficulty selection, and local save feature

Theme switch (light / dark mode)

A real high score board and simple form validation (still trying to keep it no-JS, or maybe add it in later projects)

### 5) Hours spent
- 30 hours


### 7) Sources / Credits
- Fonts: [Baloo 2](https://fonts.google.com/specimen/Baloo+2), [Noto Sans SC](https://fonts.google.com/noto/specimen/Noto+Sans+SC)
- Icons/Logo: from weibo
- No JavaScript / No CSS framework used (per assignment rules)
