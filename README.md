# OPAN 3257 — Databases for Business

Companion site and hands-on materials for **OPAN 3257: Develop/Managing Data Bases**
(McDonough School of Business, Georgetown University, Fall 2026), taught by
Prof. Emisa Nategh.

This repo hosts a lightweight static site (GitHub Pages) for students to get
hands-on with SQL before the semester starts and throughout the course. It is
a **companion** to Canvas, not a replacement — official assignments, due
dates, and grading always live on Canvas.

## Site structure

- `index.html` — course overview and instructor info
- `topics.html` — walkthrough of the module arc with SQL examples
- `practice.html` — live, in-browser SQL sandbox (SQLite via [sql.js](https://sql.js.org/)) plus practice exercises
- `assignments.html` — non-graded previews/hints for Assignments 1–5, mini-challenges, and the semester project tracks
- `advanced.html` — enrichment material for students who want to go further
- `css/style.css` — Georgetown-branded styling (Georgetown Blue / Georgetown Gray)
- `OPAN 3257-Syllabus-Prof Nategh-F26.pdf` — the official course syllabus

## Running locally

No build step — it's plain HTML/CSS/JS. Serve the folder with any static
server, e.g.:

```
python3 -m http.server 8000
```

then open `http://localhost:8000`.

## Deploying

Hosted via **GitHub Pages**. In this repo's Settings → Pages, set the source
to the `main` branch, root folder.
