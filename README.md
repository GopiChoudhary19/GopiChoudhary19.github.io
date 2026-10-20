# Portfolio

Source for https://gopichoudhary19.github.io/ - plain HTML and CSS, no build step.

`resume.html` is printed to `resume.pdf` with headless Chrome:

```bash
chrome --headless --no-pdf-header-footer --print-to-pdf=resume.pdf resume.html
```
