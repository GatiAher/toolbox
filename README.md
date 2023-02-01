# Code Tools

> Author: Gati Aher  
> Created: September 25, 2022
> macOS Monterey, MacBook Pro, Apple M1 Max

## 1. Mac Set-Up

### 1.1. Guides

- [How to Set up an Apple Mac for Software Development](https://www.stuartellis.name/articles/mac-setup/) by Stuart Ellis
- [macOS Setup Guide](https://sourabhbajaj.com/mac-setup/) by Sourabh Bajaj
- [Zettelkasten](https://www.youtube.com/playlist?list=PLgtmMKe4spCM5YQa3tbbdloBQB5RFKb3Y) by Artem Kirsanov
- [Zotero hacks: unlimited synced storage and its smooth use with rmarkdown](https://ikashnitsky.github.io/2019/zotero/) by ilya.kashnitsky

### 1.2. Tools

- xcode, homebrew, autocompletion of commands
- git, ssh keys
- [neovim](https://neovim.io/) + initalization - hyperextensible Vim-based text editor
- [Amethyst](https://ianyh.com/amethyst/) - tiling window manager for macOS

### 1.3. Formatting

- [Prettier](https://prettier.io/docs/en/install.html) - formatting for Markdown
  - [VS Code Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) - formatting for Markdown

### 1.4. Testing

- [pre-commit](https://pre-commit.com/) - multi-language package manager for pre-commit hooks

### 1.5 Notes

- [Obsidian]() + iPhone App + iCloud Sync
  - [Admonition](https://github.com/valentine195/obsidian-admonition) - adds admonition block-styled content to Obsidian.md
  - [Citations](https://github.com/hans/obsidian-citation-plugin) - Insert literature note references from Zotero Library
- [Zotero](https://www.zotero.org/) + iPhone App + Zotero Account Sync

  - [Firefox Contector](https://www.zotero.org/download/) - browser plugin
  - [Zotero Better Bibtex](https://retorque.re/zotero-better-bibtex/) - faculties for generating citekeys
  - [Zotfile](http://zotfile.com/ - manage attachments: automatically rename, move, and attach PDFs

## 2. Command-Line (Zsh)

### 2.1. Guides

- [Level up your terminal game with iTerm2’s Hotkey Window and text settings](https://www.typefloundry.com/1-800-iterm-bling.html) - very helpful guide to improving usability of iTerm2
- [A Quick and Easy Guide to tmux](https://www.hamvocke.com/blog/a-quick-and-easy-guide-to-tmux/)
- [Code like a Hacker: Another Neovim Terminal Setup](https://ccavales3.medium.com/code-like-a-hacker-another-neovim-terminal-setup-4613abecb7c8)
- [iTerm2 + Oh-My-Zsh: Supercharge Your Mac Terminal](https://catalins.tech/improve-mac-terminal#heading-install-iterm2) by Caitlin Pit
- [Vim and Tmux on your Mac](https://fideloper.com/mac-vim-tmux)

### 2.2. Tools

- [iTerm2](https://iterm2.com/) - better terminal for MacOS
- [tmux](https://github.com/tmux/tmux/wiki) - terminal multiplexer, window manager within the terminal (like screen)

### 2.3. Formatting

- [oh-my-zsh](https://ohmyz.sh/) - framework for managing Zsh configuration
  - [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) - Fish-like autosuggestions for zsh
  - [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) - Fish shell like syntax highlighting for Zsh. **Note:** manual install into `~/.oh-my-zsh/plugins/`
  - [autojump](https://github.com/wting/autojump) - weighted cd shortcut command (`j code` for `cd ~/Documents/Code`)
- [Powerlevel10k](https://github.com/romkatv/powerlevel10k) - popular zsh theme
- [thefuck](https://github.com/nvbn/thefuck) - corrects previous command
- ! [fasd](https://github.com/clvv/fasd) - shortcuts for terminal commands
- [tldr](https://tldr.sh/) - simplified man pages
- [tree](https://formulae.brew.sh/formula/tree) - visualize recursive directory structure

## 3. Bash

### 3.1. Guides

### 3.2. Tools

- [curl](https://curl.se/) - data transfer with URLs
- [jq](https://stedolan.github.io/jq/) - like `sed` for JSON data

### 3.3. Formatting

- [shellcheck](https://github.com/koalaman/shellcheck) - lint Bash scripts
  - [vscode-shellcheck](https://marketplace.visualstudio.com/items?itemName=timonwong.shellcheck)
- [shfmt](https://github.com/mvdan/sh) - format Bash scripts
  - [shell-format](https://marketplace.visualstudio.com/items?itemName=foxundermoon.shell-format)

### 3.4. Testing

- [bats](https://bats-core.readthedocs.io/en/stable/installation.html) - unit testing Bash scripts
  - [Bats on VS Code](https://marketplace.visualstudio.com/items?itemName=jetmartin.bats)

## 4. Python

### 4.1. Guides

- [Hypermodern Python - poetry](https://cjolowicz.github.io/posts/hypermodern-python-01-setup/) by Claudio Jolowicz, recommended by Eamon
- [Hypermodern Python Chapter 2: Testing](https://cjolowicz.github.io/posts/hypermodern-python-02-testing/)
- [Hypermodern Python Chapter 3: Linting](https://cjolowicz.github.io/posts/hypermodern-python-03-linting/)
- [Hypermodern Python Chapter 4: Typing](https://cjolowicz.github.io/posts/hypermodern-python-04-typing/)
- [Hypermodern Python Chapter 5: Documentation](https://cjolowicz.github.io/posts/hypermodern-python-05-documentation/)
- [Hypermodern Python Chapter 6: CI/CD](https://cjolowicz.github.io/posts/hypermodern-python-06-ci-cd/)
- [How to use black, flake8, isort, and pre-commit framework to format Python codes](http://www.sefidian.com/2021/08/03/how-to-use-black-flake8-and-isort-to-format-python-codes/)
- [AsyncIO Complete Walkthough - RealPython Tutorial](https://realpython.com/async-io-python/)
- [Logging HOWTO - Python Docs](https://docs.python.org/3/howto/logging.html)
- [Logging in Python](https://realpython.com/python-logging/)

### 4.2. Tools

- ! [pyenv](https://github.com/pyenv/pyenv) - python version manager
- [poetry](https://python-poetry.org/docs/#system-requirements) - python-specific dependency management and packaging
- [mambaforge](https://mamba.readthedocs.io/en/latest/installation.html) - reimplementation of the conda package manager in C++, part of a bigger ecosystem to make scientific packaging more sustainabl
  - [miniconda](https://docs.conda.io/en/latest/miniconda.html) - package dependency management for any langauge
- [asyncio](https://docs.python.org/3/library/asyncio.html) - write concurrent IO-bound network code using async/await syntax, use with Python asynchronous frameworks
- [logging](https://docs.python.org/3/library/logging.html) - write logging messages correctly and concisely, part of Python's standard library

### 4.3. Formatting

- [black](https://github.com/psf/black) - python uncompromising code formatter
- [flake8](https://flake8.pycqa.org/en/latest/) - python code linter (comments, docstrings, etc.)
  - [flake8-import-order](https://pypi.org/project/flake8-import-order/) - checks the ordering of your imports
  - [flake8-bugbear](https://github.com/PyCQA/flake8-bugbear) - find more bugs and design problems
  - [flake8-bandit](https://github.com/tylerwince/flake8-bandit) - find common security issues in python code
  - [flake8-black](https://github.com/peterjc/flake8-black) - run black for checking Python coding style (If you are using `pre-commit` configure it to call black and/or flake8 directly - you do not need `flake8-black` at all)
  - [flake8-docstring](https://github.com/PyCQA/flake8-docstrings) - pydocstyle and flake8 for combined linting and reporting
  - [darglint](https://github.com/terrencepreilly/darglint) - functional docstring linter which checks whether a docstring's description matches the actual function/method implementation (expects docstrings to be formatted using the Google, Sphinx, or Numpy style guide) (can pull configuration from Flake8)
- [Google Python Style Guide](https://google.github.io/styleguide/pyguide.html) - rules by Google
- [Sphinx](https://www.sphinx-doc.org/en/master/) - python documentation generator
- ! [safety](https://github.com/pyupio/safety) - checks dependencies for known security vulnerabilities
- ! [isort](https://github.com/PyCQA/isort) - python, isort your imports, so you don’t have to
- [pyright](https://github.com/microsoft/pyright) - Microsoft, static type checker for python

### 4.4. Testing

- [pytest](https://docs.pytest.org/en/7.1.x/) - testing framework
- [nox](https://nox.thea.codes/en/stable/) - automates testing in multiple Python environments
  - [nox-poetry](https://github.com/cjolowicz/nox-poetry) - use poetry inside Nox sessions

