# Experience Journal

A single-page journal of numbered interactive ambience experiments.

- `001`: Slow photo fade with rotating buffer-inspired datamosh modes: horizontal block shifts, channel corruption, threshold fragments, vertical tears, and automatic frame-feedback transfer from the next image.
- `002`: Rollover pixel reveal with three image layers and a scattered circular brush.
- `003`: Concentric duplicate-image masks that rotate and offset over the matching base image.
- `004`: Granular shatter: click refreshes the composition; rollover and drag add sampled image shards that burst, drift, and fade.
- `005`: Additive remix: click refreshes a dense field of circular photo samples; rollover and drag add more sampled circles.
- `006`: Radial lens: a colorful blurred photo field with a black-and-white circular zoom study from another photo.
- `007`: Lomo double exposure: two offset photographs, saturated toy-camera color, film grain, vignette, and irregular edge light leaks.
- `008`: ActionSampler double exposure: four sequential frames, each made from two overlapping photographs with toy-camera grain, color, and light leaks.
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

Audio is shared across the journal. The minimal player shows track name, time, progress, volume, mute, and reset; reset and sketch navigation both choose a new random sound bed.

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
