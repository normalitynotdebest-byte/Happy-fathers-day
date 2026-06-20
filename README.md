# Happy Father's Day ❤️

A personal, single-page Father's Day website — premium glass design, family photos, and a song, all wrapped into one shareable link.

Everything (photos + music) is embedded directly inside `index.html`, so there is nothing else to configure. Upload this repo, turn on GitHub Pages, and you have a live link to send.

---

## 🚀 Host it on GitHub Pages (free, ~3 minutes)

### 1. Create a new repository
- Go to [github.com/new](https://github.com/new)
- Name it anything, e.g. `fathers-day`
- Set it to **Public** (required for free GitHub Pages)
- Click **Create repository**

### 2. Upload the file
- On your new repo's page, click **Add file → Upload files**
- Drag in `index.html` from this folder
- Scroll down, click **Commit changes**

### 3. Turn on GitHub Pages
- Go to your repo's **Settings** tab
- In the left sidebar, click **Pages**
- Under **Branch**, select `main` and folder `/ (root)` → click **Save**
- Wait 1–2 minutes. GitHub will show you a live URL like:

  ```
  https://your-username.github.io/fathers-day/
  ```

### 4. Open the link
- Visit the URL above (give it a minute if it 404s at first — it's still deploying)
- Once it loads correctly for you, send that same link to your dad — works on any phone, tablet, or laptop browser, no app needed

---

## 📱 What he'll see

1. A short loading screen ("Made With Love ❤️")
2. A full-screen photo with **"Papa Yha Dabao ❤️"** button
3. Tapping it starts the music, launches confetti, and begins a photo + message slideshow
4. Ends on a final "Happy Father's Day" screen with a **Watch Again** button

No installs, no accounts — just a link that works the same on Android, iPhone, or desktop.

---

## 🛠 Notes

- The file is large (~6 MB) because the song and all three photos are embedded directly inside `index.html` as base64 data — this is intentional, so the page never depends on loading separate files and works reliably the first time, every time.
- If you ever want to swap a photo or the song, see `EDITING.md` in this folder.
- Don't rename `index.html` — GitHub Pages looks for that filename specifically to serve as your homepage.
