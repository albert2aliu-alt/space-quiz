# Space Quiz

A polished, responsive space exploration quiz with ten questions, animated answer feedback, a live score, and a final results screen. The project is a single static `index.html` file: it uses vanilla HTML, CSS, and JavaScript with no external assets, runtime dependencies, or build step.

## Run locally

Open `index.html` directly in a modern browser. No server or install is required.

## Play

Select **Start mission**, choose one answer for each question, and use **Next question** to continue. The quiz reports your score and a mission-complete emoji at the end. Use **Fly again** to restart. Keyboard users can move through the answer buttons with Tab and activate them with Enter or Space.

The interface follows your system light/dark preference by default. Use the theme button to switch themes manually. Reduced-motion preferences are respected.

## Publish

The existing GitHub Actions workflow in `.github/workflows/deploy-pages.yml` deploys the repository root to GitHub Pages when changes are pushed to `main` or when the workflow is run manually. Enable GitHub Actions as the Pages source in the repository settings if it is not already enabled.

## Attribution and license

Created by [James Montemagno](https://github.com/jamesmontemagno), adapted from [First Steps with GitHub Copilot](https://github.com/jamesmontemagno/first-steps-with-github-copilot). Released under the [MIT License](LICENSE).
