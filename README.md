# Experience Journal

A single-page journal of numbered interactive ambience experiments.

- `001`: Slow blur dissolve ambience with drifting photos, risograph-style color wash, dot grain, vignette, and crossfaded audio.
- `002`: Pixel dissolve reveal brush. Move or press over the image to fade rectangular pixels from the top layer and reveal a deeper blended image stack underneath. This sketch no longer auto-advances; use next when you want a new reveal layer.
- `003`: Concentric circular image masks that offset in layered motion over a softened duplicate of the same image.
- `004`: Placeholder for the next sketch.
- `005`: p5Catalyst.
- `006`: PerlinNoiseSlider.
- `007`: ScanLines.
- `008`: TrailingCircle.
- `009`: CirclePatternSketch.
- `010`: CircleLine.
- `011`: imageslice.
- `012`: dot-connect.
- `013`: Wander-Web.
- `014`: GradientNodes.
- `015`: GradientDrag.
- `016`: ColorPills.
- `017`: AntiGravity_001.
- `018`: midi-experiments.
- `019`: digital-nature.

Audio is shared across the journal. `001` can cycle the audio bed with the image fade, while `002` and `003` keep the current sound bed running as their visuals change.

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

The current page uses local files in `assets/images/` and `assets/audio/`. Update the `IMAGES` and `AUDIO_TRACKS` arrays inside `index.html` when replacing or reordering assets.
