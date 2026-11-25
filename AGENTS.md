# Public résumé publishing repository

GitHub Pages serves `index.html` and `resume.pdf` from the root of `main` at <https://justusburger.github.io/cv/>.

Start résumé changes in the private `resume-current` source checkout (typically `~/src/resume-current`). Follow its `AGENTS.md` for editing the JSON, portrait, or template and rebuilding the HTML and PDF. Treat the files here as publishing artifacts. Avoid editing résumé content, portrait, or shared layout directly in this repository.

For a release, update `index.html` from the source build's `dist/resume.html` and preserve the public favicon, PDF download link, and its screen and print styles. Copy the matching `dist/resume.pdf` to `resume.pdf`. Review the diff, confirm the PDF matches the source artifact, and verify both live files after the GitHub Pages deployment.
