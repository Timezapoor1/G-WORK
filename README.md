# G-WORK

A 5/3/1 workout tracker that runs in the browser and installs to the iPhone home screen.

- Per-lift cycle and week, with weights built from a training max (90% of your PR by default)
- Set-by-set logging, plate breakdown, rest timer
- PRs from estimated 1RM, updated automatically when you beat them
- Add your own lifts
- Works offline once loaded

## Run it

Serve the folder over HTTPS (service workers and install need it). With GitHub Pages:
Settings, Pages, Deploy from branch, `main`, `/ (root)`. The app is then at
`https://<user>.github.io/G-WORK/`.

Locally: `python -m http.server 8000` and open `http://localhost:8000`.

## Install on iPhone

Open the Pages URL in Safari, tap Share, then Add to Home Screen.

## Your data

Everything is stored in the browser's `localStorage`. The Safari tab and the installed home-screen
app keep separate copies, so pick one and stay with it. Use Settings, Backup to export a JSON file
and import it on another device or after a reset.
