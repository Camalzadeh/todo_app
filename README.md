# To-Do App

A to-do list built with nothing but HTML, CSS and vanilla JavaScript - no framework,
no build step, nothing to install. Buta internship task.

## What it does

- Add, complete and delete tasks.
- Three colour themes, switched from the header.
- Tasks and the chosen theme are kept in `localStorage`, so a reload restores both.
- A live clock and date in the header.
- A layout that works on a phone.

## Running it

There is no build step. Serve the folder:

```bash
python -m http.server 8000     # then open http://localhost:8000
```

Or open `index.html` in a browser directly.

## Layout

- `index.html` - the markup.
- `CSS/main.css` - layout and the three themes.
- `JS/main.js` - task handling and `localStorage`.
- `JS/time.js` - the clock.
