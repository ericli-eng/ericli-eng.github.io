# Eric Li — Engineering, AI & Product Portfolio

A lightweight, dependency-free portfolio designed for **GitHub Pages**. It presents four core areas of work:

- **Orvanthis** — live continuous market-research and prioritization product
- **Siemens NX** — mechanical CAD and rendering gallery
- **ASME Robotics Rover** — system-level rover CAD and subsystem integration
- **Machine Learning Research** — *Comparing Performance of Mamba and Self-Attention Models on Imbalanced Image Classification Tasks*

## Live project included

**Orvanthis:** https://orvanthis.com/

The portfolio links directly to the production site and frames the project around its evidence-first research workflow: discovery, evidence, risk, validation, and follow-up.

## Repository structure

```text
.
├── index.html
├── styles.css
├── script.js
├── README.md
└── assets
    ├── favicon.svg
    ├── docs
    │   └── mamba-vs-transformers.pdf
    └── images
        ├── cad
        │   └── ... Siemens NX renders
        └── rover
            └── ... ASME rover CAD images
```

## Publish with GitHub Pages

1. Create a new GitHub repository, e.g. `portfolio`.
2. Upload the contents of this folder to the repository root.
3. Commit and push to the `main` branch.
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select **main** and **/(root)**, then save.
7. GitHub will provide the public Pages URL after deployment.

If you name the repository `<your-username>.github.io`, the site can appear directly at `https://<your-username>.github.io/`.

## Before publishing

Update the contact links in `index.html` if you want to use a personal email, GitHub profile, LinkedIn, resume, or another call-to-action. The current email button uses the public Orvanthis contact address.

## Design notes

- No build system or framework required
- Responsive on desktop and mobile
- Accessible semantic HTML and keyboard-friendly image lightbox
- Optimized WebP project images
- Research paper is included as a directly viewable PDF
- Dark, engineering-focused visual system intended to keep project imagery prominent

## Content note

Project images, research content, and Orvanthis-related materials remain the property of their respective owner(s). This repository does not add an open-source license to those materials.
