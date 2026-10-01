<div align="center">

<a href="https://github.com/your-username/age-calculator">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=1F7A5C&center=true&vCenter=true&width=520&lines=Age+Calculator;Years%2C+months+and+days;Next+birthday+countdown;One+file.+No+dependencies." alt="Age Calculator animated title">
</a>

<br>

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-1F7A5C?style=for-the-badge)

</div>

---

## About

A small, fast age calculator that runs entirely in the browser. Enter a date of birth and see your exact age, with the result animating in.

## Features

- Exact age in **years, months and days**
- Totals in months, weeks, days and hours
- Weekday you were born
- Days until your next birthday
- Optional "age on" date to calculate for any day, not just today
- Light and dark mode that follows your system setting
- Responsive layout, keyboard friendly, respects reduced-motion settings
- Single HTML file with no libraries or build step

## Demo

<div align="center">

| Input | Output |
|---|---|
| Date of birth: `1995-06-15` | `31 years  3 months  16 days` |
| Age on: `2026-10-01` | Next birthday in `257 days` |

</div>

> Add a screen recording here: `![Demo](assets/demo.gif)`

## Getting started

```bash
git clone https://github.com/your-username/age-calculator.git
cd age-calculator
```

Then open `index.html` in any browser. No install needed.

### Host it for free

Push the repo to GitHub, then go to **Settings → Pages**, choose the `main` branch, and your app goes live at `https://your-username.github.io/age-calculator/`.

## How it works

1. Reads the two dates from the form.
2. Subtracts year, month and day, borrowing from the previous month when a value goes negative.
3. Converts the difference to total days, weeks and hours.
4. Finds the next occurrence of the birth date to count days until your birthday.

## Project structure

```
age-calculator/
├── index.html   # markup, styles and script
└── README.md
```

## Contributing

Pull requests are welcome. For larger changes, open an issue first to discuss what you'd like to change.

## License

Released under the [MIT License](LICENSE).

<div align="center">

Made with care. If this helped, give it a star.

</div>
