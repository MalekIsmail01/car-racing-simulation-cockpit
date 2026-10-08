# Car Racing Simulation Cockpit

A final-year project by **Malek Ismail** and **Emir Zouabi**, developed at AJST FabLab Solidaires in 2022–2023. The project explores a physical cockpit for racing simulation, bringing together a steering wheel, pedals, handbrake and gearbox with vibration and force feedback.

This private repository combines a responsive project portfolio with the original report, selected report photographs and project-authored Unity scripts. The site describes what the report documents and links to the original LinkedIn demonstration.

## Portfolio

The portfolio is published at [malekismail01.github.io/car-racing-simulation-cockpit-portfolio](https://malekismail01.github.io/car-racing-simulation-cockpit-portfolio/). The public site has its own repository containing only the portfolio and project photos; this repository remains private. Open `index.html` here in a browser or run any static web server from the repository root to preview it locally. The site uses plain HTML, CSS and JavaScript and requires no package installation or build step.

**Project demo:** [Watch on LinkedIn](https://www.linkedin.com/feed/update/urn:li:activity:7096957835313336320/)

The video is linked rather than embedded because playback and access are controlled by LinkedIn.

GitHub Pages deploys only the portfolio HTML, styles, script, favicon and project photos. The private project report and Unity source are not published.

## Repository layout

```text
.
├── assets/
│   ├── favicon.svg
│   └── photos/                 # Selected photographs embedded in the report
├── docs/
│   └── report/                 # Original final-year report
├── UnityProject/
│   ├── Assets/Scripts/          # Selected project-authored C# scripts
│   ├── Packages/                # Unity package manifest
│   └── ProjectSettings/         # Unity editor version
├── index.html                   # Portfolio site
├── script.js                    # Mobile navigation
└── styles.css                   # Responsive site styling
```

## Unity code

**Yes—the repository includes Unity C# code** from the supplied project, under [`UnityProject/Assets/Scripts/`](UnityProject/Assets/Scripts/):

- `CarController.cs` — car movement, steering, braking and wheel behavior.
- `cameracontroller.cs` — camera movement that follows the car.

These scripts are a small part of the Unity work, not the complete game or cockpit integration. Scenes and third-party road/terrain assets are not included, so `UnityProject/` is not a playable project on its own. The source project uses Unity **2021.3.26f1**. The supplied car-controller script had a stray character that prevented it from compiling; that typo is corrected in this copy.

The report also documents the physical controls: an Arduino Leonardo, pedal springs and potentiometers, shifter limit switches, and a steering wheel with a rotary encoder and motor-driven force feedback. Those details describe the hardware in the report; the included C# files do not implement its Arduino firmware.

## Report and photographs

The original report is in [`docs/report/`](docs/report/). The gallery uses real photographs embedded in that report, with their original figure numbers. They show the fabricated parts and physical prototypes—not CAD renders. The report does not include standalone editable SolidWorks model files.
