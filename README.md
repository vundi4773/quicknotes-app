# Notes App

A small notes app built with plain HTML, CSS and JavaScript. You can write short notes, sort them into categories, search through them and delete the ones you no longer need. Your notes are saved in the browser, so they are still there after a refresh.

## Features

- Add a note with a category (Personal, Work or Study)
- Each note shows its text, category label, date and time, and a Delete button
- Validation: empty notes and notes over 200 characters show an error message
- Delete any note with its own Delete button
- Live search that ignores upper and lower case
- Note count message for zero, one and many notes
- Notes saved with `localStorage` and loaded when the page opens
- Responsive layout that stacks the form on screens 600px wide or smaller

## How to run locally

1. Clone the repository: `git clone <your-repository-url>`
2. Open the project folder.
3. Double-click `index.html` to open it in a browser (no build step or server needed).

## What I learned

- How to build a page with semantic HTML tags and link each `<label>` to its input with `for` and `id`.
- How to use Flexbox for the form and a `@media (max-width: 600px)` rule to change the layout on small screens.
- How to rebuild a list from an array with `createElement` and `textContent`, which keeps user text safe from HTML injection.
- How to save and load data with `localStorage`, `JSON.stringify` and `JSON.parse`.
- How to make small, clear Git commits for each step of a project.
