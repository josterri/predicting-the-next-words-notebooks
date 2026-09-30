# Predicting the Next Words — notebooks

The companion notebooks for *Predicting the Next Words*. Chapters 1 to 15 each
have a lab notebook, `chNN_<topic>.ipynb`, and a chapter with a workbook also has
`chNN_workbook.ipynb`: three short steps and an appendix, with the solutions
folded. Each opens in Google Colab from the badge at the top of the notebook.

`data/pride_and_prejudice.txt` holds the novel's 61 chapters, which the
workbooks download when they run.

This repository is a **mirror**. The notebooks are written and reviewed in the
course repository, which is private; this one exists so that Colab can read
them, because Colab opens notebooks from GitHub anonymously and cannot see a
private repository. Nothing here is edited by hand — `tools/publish_notebooks.py`
in the course repository writes it, and a check there fails if the two drift.

Course materials, slides and exercise sheets: https://josterri.github.io/predicting-the-next-words-teaching/

Lab notebooks that need a package Colab does not ship have a `%pip install`
cell at the top. Running it twice is harmless.
