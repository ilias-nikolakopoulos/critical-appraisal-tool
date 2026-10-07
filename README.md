# Critical appraisal tool for Journal Club

A single-page web app for appraising randomised controlled trials at journal club. It runs entirely in the browser and has no build step or server.

## Features

- **PICO**: define the trial's population, intervention, comparator and outcome, and see the question they form.
- **Checklist**: 13 questions in three parts (are the results valid, what are they, will they help my patients). Helpers drawn from the trial's numbers appear beside the relevant questions.
- **Results & precision**: enter the event counts and the reported effect to get:
  - absolute risk difference and NNT/NNH with 95% CIs
  - fragility index and fragility quotient (Fisher's exact test), compared with loss to follow-up
  - primary versus per-protocol comparison
  - non-inferiority assessment against a ratio or risk-difference margin, with a forest plot
  - design analysis with Type S and Type M errors (Gelman & Carlin, 2014)
- **Discussion**: prompts and a bottom-line summary.
- **Trial library**: keep several appraisals. The DanGer Shock trial is preloaded as a worked example.
- **Export and import**: save an appraisal as a file to back it up or send it to colleagues, and import theirs.

Everything you enter is saved on your own device (`localStorage`). Nothing is sent to a server.

## Use it

Open the live version at https://ilias-nikolakopoulos.github.io/critical-appraisal-tool/, or download `index.html` and open it in any modern browser.

### Install it on your phone

It installs like an app, with its own icon, full screen and working offline.

- **iPhone / iPad**: open the link in Safari, tap **Share**, then **Add to Home Screen**.
- **Android**: open the link in Chrome, tap **⋮**, then **Install app** (or **Add to Home screen**).
- **Mac / PC**: in Chrome or Edge, click the install icon in the address bar.

On iPhone, the home-screen app keeps its appraisals separately from Safari. Use **Export** and **Import** to move them across.

## License

[MIT](LICENSE)
