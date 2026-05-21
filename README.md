# Concours d'Elegance — Digital Judging (Concept Prototype)

An interactive concept prototype for a mobile app that replaces judges' paper
clipboards at Concours d'Elegance car-show events. A head judge builds and assigns
custom scoring forms; walking judges score cars on a phone, with auto-calculated
scores, notes, and photos — and it works fully offline.

This is a **concept prototype with sample data**, not production software.

## Files

| File | Purpose |
|------|---------|
| `index.html` | Landing page linking to both views |
| `phone.html` | Full-screen version — installable as an app, best for review on a phone |
| `prototype.html` | The app shown inside a phone frame — best for laptop / screen-share demos |
| `manifest.webmanifest` | Web app manifest (makes `phone.html` installable) |
| `sw.js` | Service worker — caches the app for instant load and full offline use |
| `icons/` | App icons used when added to a home screen |

## Live site

Published with GitHub Pages:

> _Add your Pages URL here once published, e.g._ `https://<username>.github.io/concours-judging-app/`

## Running locally

Open `index.html` in any modern browser. The prototype is fully self-contained —
there is no build step and no dependencies.

## Installing on a phone

Open the live URL on a phone, then use the browser's **Add to Home Screen** option.
The prototype launches full-screen from its own icon and works without a connection.

## Notes

- All data shown (event, cars, judges, scores) is fictional sample data.
- Scoring supports both deduction-based and additive methods, configured per form.
