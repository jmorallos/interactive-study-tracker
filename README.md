# Interactive Study Tracker

A lightweight, mobile-first productivity app that helps students manage their study tasks — built entirely with vanilla HTML, CSS, and JavaScript.

---

## Features

- **Add / Remove Tasks** — Quickly add new study tasks and delete ones you no longer need.
- **Mark Complete / Incomplete** — Toggle any task between done and not-done with a single click.
- **Filter Tasks** — View tasks by status: *All*, *Active* (still to do), or *Done* (completed).
- **Persistent Storage** — Tasks are saved to `localStorage` so your list survives page refreshes.
- **Responsive UI** — Mobile-first design that looks great on phones, tablets, and desktops.

---

## Tech Stack

| Layer      | Technology                        |
|------------|-----------------------------------|
| Markup     | HTML5                             |
| Styling    | CSS3 — Flexbox & Grid             |
| Logic      | Vanilla JavaScript (ES6+)         |
| Persistence| Web Storage API (`localStorage`)  |

No frameworks. No build tools. No dependencies.

---

## Why This Project?

This app is a deliberate **learning project** aimed at solidifying core front-end fundamentals:

- **DOM Manipulation** — Creating, reading, updating, and deleting elements without any library.
- **Application State (without frameworks)** — Managing an in-memory array of tasks and keeping the UI in sync manually.
- **UI Structure** — Practicing semantic HTML and a clean CSS architecture (Flexbox for layout, Grid where appropriate).
- **Web Storage** — Persisting state across sessions using `localStorage`.

Starting simple and framework-free forces a deep understanding of the browser platform before moving on to tools like React or Vue.

---

## Getting Started

No installation required — it's plain HTML/CSS/JS.

1. Clone or download the repository:
   ```bash
   git clone https://github.com/jmorallos/interactive-study-tracker.git
   ```
2. Open `index.html` in your browser.

That's it!

---

## Project Structure

```
interactive-study-tracker/
├── index.html      # App markup
├── style.css       # Styles (mobile-first, Flexbox/Grid)
└── app.js          # App logic & localStorage handling
```

---

## License

Distributed under the [MIT License](LICENSE).
