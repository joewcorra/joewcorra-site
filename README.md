# joewcorra-site

Personal Quarto website. Portfolio only — no blog.

## Setup

1. Install Quarto: https://quarto.org/docs/get-started/
2. Clone this repo and open in RStudio (or any editor)
3. Preview locally:

```r
quarto::quarto_preview()
# or from terminal:
# quarto preview
```

## Before publishing

- [ ] Add your photo as `images/photo.jpg` (square crop works best; will be displayed circular)
- [ ] Add a `images/favicon.png` (32x32 or 64x64 px)
- [ ] Update GitHub and LinkedIn URLs in `_quarto.yml`
- [ ] Add your actual GitHub handle to project card links in `projects.qmd`
- [ ] Place your resume PDF at `cv/resume_corra_j.pdf` for the CV download link
- [ ] Add DOI links to publications as they become available

## Deploying

Easiest options:
- **GitHub Pages**: `quarto publish gh-pages`

## Structure

```
_quarto.yml         # site config, navbar, theme
index.qmd           # landing/about page
projects.qmd        # project card grid
publications.qmd    # publications list
cv.qmd              # inline CV + PDF download
styles/custom.scss  # all custom styling
images/             # photo, favicon
cv/                 # place resume PDF here
```
