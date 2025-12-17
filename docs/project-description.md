# TEST-PROJECT (Static Site)
A tiny static site built with plain HTML + CSS.

## Structure
site/
index.html
faq.html
contact.html
styles.css

## Run locally (Node)
From the repo root: npx serve site -l 8000
Open: http://localhost:8000/

## Run locally (Python)
If you have Python 3 installed: python3 -m http.server 8000
Open: http://localhost:8000/site/

## Notes
Styling is shared via site/styles.css.
Navigation highlights the current page automatically (a JavaScript snippet is included in each HTML file).
