# python-ds-project-template

A Template for Python Data science Projects

- Basic folder structures.
- A .flake8 config file that increases the maximum line length
- A basic .gitignore file
- Jupyter config files that automatically save `.py` and `.html` copies of the notebook, change root to the `/notebooks` folder, and set a password to disable the token system (The password is hashed. Remember to set a new one if you don't know the old one).
- A filter in .gitconfig that clear all cell outputs before committing a notebook ([reference](https://zhauniarovich.com/post/2020/2020-10-clearing-jupyter-output-p3/)).

Post-forking steps:

- Run `git config --local include.path ../.gitconfig` to import filters to Git
