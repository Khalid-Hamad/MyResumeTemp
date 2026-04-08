# MyResume

[![Build and Release](https://github.com/iamdotdev/MyResumeTemp/actions/workflows/release.yml/badge.svg)](https://github.com/iamdotdev/MyResumeTemp/actions/workflows/release.yml)

LaTeX resume that is automatically compiled and released as a PDF via GitHub Actions on every push to `main`.

## Download

Grab the latest PDF from the [Releases](https://github.com/iamdotdev/MyResumeTemp/releases/latest) page.

## Build Locally

Requires a TeX distribution with XeLaTeX (e.g. TeX Live, MiKTeX).

```bash
latexmk -xelatex resume.tex
```

## Project Structure

```
resume.tex            # Main document
custom-commands.tex   # Shared LaTeX macros
src/
  heading.tex         # Name and contact info
  education.tex       # Education section
  experience.tex      # Work experience
  projects.tex        # Projects section
  skills.tex          # Technical skills
  certifications.tex  # Licenses and certifications
```

## License

[MIT](LICENSE)
