# Maanya Tyagi — Portfolio (single-file version)

Open `index.html` in a browser, or host the folder on any static host (GitHub Pages, Netlify, Vercel). Needs internet for Three.js (cdnjs) and Google Fonts.

## Still to add (not included in this zip)
1. Resume: put your PDF at `public/resume/Maanya_Tyagi_AI_ML_Resume.pdf`, then add
   `<a class="btn" href="public/resume/Maanya_Tyagi_AI_ML_Resume.pdf" download>Download Resume</a>` in the hero, nav, About and Contact sections of `index.html`. (The resume .docx was never uploaded, so no PDF exists yet.)
2. Photos: save to `public/photos/` and replace the `.ph` placeholder in the About section with an `<img>` tag.
3. Real brain: download the MRI-derived meshes from https://brainder.org/brain-for-blender (obj or ply, license CC BY-SA 3.0, by Anderson Winkler), put them in `public/models/`, and load them with Three.js OBJLoader/PLYLoader in place of the point-cloud brain. Credit the author on the page. Note: the files are not in this zip because they could not be downloaded in the build environment.

## Notes
- The current 3D scene (neurons, brain, body) is procedural and labelled as simulated. It is not real data.
- Content lives in the `D` object near the bottom of `index.html`.
