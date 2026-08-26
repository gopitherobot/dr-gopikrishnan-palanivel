# Dr Gopikrishnan Palanivel — Professional Profile

Interactive professional website for **Dr Gopikrishnan Palanivel**, M.B.B.S., M.D. (Anaesthesiology),
M.B.A. (Healthcare & Hospital Management) — Specialist Anaesthesiologist & Intensivist, Chennai, India.
DHA registered for specialist anaesthesia practice in Dubai.

## Live site

<https://USERNAME.github.io/REPO/>

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
index.html      complete site — HTML, CSS and JS in one file, no build step
img/            portrait and credential scans
.nojekyll       serve files as-is, skip Jekyll processing
```

## Local preview

```
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Notes

- No frameworks, no dependencies, no build step. Edit `index.html` and push.
- Typefaces load from Google Fonts (Archivo, Source Serif 4, IBM Plex Mono).
- Light and dark themes both supported, with a manual toggle.
- Sensitive identifiers on the scanned documents (residential address, Academic Bank of
  Credits ID, and the DHA verification PIN, barcode and QR) have been masked.
