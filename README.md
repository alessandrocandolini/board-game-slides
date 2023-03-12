[![CI](https://github.com/alessandrocandolini/board-game-slides/actions/workflows/ci.yml/badge.svg)](https://github.com/alessandrocandolini/board-game-slides/actions/workflows/ci.yml)

# board-game-slides

Companion slides of https://github.com/alessandrocandolini/haskell-player-board

## Run

From the root of the project, assuming a Latex2e distribution is available in the system, the slides can be compiled using

```bash
pdflatex board-game-slides.tex
```

To install latex with nix:
```bash
nix-shell -p texlive.combined.scheme-full
```
