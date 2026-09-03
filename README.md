# StudyOS

> A terminal-inspired study command center for BTEUP back-exam preparation and computer-science career development.

StudyOS is a dependency-free static web app. It keeps exam preparation and career development as separate missions while providing one clear next action, practice, revision, projects, and progress tracking.

## Features

- BTEUP back-exam dashboard for Mathematics-I, Chemistry, Physics, and Communication Skills
- Topic queues with revision scheduling
- YouTube search redirects for current, discoverable learning resources
- Career roadmap from C fundamentals through Python, backend, APIs, AI integration, internships, and job preparation
- Python lesson checklist with prerequisite-aware progression
- Evidence-based career telemetry for practice accuracy, weak concepts, spaced revision, project milestones, and job readiness
- Locked roadmap access with DSA explicitly running alongside development
- Adaptive daily planner for 30 minutes through 4+ hours
- Practice engine with hints, explanations, scoring, accuracy, and XP
- Offline guided AI tutor demo with Hinglish-friendly prompts
- Project briefs and milestone tracking
- Spaced-revision queue
- Progress dashboard and job-readiness telemetry
- Settings stored locally in the browser
- JSON progress export
- Responsive hacker/terminal interface for mobile and desktop

## Run locally

No package installation or build step is required.

1. Clone or download this repository.
2. Open `index.html` in a browser.

For a local development server, use any static server, for example:

```bash
python -m http.server 8000
```

Then open <http://localhost:8000>.

## Deploy with GitHub Pages

This repository includes a GitHub Actions workflow for Pages deployment.

1. Push the repository to GitHub.
2. Open **Settings → Pages**.
3. Set the source to **GitHub Actions**.
4. Push to `main` or run the workflow manually.

The workflow publishes the repository root as a static site.

## Project structure

```text
.
├── index.html                 # Application shell
├── style.css                  # Terminal UI and responsive styles
├── app.js                     # Views, interactions, state, and local storage
├── .github/workflows/pages.yml
├── .gitignore
├── CONTRIBUTING.md
├── LICENSE
└── README.md
```

## Data and resource policy

- Progress is stored only in the browser's `localStorage`.
- Exported progress is a local JSON file.
- The app does not contain API keys or private credentials.
- YouTube buttons open live search results rather than inventing video titles, channels, or IDs.
- Syllabus, exam dates, and previous-year questions should be verified against official BTEUP sources before being treated as official.
- The included tutor is an offline guided demo. A production AI integration should use a secure server-side API route.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for the small workflow used for changes.

## License

Released under the MIT License. See [LICENSE](LICENSE).
