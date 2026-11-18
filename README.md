# μLearn Redesign

A creative redesign concept for the [μLearn](https://app.mulearn.org/) platform, made as a college web design task. μLearn is a community-driven learning platform where students learn, build and grow together. This redesign gives it a bolder, friendlier look and puts **karma** at the centre of the experience.

**Live demo:** _add your GitHub Pages link here_

## Why redesign it?

The original app opens straight into a dashboard, which can feel heavy for new visitors. This concept tries to:

- Explain what μLearn is in the first few seconds
- Give new users a clear first step (pick an interest group, finish a task)
- Make karma points feel rewarding instead of just a number
- Give the platform a stronger visual identity

## Features

- **Interactive karma card:** click the tasks to earn karma and watch the points, progress bar and level update
- **Interest groups:** switch between Web development, UI/UX design, AI & ML, Cybersecurity and Mobile apps to see a learning path for each
- **Leaderboards:** top learners and top campuses
- **Events:** upcoming hackathons, workshops and meetups
- **Dark mode** toggle, which also follows your system setting
- **Responsive layout** for phones, tablets and desktops
- Respects reduced-motion settings and has visible keyboard focus

## Design choices

| Element | Choice |
| --- | --- |
| Colours | Deep indigo `#16143f`, electric blue `#3d5afe`, sunny yellow `#ffd23f`, coral `#ff6b57`, mint `#2fcf8f`, soft lavender background `#f4f2ff` |
| Fonts | Bricolage Grotesque for headings, DM Sans for body text |
| Style | Thick outlines and offset shadows for a playful, confident feel |
| Idea | Karma is the star: the hero is a playable karma card, not a static image |

## Tech stack

- HTML
- CSS (custom properties for theming, grid and flexbox for layout)
- Vanilla JavaScript (no frameworks or build step)

## Run it locally

1. Download or clone this repository
2. Open `index.html` in any browser

Or, in VS Code, install the **Live Server** extension, right-click `index.html` and choose **Open with Live Server**.

## Project structure

```
mulearn-redesign/
├── index.html   # the whole redesign: markup, styles and script
└── README.md
```

## Note on content

The live μLearn app loads its content dynamically, so the names, numbers, events and leaderboard entries here are **sample data** made up to show the design. This is a design concept, not the official μLearn website.

## Author

Made by **Amna**, 2nd-year B.Tech CSE student.

## Acknowledgements

- [μLearn](https://mulearn.org/) for the platform and the idea of learning together
- Fonts from [Google Fonts](https://fonts.google.com/)
