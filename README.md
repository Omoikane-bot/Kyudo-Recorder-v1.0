# 弓道 的中記録 — Kyudo Hit Tracker

A one-screen, single-handed tracker for kyudo target practice. Tap where each arrow lands, record the 立（たち / run), and it keeps your 射数（しゃすう / arrow count）, 中（あたり / hits）, 的中率（てきちゅうりつ / hit rate）and grouping tendency for you. Works offline once loaded — good for the dojo.

## Languages

- **日本語**: the site's main page (`index.html`)
- **English**: add `index-en.html` to the site address, or tap the language link at the top of the app

Both share the same saved data on your device, so you can switch freely.

## Install on your phone (recommended)

It runs like a normal app with its own icon, full-screen.

**iPhone / iPad**
1. Open the tracker link in **Safari** (must be Safari). Use the Japanese or English page — whichever you want on your home screen.
2. Tap **Share** → **Add to Home Screen** → **Add**.
3. Launch it from the new 的 icon.

**Android**
1. Open the link in **Chrome**.
2. Tap the menu (⋮) → **Add to Home screen** / **Install app**.

You can also just use it in the browser without installing.

## How to use

0. **Enter your name** in the top-right once. It's saved on your device and appears on your exported report.
1. **Tap the 的（まと）** where each arrow lands — inside the ring = 中 (hit), outside the ring = a miss with direction recorded. The last shot gets a dashed halo.
2. For an arrow that missed the target completely, tap **枠外 / Off target**.
3. When the run is done, tap **この立を記録 / Record this tachi** — it adds to your totals and clears the face for the next run.
4. **戻す / Undo** removes the last tap (or pulls the last recorded 立 back if the current run is empty).
5. **新しい稽古 / New session** saves the day and starts fresh.
6. **書き出し / Export** gives you a **target diagram image** — all shots on one big 的 plus a mini-的 for every 立 — to save to Photos or share, and a text summary underneath.

### Options (chips under the target)
- **星的（ほし）/ 霞的（かすみ）** — switch the target face.
- **狙い線 / Aim lines** — show a centre crosshair to read left/right and high/low drift.
- **履歴 / History** — show or hide faint dots from earlier runs in the session.

## Your data

Your log is stored **only on your own device** (in the browser, for this site). It is private to you — nobody else can see it, and there is no shared leaderboard. Clearing your browser data will erase it, so export sessions you want to keep.

## Files

`index.html` (日本語) · `index-en.html` (English) · `manifest.json` · `manifest-en.json` · `icon-180.png` · `icon-512.png` · `sw.js` (offline support)

No account, no server, no tracking — everything runs on your phone.
