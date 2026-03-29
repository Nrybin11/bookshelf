# Bookshelf PWA — Setup Guide

Your personal book library app. Follow these steps to get it on your iPhone.

---

## Step 1 — Create a free GitHub account
If you don't have one, go to https://github.com and sign up. It's free.

---

## Step 2 — Create a new repository

1. Click the **+** button (top right on GitHub) → **New repository**
2. Name it: `bookshelf`
3. Set it to **Public**
4. Click **Create repository**

---

## Step 3 — Upload your files

1. In your new repo, click **Add file** → **Upload files**
2. Upload ALL of these files/folders:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - The entire `icons/` folder (both .png files inside)
3. Click **Commit changes**

---

## Step 4 — Turn on GitHub Pages

1. In your repo, click **Settings** (top menu)
2. Scroll down to **Pages** (left sidebar)
3. Under "Source", select **Deploy from a branch**
4. Set Branch to **main** and folder to **/ (root)**
5. Click **Save**
6. Wait 1–2 minutes, then your app will be live at:
   `https://YOUR-USERNAME.github.io/bookshelf`

---

## Step 5 — Add to your iPhone home screen

1. Open Safari on your iPhone
2. Go to: `https://YOUR-USERNAME.github.io/bookshelf`
3. Tap the **Share** button (box with arrow at bottom of Safari)
4. Scroll down and tap **"Add to Home Screen"**
5. Tap **Add**

The Bookshelf icon will appear on your home screen like any other app!

---

## Features
- Add books with title, author, genre, year, status & notes
- Filter your library by read / reading / unread
- Search to instantly check if you own a book
- Works offline after first load
- All data saved locally on your phone

---

## Updating the app in the future
To add new features, just edit the files and re-upload them to GitHub.
GitHub Pages will automatically update your live app within a minute or two.
