# CV

This is the repository for my CV.
The latest version of it can be found on the [releases](https://github.com/nahu02/CV/releases) page; or open the latest version [directly](https://github.com/nahu02/CV/releases/latest/download/abel-resume.pdf).
The PDF is also displayed on my [GitHub Pages](https://nahu02.github.io/) site.

## How it works

The CV is written in LaTeX using the Medium Length Professional CV template from [LaTeX Templates](http://www.latextemplates.com/template/medium-length-professional-cv) with slight modifications.

The GitHub Action [LateX to PDF](https://github.com/nahu02/CV/actions/workflows/latex-render.yml) is used to compile the LaTeX file to a PDF, and create a new release with the updated version. It is triggered on every push to the main branch.
