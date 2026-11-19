# Black Holes, Collapse and the Singularity Theorem

An interactive 3D presentation about black holes. It follows one story: from Newton's gravity, to Einstein's curved spacetime, to Penrose's 1965 proof, to the first images of black holes.

**Author:** Rishikesh Sonar

**Live demo:** https://black-holes-presentation-ten.vercel.app

---

## What is inside

- 24 slides in four parts: basic physics, formation, Penrose and the Nobel Prize, and applications.
- A black hole that is ray-traced live in the browser (WebGL).
- Interactive diagrams: geodesics, spacetime curvature, the Schwarzschild radius, stellar collapse, trapped surfaces, Penrose diagrams, the Event Horizon Telescope, LIGO mergers, Hawking radiation and the Page curve, and a timeline from 1687 to 2022.
- A **Theory** panel with short explanations. Each point is tagged Established, Observed, Prediction or Open question.
- Liquid-glass style panels, a light-waterfall effect on the timeline slide, and a parts menu at the top left.
- Optional sound and speaker notes.
- Works on phones, tablets, laptops, TVs and smart boards. Respects reduced-motion settings.

## Controls

| Action | Keys / touch |
| --- | --- |
| Next / previous slide | `→` `←`, `Space`, `Page Down` / `Page Up`, swipe on touch |
| First / last slide | `Home` / `End` |
| Theory panel | `T` or the **Theory** button |
| Speaker notes | `N` |
| Mute | `M` |
| Fullscreen | `F` |
| Parts menu | Click the menu at the top left. Use `↑` `↓` `Enter` `Esc` |

## Run on your computer

There is no build step. It is one HTML file.

```bash
git clone https://github.com/RishiLoveKanye/black-holes-presentation.git
cd YOUR-REPO
# Option 1: open index.html in your browser
# Option 2: run a small local server
python3 -m http.server 8000
# then open http://localhost:8000
```

Use a recent version of Chrome, Edge, Firefox or Safari. An internet connection is needed for the web fonts only.

## Deploy

This is a static site. Host it on Vercel, GitHub Pages or Netlify. For Vercel:

1. Push this repository to GitHub.
2. In Vercel, choose **Add New → Project** and import the repository.
3. Set **Framework Preset** to **Other**. Leave the build command and output directory empty.
4. Click **Deploy**.

## Science and sources

The theory in this project uses sources such as NASA, ESA/Hubble, LIGO, the Nobel Prize committee and published papers. The full list is on the last content slide ("Read more").

- The black hole is drawn with an approximate light-bending model. The diagrams are teaching illustrations.
- The Big Bang-style light show at the end is art. It is not a claim about physics.
- This work is independent. Roger Penrose and the Nobel Foundation do not endorse it.

## Project structure

```text
.
├── index.html   # the whole presentation (HTML, CSS and JavaScript)
└── README.md
```

## Licence

Add a `LICENSE` file of your choice before you publish (for example MIT). Third-party names and sources belong to their owners.
