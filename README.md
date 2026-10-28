# Zac Vo | Engineering Portfolio

Mechanical engineering • Mechatronics • Product and process improvement

I'm Zac (Hoang Long) Vo, a Mechanical Engineering student at the University of Toronto, focusing on mechatronics and solid mechanics. This repository contains the source for my engineering portfolio: course projects, CAD assemblies, design studies, manufacturing experience, and community work.

**[Explore the portfolio website](https://zacvo01.github.io/ZacVoEngineeringPortfolio/)** · **[LinkedIn](https://www.linkedin.com/in/hoang-long-vo/)** · **[Project guide](docs/PROJECTS.md)**

## Start here

If you're interested in the engineering behind a project, open its detail page and look through the original images and diagrams. The accompanying [project guide](docs/PROJECTS.md) summarizes the problem, approach, contribution, and available evidence for each entry.

| Project | What it covers | Details |
| --- | --- | --- |
| Antenna torque-balancing system | Counterweight concept, sheet-metal design, displacement simulation | [View project](project1.html) |
| FDM 3D printer | Motion systems, axes, lead screw, nozzle and extrusion concept | [View project](project2.html) |
| Gearbox design | Gears, shafts, housing, assembly and 3D printing | [View project](project3.html) |
| Can-opener redesign | Gear geometry, higher output torque, CAD motion mates | [View project](project4.html) |
| Screwdriver mechanism | Planetary gearing and manual/electronic-mode locking concept | [View project](project5.html) |
| Jigsaw design | Mechanical assembly and mechanism drawings | [View project](project6.html) |
| V6 engine CAD model | Engine component modeling, assembly, motion analysis | [View project](project7.html) |
| Brighter Pages | Educational outreach and community organizing | [View project](project8.html) |
| Mancor manufacturing internship | Welding cell layout, fixtures, process flow and standard work | [View project](project9.html) |

## Experience beyond the original website

**Collins Aerospace — Continuous Improvement Intern (16-month placement)**

My work combined shop-floor improvement and operational technology rollout. I coordinated stakeholder feedback, workflow layouts, feature selection and prioritization, user onboarding, training and troubleshooting for PowerApps-based tools supporting approximately 300 shop-floor users. Developers were responsible for implementing the application code. I also contributed to 5S, process mapping, tier management and continuous-improvement projects.

**University of Toronto Formula Racing (UTFR) — Internal FEA / EBS Design**

- Designed mounting options for pneumatic Emergency Braking System (EBS) pistons with a required **10 mm clearance** between the housing and pistons.
- Analyzed shear stresses in mounting tabs and bolts, targeting a **factor of safety ≥ 2** under peak braking loads and an estimated **20% reduction in failure risk**.
- Used **ANSYS Mechanical** for yielding and fatigue analysis of a custom EBS chamber operating at **140 psi**; project estimates indicated up to **25% longer fatigue life** and **$90 lower manufacturing cost per redesigned part**.

**University of Toronto Consulting Association (UTCA) — Consulting Project, CIBC Client**

Worked on a UTCA consulting engagement for **CIBC**. Specific deliverables and analysis can be added once confirmed; this portfolio does not imply unverified project outcomes.

**MIE444 Mechatronics Rover — University of Toronto**

Worked on a four-wheel omni-directional rover integrating an Arduino Mega, DC motor control, encoders, Bluetooth communication and distance sensing. This is ongoing project context, not a claim that all planned functions were successfully implemented or verified. A dedicated technical repository/page can be added when hardware, code and test artifacts are ready to share.

These experiences are also summarized in the website's resume section. Existing project pages remain intact.

## Repository layout

```text
.
├── index.html                 # Portfolio landing page
├── project1.html ... project9.html
├── portfolio-details.html    # Existing template/detail page
├── assets/
│   ├── img/                  # Original project photos and diagrams
│   ├── css/                  # Website styling
│   ├── js/                   # Website interactions
│   └── vendor/               # Front-end libraries
├── forms/
└── docs/
    └── PROJECTS.md           # Project-by-project engineering documentation
```

## View the website locally

This is a static HTML/CSS/JavaScript portfolio. Clone the repository and open `index.html` in a browser. For a local HTTP server (recommended for consistent asset loading):

```bash
git clone https://github.com/ZacVo01/ZacVoEngineeringPortfolio.git
cd ZacVoEngineeringPortfolio
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Notes about the evidence

- The photos and drawings in `assets/img/` are preserved from the original portfolio.
- Project descriptions distinguish documented work from future extensions.
- Original project pages remain the source for historical course-project descriptions; this README is an overview, not a replacement.
- The repository currently presents a website and its media, **not** a complete archive of native CAD, firmware or manufacturing documentation.
- Some older pages use broad or inconsistent terminology. The [project guide](docs/PROJECTS.md) records what is documented and where more evidence would improve the story.

## Next documentation improvements

Add CAD exports, design constraints, calculations, test data, code, and a short `README.md` inside dedicated project repositories as those materials become available. Prefer measured results and images of actual prototypes over unverified performance claims.

---

© Zac Vo. Portfolio text, photographs and project materials remain attributed to their respective owners. Third-party template and vendor code retain their existing license notices.
