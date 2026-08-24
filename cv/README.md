# Curriculum vitae

The editable source is `curriculum_vitae.tex`. To build it locally, run:

```sh
latexmk -pdf -interaction=nonstopmode -halt-on-error curriculum_vitae.tex
```

When this source is pushed to `main`, the `Build CV` GitHub Actions workflow
compiles it and commits the resulting PDF to
`assets/files/curriculum_vitae.pdf`, which is the file linked by the website.

The workflow can also be run manually from the Actions tab.
