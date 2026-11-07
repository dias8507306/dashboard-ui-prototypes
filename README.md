# Dashboard UI Prototypes

Interactive, single-file HTML prototypes made while designing an internal marketing dashboard: three variants of a date navigator and a set of animated "daily motivation" cards for the team. Each file is self-contained (HTML + CSS + vanilla JS) and is meant to be opened in the browser and clicked through, so design decisions could be made on working UI rather than static mockups.

## Features
- **`date-picker-variants.html`** — three live variants of a day switcher for statistics (minimal glass bar, segmented buttons, floating pill with "Today / Yesterday" shortcuts): arrow navigation that stops at today and at the first day with data, a popover calendar, light and dark themes, hover / press feedback.
- **`motivation-cards/variants.html`** — four layouts for a daily progress card (progress ring, rocket trajectory, big quote, streak) sharing the same bottom block.
- **`motivation-cards/cards.html`** — the chosen "rocket + quote" direction in several visual styles with entrance animations (animated glass border, full gradient, "stories" night-sky format) and a replay button.

## Tech stack
Plain HTML5, CSS (custom properties, keyframe animations, `backdrop-filter`), vanilla JavaScript, inline SVG. Google Fonts. No build step.

## Project structure
```
date-picker-variants.html
motivation-cards/
  variants.html
  cards.html
```

## How to run (demo mode)
Open any `.html` file in a browser, or serve the folder: `python -m http.server 8000` → http://localhost:8000/date-picker-variants.html.

> All data in this repository is randomly generated; brand names are anonymized.

## Кратко (RU)

Интерактивные HTML-прототипы, сделанные при проектировании внутреннего маркетингового дашборда.
Три варианта выбора даты и анимированные карточки «мотивации дня» для команды.
Каждый файл самостоятельный: HTML + CSS + JavaScript, сборка не нужна — достаточно открыть в браузере.
