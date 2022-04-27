# nbstyle

The notebook behind my [JupyterCon 2020 presentation](https://cfp.jupytercon.com/2020/schedule/presentation/186/a-notebook-style-guide/): [Video](https://www.youtube.com/watch?v=gFvKvdznUdc) -- including speaker notes.

## Introduction

This notebook was written to accompany a talk around patterns I've
observed that make notebooks easier to read, write and maintain: both
from experience writing and using notebooks for several different
purposes, as well as stealing from far more accomplished authors.

## Minimal, 30 second version

- Keep minimal global state core to the notebook, manipulate it with
  pure functions.
- Assertions and tests throughout the notebook, preferably at the end
  of each cell.
- Structure it appropriately with headings.
- Make sure it runs cleanly with a run-all.
- Make sure it's meaningfully reproducible.
- Minimize noise from unnecessary output, like logging.
- Follow best practices for prose.
- Follow best practices for programming: PEP8, YAGNI, etc.
