# Dr Gopikrishnan Palanivel — Professional Profile

Interactive professional website for **Dr Gopikrishnan Palanivel**, M.B.B.S., M.D. (Anaesthesiology),
M.B.A. (Healthcare & Hospital Management) — Specialist Anaesthesiologist & Intensivist, Chennai, India.

## Live site

**<https://gopitherobot.github.io/dr-gopikrishnan-palanivel/>**

## Contents

- Profile, practice history and postings (filterable, expandable timeline)
- Clinical scope — anaesthesia, critical care, procedures, teaching
- Education & training
- MBA in Healthcare & Hospital Management, with full curriculum and grades
- Leadership, councils & community roles
- Research & scholarship
- Certification & registration
- Credential gallery with full-size viewer
- Contact

## Structure

```
index.html        complete site — HTML, CSS and JS in one file, no build step
*.jpg             portrait and credential scans, referenced by plain filename
```

## Editing

No frameworks, no dependencies, no build step. Edit `index.html` and commit — Pages
redeploys within a minute or two.

To preview locally:

```
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Notes

- Typefaces load from Google Fonts (Archivo, Source Serif 4, IBM Plex Mono).
- Light and dark themes are both supported, with a manual toggle; the page follows the
  visitor's system setting by default.
- Printing the page (⌘P) expands every collapsed entry and produces a clean CV.
- Sensitive identifiers on the scanned documents — residential address, Academic Bank of
  Credits ID, and the DHA verification PIN, barcode and QR — have been masked.
