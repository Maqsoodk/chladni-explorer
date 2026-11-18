# CHLADNI — Visible Resonance

An interactive motion laboratory inspired by the Chladni plate experiment. Explore the patterns created by idealized standing-wave modes on a square plate, and watch simulated grains assemble near the nodal lines.

![A still from Chladni Explorer](chladni-preview.jpg)

## Experience

- Explore five resonance geometries: Diagonal, Circle, Curvature, Lattice, Rosette.
- Adjust excitation and sand-grain count.
- Reveal the modeled vibration field and cycle through modes automatically.
- Start/stop the synthesized tone, pause, save a PNG, and record a silent WebM video (browser support varies).
- Works with modern desktop and mobile browsers; higher grain counts may be slower on phones.

**Scientific scope:** An illustrative model, not a recording of a physical experiment. The nodal patterns come from analytical mode shapes for an idealized simply supported square plate; grain movement uses a stylized transport simulation. Frequencies shown are theoretical estimates, not measured resonance frequencies.

## Publish on GitHub Pages

1. Create a **public** repository named `chladni-explorer` at <https://github.com/new>.
2. Upload the files in this folder to the repository root. The home page must be named **`index.html`**.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select **main** and **/(root)**, then click **Save**.
6. Once publishing completes, open `https://YOUR-USERNAME.github.io/chladni-explorer/` (replace YOUR-USERNAME).

For troubleshooting see [GitHub Pages documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

## File layout

```
index.html             The complete website — HTML + CSS + JavaScript
chladni-preview.jpg    Repository preview image
.nojekyll              Serve site directly without Jekyll preprocessing
README.md              Project information and deployment instructions
```

No Node.js, build tools, external dependencies, paid hosting, or server are required.

## Sharing and attribution

The source files are public if published in a public GitHub repository. The repository does not include a license. If you want others to reuse or modify the code, choose and add a suitable open-source license separately.
