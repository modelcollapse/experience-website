# Minimalist Audio & Photo Experience

A single-page ambient experience with fullscreen rotating photos, crossfaded audio, mute, volume, and next-track controls.

## Run locally

```sh
python3 -m http.server 3000
```

Then open `http://localhost:3000`.

## Publish on Replit

1. Create a new Replit project.
2. Upload these files, or import the GitHub repository after pushing it.
3. Replit will use `.replit` to serve the static page on port `3000`.
4. Click **Run**.

## Publish on GitHub Pages

1. Push this folder to a GitHub repository.
2. In GitHub, open **Settings > Pages**.
3. Set **Source** to **Deploy from a branch**.
4. Select the branch, then choose the repository root folder.
5. Save and wait for GitHub Pages to publish the site.

## Asset note

The current page loads sample photos from Unsplash and sample audio from Google-hosted sound files. For a production version, replace the URLs in `IMAGES` and `AUDIO_TRACKS` inside `index.html` with assets you own or have permission to use.
