# abhijitkghosh.github.io

Personal academic website of **Abhijit Kumar Ghosh** — Lecturer, Department of Computer Science and Engineering, European University of Bangladesh; Research Assistant, ELITE Research Lab LLC.

Live site: https://abhijitkghosh.github.io

Built with Jekyll on GitHub Pages, based on the [Academic Pages](https://github.com/academicpages/academicpages.github.io) template.

## Where to edit things

| What | File |
|---|---|
| Name, bio, sidebar links (Scholar, ORCID, LinkedIn…) | `_config.yml` |
| Header menu | `_data/navigation.yml` |
| Home page | `_pages/about.md` |
| CV page | `_pages/cv.md` |
| Publications page | `_pages/publications.html` |
| Talks page | `_pages/talks.html` |
| Teaching page | `_pages/teaching.html` |
| Portfolio / projects page | `_pages/portfolio.html` |
| Downloadable CV (PDF) | `files/Abhijit_Kumar_Ghosh_CV.pdf` |
| Profile photo | `images/Abhijit.jpg` |

To update the CV PDF, upload the new file to `files/` with the same name `Abhijit_Kumar_Ghosh_CV.pdf`; all download buttons will pick it up automatically.

## Run locally

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

Then open http://localhost:4000.
