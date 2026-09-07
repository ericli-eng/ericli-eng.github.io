# Eric Li — Engineering, AI & Product Portfolio

A lightweight GitHub Pages portfolio featuring:

- **Orvanthis** — live product: https://orvanthis.com/
- **Siemens NX** — 8 mechanical CAD/rendering examples
- **ASME Robotics Rover** — 4 assembly and mechanism CAD views
- **Machine Learning Research** — *Comparing Performance of Mamba and Self-Attention Models on Imbalanced Image Classification Tasks*

## Simple root-level structure

This version intentionally keeps every file at the repository root so it is easy to upload through GitHub's web interface.

```text
.
├── index.html
├── styles.css
├── script.js
├── README.md
├── favicon.svg
├── Paper Comparing Mamba and Transformers.pdf
├── Funnel.png
├── Picture4.jpg
├── Picture5.jpg
├── Picture6.jpg
├── Picture7.jpg
├── Picture8.jpg
├── Picture9.jpg
├── Picture10.jpg
├── rover-electronics.png
├── rover-full-assembly.png
├── rover-linkage-detail.png
└── rover-suspension.png
```

## Publish with GitHub Pages

For the GitHub account `ericli-eng`, the cleanest repository name is:

```text
ericli-eng.github.io
```

1. Upload **all files in this folder** to the repository root.
2. Commit the changes to `main`.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose **main** and **/(root)**, then save.
6. The site should become available at `https://ericli-eng.github.io/` after GitHub finishes deploying it.

## Important

`index.html` now references the JPG/PNG/PDF files directly from the repository root. There is no `assets` folder required in this version.
