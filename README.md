# Car Racing Simulation Cockpit

A final-year project by **Malek Ismail** and **Emir Zouabi**, developed at AJST FabLab Solidaires in 2022–2023. The project explores a physical cockpit for racing simulation, bringing together a steering wheel, pedals, handbrake and gearbox with vibration and force feedback.

This private repository combines a responsive project portfolio with the original report, selected report photographs and project-authored Unity scripts. The site describes what the report documents and links to the original LinkedIn demonstration.

## Portfolio

Open `index.html` in a browser, or run any static web server from the repository root. The website uses plain HTML, CSS and JavaScript; it needs no package installation or build step. Google Fonts are optional; system font fallbacks are included.

**Project demo:** [Watch on LinkedIn](https://www.linkedin.com/feed/update/urn:li:activity:7096957835313336320/)

The video is linked rather than embedded because playback and access are controlled by LinkedIn.

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

## Project details

The report describes an Arduino Leonardo as the cockpit microcontroller; pedal potentiometers and springs; shifter limit switches; and a steering wheel with a rotary encoder and a motor-driven force-feedback mechanism. The Unity source included here consists of the car controller and follow-camera scripts found in the supplied project. The car-controller script had a stray `&` before a field declaration; that syntax typo was removed in the repository copy so the script can be parsed.

The portfolio's workshop images are real photographs embedded in the authors' report, reproduced with the corresponding figure numbers and captions. They show physical parts and prototypes, not CAD renders. The images are also retained under `assets/photos/`.

The original report is preserved at `docs/report/rapport-PFE-Malek-Ismail-Emir-Zouabi.docx`. The existing Unity project was inspected without changing its source directory. Only selected scripts, their Unity metadata, the original package manifest and Unity version were copied. The full Unity scenes/assets were not imported: the supplied project contains EasyRoads3D and MapMagic content, and no attempt is made to redistribute those vendor assets.

No standalone editable SolidWorks CAD models are included; the documented part visuals are photographs in the report.

## Open the Unity code

Open `UnityProject/` with Unity **2021.3.26f1**. The package manifest is carried over from the supplied project. This repository intentionally includes only the selected C# scripts and the minimum Unity project metadata, not a complete playable scene or its third-party assets.

## Accuracy and scope

The site does not claim universal game compatibility, a specific device-connection protocol or performance measurements. The LinkedIn demo is the source for viewing the original project in motion.
