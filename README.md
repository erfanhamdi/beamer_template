# MESharif
Beamer theme for ME@Sharif - Mechanical Engineering department of Sharif University of Technology

## Logo
The logo in the lower right corner can be removed from a specific `frame` using the macro `\hidelogo` outside of the `frame` like this:
```LaTeX
\hidelogo
\begin{frame}
    ...
\end{frame}
```
Use `\showlogo` in the same manner to make the logo appear again.

## Section page
The command `\SectionPage` inserts a `[NoFrameNumbering, plain]` frame with yellow background issuing the `\sectionpage` command.
The command `\SectionPage` is used outside of a `frame`, unlike `\sectionpage`.

## Enumerated references
The command `\enumref` inserts a reference to an enumerated item in the shape of a yellow box, like the ones used in the `enumerate` environment.

## Options
Options are given as
```LaTeX
\usetheme[option]{OsloMet}
```

### Widescreen
By default, `beamer` uses the aspect ratio 4:3. You can change this to 16:9 with the option `widescreen`.

### Font
By default, almost all text is typeset in a sans serif. The option `MathSerif` enables serifs for mathematical symbols, whereas `Serif` enables serifs for all text.

### Numbered environments
By default, the environments listed below are unnumbered. The option `numbered` adds numbers, whereas `AMS` adds numbers and typesets the environment names in the style of the American Mathematical Society.

### Title frame
Presentations automatically start with a title frame. This can be disabled with the option `NoTitlePage`.

## Environments
An _environment_ is initialized with
```LaTeX
\begin{environment}
    ...
\end{environment}
```
The following environments are predefined by `beamer`:
* `corollary`
* `definition`
* `definitions`
* `example`
* `examples`
* `fact`
* `lemma`
* `theorem`

In addition, `OsloMet` defines these environments:
* `assumption`
* `axiom`
* `calculation`
* `computation`
* `conjecture`
* `facts`
* `hypothesis`
* `notation`
* `observation`
* `proposition`
* `property`
* `remark`
* `remarks`

## Dependencies
`OsloMet` imports the following packages:
* `babel`
* `beamerposter`
* `beramono`
* `calc`
* `etoolbox`
* `fontenc`
* `gfsneohellenic`
* `thmtools`
* `tikz`

## Credit

OsloMet Beamer Template [link](https://www.overleaf.com/latex/templates/oslomet-beamer-theme/wknwhwkrzvgk)
[![MIT license](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/martinhelso/OsloMet/blob/master/LICENSE)
