# SENEX · PUER · CYCLICA

A tiny static Venn-board app for organizing ideas with draggable sticky notes.

The three outlined circles are:

- **SENEX** — red
- **PUER** — gold
- **CYCLICA** — blue

Notes change appearance depending on where their center is placed. If a note is in an overlap, its color blends the relevant circle characteristics.

## How to use locally

Open `index.html` in your browser.

## How to host on GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html` to the repository root.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/root`.
6. Save.
7. GitHub will give you a public URL.

## Data

The app saves notes automatically in your browser using `localStorage`.

Use **Export** to download a JSON backup of the board.

Use **Import** to restore a previously exported board.
