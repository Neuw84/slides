# Slides for programming courses

This is a collection of slides for programming courses, created from markdown sources.

See <http://marko-knoebl.github.io/slides> for the slides.

The presentations are standalone HTML files that can be downloaded and viewed offline.

## Building process

To build from the sources:

- clone this repository
- run `npm install`
- run `npm run build`

The build process looks for files in the _entrypoints_ folder which in turn include files from the _sections_ folder.

## Technical details, writing your own

The slides in this repository are created from markdown sources via [rehype-slides](https://github.com/marko-knoebl/rehype-slides)

If you want to create your own presentations, see [rehype-slides-starter](https://github.com/marko-knoebl/rehype-slides-starter)

## Philosophy

These materials are organized so that _relevant_ and _generic_ content is prioritized

principles applied in these slides:

- Cover the most important aspects first, dive deeper later
  - do sensible exercises as early as possible
  - keep details for later or provide references for self-study
- Prioritize general priniples that can be applied elsewhere (e.g. focus on "SQL basics" instead of "SQL in Python")
