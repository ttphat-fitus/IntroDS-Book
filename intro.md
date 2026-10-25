# Introduction

Term project report of Group 15 for Introduction to Data Science (HCMUS).

The project crawls the full-text LaTeX sources of our assigned arXiv papers (Milestone 1),
parses every version into a hierarchical structure (Milestone 2), and matches citations to the
crawled reference metadata with a machine learning pipeline evaluated by MRR@5 (Milestone 3).

- Source code: <https://github.com/ttphat-fitus/IntroDS>
- Dataset: Hugging Face link, published in Milestone 3

Every figure and table in this book is generated when the book is built, by notebooks that read
the small statistics files in `data/` exported with `python -m introds stats`.
