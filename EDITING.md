# Editing This Page

Everything lives inside one file: `index.html`. The photos and song are embedded as base64 text directly in the HTML, so there are no separate image/audio files to manage.

## Changing the text messages

Open `index.html` in any text editor and search for this block (near the bottom, inside the `<script>` tag):

```js
const messages = [
  "Tunak Tunak Papa! 🎉",
  "Thank You Papa ❤️",
  "For Everything You Do",
  "You Mean The World To Me",
  "Happy Father's Day! 🎊",
  "Love You Papa ❤️"
];
```

Edit any line, save, and re-upload to GitHub (or just commit the change if using GitHub's web editor).

## Changing a photo or the song

Because the media is embedded as base64, swapping it means re-encoding a new file and pasting the result in. This is easiest done by asking Claude to do it for you again with the new photo/song — just say "replace photo2 with this new image" and re-share this project.

If you'd rather do it manually:
1. Convert your new file to base64 (e.g. using [base64.guru](https://base64.guru/converter/encode/file) or `base64 yourfile.jpg` in a terminal)
2. In `index.html`, find the matching `data:image/jpeg;base64,...` or `data:audio/mpeg;base64,...` string
3. Replace everything between the quotes with your new base64 string

## Quick edits via GitHub's web editor (no software needed)

1. Go to your repo on github.com
2. Click on `index.html`
3. Click the pencil ✏️ icon (top right) to edit directly in the browser
4. Make your change, then click **Commit changes**
5. GitHub Pages will redeploy automatically within a minute or two
