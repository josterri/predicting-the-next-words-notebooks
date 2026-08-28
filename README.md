# Predicting the Next Words — lab notebooks

The fifteen companion notebooks for *Predicting the Next Words*, one per
lecture. Each opens in Google Colab from the badge at the top of the notebook.

This repository is a **mirror**. The notebooks are written and reviewed in the
course repository, which is private; this one exists so that Colab can read
them, because Colab opens notebooks from GitHub anonymously and cannot see a
private repository. Nothing here is edited by hand — `tools/publish_notebooks.py`
in the course repository writes it, and a check there fails if the two drift.

Course materials, slides and exercise sheets: https://josterri.github.io/predicting-the-next-words-teaching/

Notebooks that need a package Colab does not ship carry a `%pip install` cell
at the top. Running it twice is harmless.
