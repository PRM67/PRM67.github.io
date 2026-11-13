# PRM67.github.io
Paige Merkley Speeches: a simple site of Paige's talks, hosted on GitHub Pages.

## Layout
- `index.html`: home page with the list of talks (newest first)
- `talks/`: one page per talk
- `audio/`: recordings (`.m4a`)
- `images/paige.jpg`: speaker photo (until it's added, a "PM" badge shows instead)
- `css/style.css`: all styling

## Adding a talk
1. Copy an existing page in `talks/` to `talks/YYYY-MM-DD-short-title.html`. Pick one with audio if the new talk has a recording.
2. Change the title, date, topic line, audio file name and length, and the talk text.
3. Put the recording in `audio/` with the same `YYYY-MM-DD-short-title` name.
4. In `index.html`, copy one `<li class="talk-card">` block, put it in date order, and update its link, date, title and badges.

Look for `TODO` comments in the talk pages for details that still need filling in.
