# myTalks
Repository of source for my talks. To clone, run

```
git clone https://github.com/benSepanski/myTalks.git
```

## Building presentations

Some plots are built using [Rstudio](https://rstudio.com/)'s
[Rmarkdown](https://rmarkdown.rstudio.com/https://rmarkdown.rstudio.com/).
Compiling the `*.Rmd` documents using Rstudio should run smoothly.

### Sty files

The following folders hold style files which some presentations rely upon:
* `utcsStyFiles/`

If you run into an error `*.sty not found`, it may be from one of these
folders. You must copy the contents of that folder into the
presentation directory (e.g. `cp -r utcsStyFiles/* 2021-03-25-Nonlocal-UFL-Finite-Elements-for-Helmholtz-equations-with-a-nonlocal-boundary-condition`).

## Contents

* `2019-Cardano-and-the-Cubic-Equation/` A talk given at [Baylor](https://www.baylor.edu/)'s
    Mobius math club and also at [UBC Waco](http://ubcwaco.org/)'s powerpoint nights.
    Presents history of [Cardano](https://en.wikipedia.org/wiki/Gerolamo_Cardano)
    and the [cubic equation](https://en.wikipedia.org/wiki/Cubic_equation).
* `2021-03-25-Nonlocal-UFL-Finite-Elements-for-Helmholtz-equations-with-a-nonlocal-boundary-condition/`
   [This talk](https://bensepanski.github.io/talks/2021-03-25-Nonlocal-UFL-Finite-elements-for-Helmholtz-equations-with-a-nonlocal-boundary-condition)
   given at [FEniCS 2021](https://fenics2021.com/).
* `utcsStyFiles/` Beamer theme copied and modified from [Kevin Song]'s [latex templates](https://gitlab.com/chipbuster/latex-templates)
for [UTCS](https://www.cs.utexas.edu/)
