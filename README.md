# Swisstransplant cookbook for R

This repo is home to the Swisstransplant R cookbook. It includes instructions on the R package [`swt`](https://github.com/Swisstransplant/swt) to produce dynamic reports and ggplot2 figures in our in-house style.

The cookbook is available at this link:
<https://swisstransplant.github.io/rcookbook>

To publish the cookbook, use the Windows Command Prompt (and no bash emulation) and navigate to the project directory; then type:

```
quarto publish gh-pages R/rcookbook.qmd
```