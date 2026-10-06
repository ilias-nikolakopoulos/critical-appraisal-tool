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

Everything you enter is saved in your own browser (`localStorage`). Nothing is sent to a server.

## Use it

Open the live version at https://ilias-nikolakopoulos.github.io/critical-appraisal-tool/, or download `index.html` and open it in any modern browser.

## License

[MIT](LICENSE)
