# “ಅಕ್ಷಯ” Gruhapravesha – Digital Invitation

The official Gruhapravesha invitation as a single page. Tapping the seal opens the envelope and reveals the name “ಅಕ್ಷಯ” one akshara at a time (ಅ → ಕ್ಷ → ಯ), with temple-bell chimes and golden sparkles. Then come the card's text on the pine-frame notebook pages and a pine scratch card that reveals the date.

The sounds are generated in the browser, so there are no audio files. On iPhone they only play when the phone's silent switch is off.

## Files
```
index.html               the whole site (HTML + CSS + JS in one file)
images/frame-portrait.*  the pine frame, upright
images/pine-tl.webp      soft pine corner, top-left (cut from the frame)
images/pine-br.webp      soft pine corner, bottom-right
images/scratch-pine.webp pine from the frame, used as the scratch-card surface
images/house.jpg         the house photo from the printed card
images/og-preview.jpg    picture shown when the link is shared
```

## Editing
- **Phone number (tap to call) and how much of the gold foil must be scratched:** the `CONFIG` block near the top of `index.html`.
- **Kannada text:** written directly in the HTML sections, which are marked with comments. Text inside the pine-frame pages shrinks automatically if it gets longer.

## Personal links for each guest
Add `?to=Name` to the link:
```
https://<username>.github.io/<repo>/?to=ರಮೇಶ್
```
The name appears on the opening envelope screen ("ಆತ್ಮೀಯ ರಮೇಶ್ ಅವರಿಗೆ").

## Publish on GitHub Pages
1. Create a **public** repository on github.com, for example `gruhapravesha`.
2. Choose **Add file → Upload files** and drag in `index.html`, `README.md` and the whole `images` folder. Click **Commit changes**.
3. Open **Settings → Pages**, choose Branch `main` and folder `/ (root)`, then click **Save**.
4. After 1–2 minutes the site is live at `https://<username>.github.io/gruhapravesha/`.

**WhatsApp preview picture:** after publishing, change `content="images/og-preview.jpg"` in `index.html` to the full address, `https://<username>.github.io/gruhapravesha/images/og-preview.jpg`.
