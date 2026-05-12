# 📱 NRL Footy Tipper — iPhone App Install Guide
## Complete step-by-step for beginners

---

## What you'll need
- A computer (Mac or Windows)
- A free GitHub account
- Your iPhone
- About 10 minutes

---

## STEP 1 — Create a free GitHub account

1. Open your browser and go to **github.com**
2. Click **"Sign up"** in the top right
3. Enter your email, create a password, choose a username
4. Verify your email when GitHub sends you a confirmation
5. You're in! GitHub is completely free for what we need.

---

## STEP 2 — Create a new repository (this is just a folder on the web)

1. Once logged in, click the **"+"** button in the top right corner
2. Click **"New repository"**
3. Fill in the details:
   - **Repository name:** `nrl-tipper` (no spaces, all lowercase)
   - **Description:** NRL Footy Tipping App (optional)
   - Make sure **"Public"** is selected (required for free hosting)
   - Tick the box **"Add a README file"**
4. Click the green **"Create repository"** button

You'll land on your new repository page. It will look mostly empty — that's fine!

---

## STEP 3 — Upload your app files

1. On your repository page, click **"Add file"** → **"Upload files"**

2. You need to upload these 5 files from the zip you downloaded:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`

   **How to get the files out of the zip:**
   - **Mac:** Double-click the `nrl-tipper-pwa.zip` file — a folder called `nrl-tipper-pwa` will appear. Open it and you'll see the 5 files inside.
   - **Windows:** Right-click the zip file → "Extract All" → click "Extract". Open the `nrl-tipper-pwa` folder that appears.

3. Drag all 5 files from that folder into the GitHub upload box (or click "choose your files")

4. Scroll down to the bottom of the page
5. Make sure **"Commit directly to the main branch"** is selected
6. Click the green **"Commit changes"** button

Wait a few seconds while GitHub saves your files. You'll see them appear in your repository.

---

## STEP 4 — Turn on GitHub Pages (free web hosting)

1. Click **"Settings"** in the tabs near the top of your repository page
   *(It's to the right of "Insights" — you may need to scroll the tab bar)*

2. In the left sidebar, click **"Pages"**

3. Under **"Source"**, click the dropdown that says **"None"** and select **"main"**

4. Make sure the folder dropdown shows **"/ (root)"**

5. Click **"Save"**

6. GitHub will show a message: *"Your site is ready to be published"*
   Wait about 60 seconds, then refresh the page.

7. You'll see a green banner with your URL — it will look like:
   **`https://YOURUSERNAME.github.io/nrl-tipper/`**

   Write this URL down — this is your app's address! 🎉

---

## STEP 5 — Install on your iPhone

1. **On your iPhone**, open **Safari** (must be Safari, not Chrome)

2. Type your URL into the address bar:
   `https://YOURUSERNAME.github.io/nrl-tipper/`
   *(Replace YOURUSERNAME with your actual GitHub username)*

3. The app will load — it should look like a sleek dark sports app

4. Tap the **Share button** at the bottom of Safari
   *(It looks like a box with an arrow pointing up)*

5. Scroll down in the share sheet and tap **"Add to Home Screen"**

6. You can rename it (e.g. "Footy Tips") or leave it as is

7. Tap **"Add"** in the top right

8. **Done!** 🏉 The app icon will appear on your iPhone home screen.
   Tap it to open — it launches full screen like a native app!

---

## STEP 6 — Using the app

**Entering results each week:**
- Tap any game card to expand it
- Tap **"✓ WON"** or **"✗ LOST"** after each game finishes
- Results save automatically to your phone

**Tabs:**
- 🏉 **TIPS** — Current round AI picks with analysis
- 📋 **TRACKER** — Full season history, card points
- ⚔️ **H2H** — Aido vs Jess scoreboard
- 📱 **WIDGET** — Shows you what the home screen widget looks like

**Works offline:**
Once you've opened it once on your phone, it works without internet.

---

## Updating the app each week

When a new round starts, I'll give you a new `index.html` file with the updated tips and results. To update your app:

1. Go back to **github.com/YOURUSERNAME/nrl-tipper**
2. Click on `index.html` in your file list
3. Click the **pencil icon** (Edit) in the top right
4. Select all the text (Ctrl+A or Cmd+A), delete it
5. Paste in the new code I give you
6. Click **"Commit changes"**
7. Wait 60 seconds, then open your iPhone app — it will update automatically!

---

## Troubleshooting

**"I can't find the Add to Home Screen option"**
→ Make sure you're using **Safari**, not Chrome or Firefox. Only Safari supports PWA installation on iPhone.

**"The site shows a 404 error"**
→ Wait a few more minutes — GitHub Pages can take up to 5 minutes the first time. Also double-check the URL has your correct username.

**"The files aren't showing up after upload"**
→ Make sure you uploaded the files from *inside* the `nrl-tipper-pwa` folder, not the folder itself.

**"I accidentally uploaded the wrong files"**
→ On GitHub, click the file you want to replace → click the pencil icon → paste new content → commit. Or click the trash icon to delete it and re-upload.

---

## Your app URL (fill this in once set up)

```
https://________________________.github.io/nrl-tipper/
```

---

*Guide prepared for the NRL Footy Tipper PWA — Magic Round 2026*
*For help, just ask Claude! 😄*
