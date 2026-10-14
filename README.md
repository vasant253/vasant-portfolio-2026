# Vasant Gawade — Portfolio

A one-page static site. No build step.

## Add a video to a row
Open `index.html`, find the row (search for its caption, e.g. `AI product commercials`) and paste one link into `data-src=""`:

- Google Drive: `https://drive.google.com/file/d/FILE_ID/view` (set sharing to "Anyone with the link")
- YouTube: `https://youtu.be/VIDEO_ID` (Public or Unlisted)
- Vimeo: `https://vimeo.com/VIDEO_ID`
- Your own file: `videos/ads-01.mp4`

The thumbnail is loaded automatically. For a sharper cover, add `data-poster="img/your-cover.jpg"`.

## Deploy on Vercel
1. Push this folder to a GitHub repo (or drag it into vercel.com/new).
2. Framework preset: **Other**. Build command: none. Output directory: `./`.
3. Deploy. Every push updates the site.

## Link previews (do this once after the first deploy)
In `index.html`, replace every `SITE_URL` with your live address (e.g. `https://vasantgawade.vercel.app`) and push again.
Then WhatsApp / LinkedIn show a card with your photo and name when you share the link.
If WhatsApp still shows an old preview, add `?v=2` to the end of the link once.

## Showreel
The first video under the hero. Put your reel link (or `videos/showreel.mp4`) in its `data-src`.
An .mp4 plays muted on loop automatically.
