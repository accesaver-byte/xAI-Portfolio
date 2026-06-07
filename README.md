# Travis Yip xAI Portfolio

Static GitHub Pages portfolio for the xAI AI Tutor - Chinese application.

## Files to add before publishing

Add these real assets:

- `assets/audio/travis-yip-chinese-voice-sample.mp3`
- `assets/audio/travis-yip-english-voice-sample.mp3`
- `assets/docs/travis-yip-annotated-transcript.pdf`
- `assets/docs/travis-yip-resume.pdf`

Then update the placeholder Google Drive links in `index.html`:

- `https://drive.google.com/`

Replace each placeholder with the public `Anyone with the link -> Viewer` URL.

## Local preview

Use any static server from this folder:

```powershell
python -m http.server 8080
```

Then open:

```text
http://localhost:8080
```

## GitHub Pages deployment

1. Create a GitHub repository named `xai-portfolio`.
2. Push this folder to the repository `main` branch.
3. In GitHub, open `Settings -> Pages`.
4. Set source to `Deploy from branch`, branch `main`, folder `/root`.
5. Test the published URL in a private browser window.

Expected project URL:

```text
https://<username>.github.io/xai-portfolio/
```

## Notes

- This page does not use xAI logos or imply affiliation.
- Audio does not autoplay.
- The values note is intentionally restrained and does not include sensitive personal political details.
