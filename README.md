
# Awesome R package development [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/IndrajeetPatil/awesome-r-pkgtools/)

A curated list of awesome tools to assist R 📦 development.

Note before:

-   Not all tools are available on [CRAN](https://cran.r-project.org/);
    some might be available only via GitHub or GitLab.
-   Only **tools** helpful for package development are included, and not
    other resources (like books, talks, presentations, etc.).

If you wish to suggest any additional tools, please make a PR request or
raise an issue here:
<https://github.com/IndrajeetPatil/awesome-r-pkgtools>

Please note that the `awesome-r-pkgtools` project is released with a
[Contributor Code of
Conduct](https://contributor-covenant.org/version/2/0/CODE_OF_CONDUCT.html).
By contributing to this project, you agree to abide by its terms.

# Swiss army knives 🛠

Tools (including their hard dependencies) useful across all stages of
package development.

-   `{devtools}`: <https://devtools.r-lib.org/>

-   `{usethis}`: <https://usethis.r-lib.org/>

-   `{pacs}` : <https://polkas.github.io/pacs/index.html>

# Package skeletons 💀

-   `{pkgkitten}`: <https://dirk.eddelbuettel.com/code/pkgkitten.html>

-   `{rcompendium}`: <https://frbcesab.github.io/rcompendium/>

-   `{fusen}`: <https://thinkr-open.github.io/fusen/>
    (`{rmarkdown}`-based)

-   `{pkgverse}`: <https://pkgverse.mikewk.com/> (for package universe)

# Naming things 🧸

-   `{available}`:
    <https://cran.r-project.org/web/packages/available/index.html> (to
    check if a package name is available to use)

-   `{collidr}`: <https://cran.r-project.org/web/packages/collidr/> (to
    check for namespace collisions)

# Documentation 📚

## Manual

-   `{roxygen2}`: <https://roxygen2.r-lib.org/>

-   `{Rd2roxygen}`:
    <https://cran.r-project.org/web/packages/Rd2roxygen/index.html> (in
    case you inherit a project where documentation was not written using
    `{roxygen2}`)

-   `{sinew}`: <https://yonicd.github.io/sinew/> (generate `{roxygen2}`
    skeletons)

-   `{roclang}`: <https://cran.r-project.org/web/packages/roclang/>
    (helpers for diffusing of content across function documentation)

-   `{Rdpack}`:
    <https://cran.r-project.org/web/packages/Rdpack/index.html> (for
    inserting references, figures, and evaluated examples in Rd docs)

-   `{roxygen2md}`: <https://roxygen2md.r-lib.org/> (using Markdown
    syntax in package documentation)

-   `{rd2list}`: <https://github.com/coolbutuseless/rd2list> (converts
    Rd docs to a human-readable list)

-   `roxygen2Comment`: <https://github.com/csgillespie/roxygen2Comment>
    (Rstudio addin for adding and remove `{roxygen2}` comment)

## Math in manual

-   `{katex}`: <https://docs.ropensci.org/katex/>

-   `{mathjaxr}`:
    <https://cran.r-project.org/web/packages/mathjaxr/index.html>

## Vignettes

-   `{knitr}`: <https://yihui.org/knitr/>

-   `{rmarkdown}`: <https://rmarkdown.rstudio.com/>

-   `{prettydoc}`:
    <https://cran.rstudio.com/web/packages/prettydoc/index.html>
    (creates lightweight yet pretty vignettes)

-   `{learnr}`: <https://rstudio.github.io/learnr/> (interactive
    tutorials)

## Lifecycle

-   `{lifecycle}`: <https://lifecycle.r-lib.org/index.html>

## Website

-   `{pkgdown}`: <https://pkgdown.r-lib.org/> (static website for
    package documentation)

-   `{gitdown}`: <https://github.com/ThinkR-open/gitdown> (software
    changes as a gitbook)

-   `{altdoc}`: <https://altdoc.etiennebacher.com/> (use docute or
    docsify to create a static website for package documentation)

## Badges and stickers

-   `{badger}`:
    <https://cran.r-project.org/web/packages/badger/index.html>

-   `{hexSticker}`:
    <https://cran.r-project.org/web/packages/hexSticker/index.html>

-   `hexwall`: <https://github.com/mitchelloharawild/hexwall> (to create
    a wall of hexstickers)

## Presentation

-   `{xaringan}`: <https://github.com/yihui/xaringan>

# Documentation quality ✒️

-   `{docreview}`: <https://thisisnic.github.io/docreview/> (to check
    quality of docs)

-   `{spelling}`: <https://docs.ropensci.org/spelling/> (to spell check)

-   `{gramr}`: <https://github.com/jasdumas/gramr> (for grammar
    suggestions)

# Unit testing 🧪

-   `{testthat}`: <https://testthat.r-lib.org/>

-   `{vdiffr}`: <https://vdiffr.r-lib.org/> (visual regression testing)

-   `{mockthat}`: <https://nbenn.github.io/mockthat/> (function mocking
    for unit testing to third-party packages)

-   `{roxytest}`: <https://github.com/mikldk/roxytest> (inline
    `{testthat}` tests with `{roxygen2}`)

-   `{exampletestr}`: <https://rorynolan.github.io/exampletestr/> (tests
    based on package examples)

-   `{shinytest}`: <https://rstudio.github.io/shinytest/> (testing Shiny
    apps)

-   `{testdown}`: <https://github.com/ThinkR-open/testdown> (turn
    `{testthat}` results into a `{bookdown}` project)

-   `{autotest}`: <https://docs.ropensci.org/autotest/>

-   `{tinytest}`:
    <https://cran.r-project.org/web/packages/tinytest/index.html>

-   `{testit}`:
    <https://cran.rstudio.com/web/packages/testit/index.html>

-   `{testthis}`: <https://cran.r-project.org/web/packages/testthis/>

-   `{xpectr}`: <https://github.com/LudvigOlsen/xpectr>

-   `{unitizer}`:
    <https://cran.r-project.org/web/packages/unitizer/index.html>

-   `{r-hedgehog}`: <https://github.com/hedgehogqa/r-hedgehog> (property
    based testing)

# Code analysis 🗂⏱

## General

-   `{goodpractice}`: <http://mangothecat.github.io/goodpractice/>
    (Swiss army knife for good practices)

## Code coverage

-   `{covr}`: <https://covr.r-lib.org/> (computes code coverage)

-   `{covrpage}`: <https://yonicd.github.io/covrpage/> (provides summary
    `README` of code coverage and corresponding tests)

## Lint detection

-   `{lintr}`: <https://github.com/jimhester/lintr>

-   `{roger}`:
    <https://cran.r-project.org/web/packages/roger/index.html>

-   `{cleanr}`:
    <https://cran.r-project.org/web/packages/cleanr/index.html>

## Code similarity

-   `{dupree}`: <https://github.com/russHyde/dupree>

## Benchmarking and profiling

-   `{bench}`:
    <https://cran.r-project.org/web/packages/bench/index.html>

-   `{profvis}`:
    <https://cran.r-project.org/web/packages/profvis/index.html>

## Lines of code

-   `{cloc}`: <https://github.com/hrbrmstr/cloc>

# Formatting 🧽

## R code

-   `{styler}`: <https://styler.r-lib.org/> (especially relevant if you
    follow `{tidyverse}` style guide)

-   `{formatR}`: <https://yihui.org/formatr/>

-   `AlignAssign`: <https://github.com/seasmith/AlignAssign> (RStudio
    addin)

## Markdown documents

-   `{stylermd}`: <https://github.com/lorenzwalthert/stylermd>

# Dependencies ⚖️

-   `{deepdep}`:
    <https://cran.r-project.org/web/packages/deepdep/index.html> (to
    visualize and explore package dependencies)

-   `{itdepends}`: <https://github.com/r-lib/itdepends> (to assess
    usage, measure weights, visualize proportions, and assist removal of
    dependencies)

-   `{DependenciesGraphs}`:
    <https://github.com/datastorm-open/DependenciesGraphs> (to visualize
    package dependencies)

-   `{functiondepends}`:
    <https://cran.r-project.org/web/packages/functiondepends/>

-   `{pkgndep}`: <https://cran.r-project.org/web/packages/pkgndep/>
    (checks the heaviness of the packages used)

-   `{oysteR}`: <https://sonatype-nexus-community.github.io/oysteR/>
    (secure package against insecure dependencies)

-   `{attachment}`: <https://github.com/ThinkR-open/attachment>

# CRAN submission and status 📬

-   `{rhub}`: <https://cran.r-project.org/web/packages/rhub/index.html>
    (to run `R CMD check` on CRAN architectures)

-   `{checkhelper}`: <https://thinkr-open.github.io/checkhelper/>
    (submission help)

-   `{foghorn}`:
    <https://cran.r-project.org/web/packages/foghorn/index.html> (check
    results and submission portal status)

-   `{urlchecker}`: <https://github.com/r-lib/urlchecker> (URL checks)

# Usage 🙈

-   `{cranlogs}`: <https://r-hub.github.io/cranlogs/> (computing CRAN
    download counts)

-   `{packageRank}`:
    <https://cran.r-project.org/web/packages/packageRank/index.html>
    (visualizing CRAN download counts)

# CI/CD 📟

CI/CD: continuous integration and either continuous delivery or
continuous deployment

-   `actions`: <https://github.com/r-lib/actions> (for [GitHub
    Actions](https://github.com/features/actions))

-   `r-appveyor`: <https://github.com/krlmlr/r-appveyor> (for
    [AppVeyor](https://www.appveyor.com/))

-   `{tic}`: <https://docs.ropensci.org/tic/> (for [Circle
    CI](https://circleci.com/) and [GitHub
    Actions](https://github.com/features/actions))

# Debugging 🔭

-   `{debugme}`: <https://github.com/r-lib/debugme>

-   `{debugr}`:<https://cran.r-project.org/web/packages/debugr/>

# Input validation 🔬

-   `{checkmate}`: <https://mllg.github.io/checkmate/> (argument checks)

-   `{assertthat}`:
    <https://cran.r-project.org/web/packages/assertthat/index.html>

-   `{assertive}`: <https://www.r-pkg.org/pkg/assertive>

-   `{pkgcond}`: <https://github.com/RDocTaskForce/pkgcond> (better
    error messages for package users)

# Package metadata 🖨

-   `{codemetar}`: <https://docs.ropensci.org/codemetar/>

-   `{pkgapi}`: <https://github.com/r-lib/pkgapi>

-   `{packagemetrics}`: <https://github.com/sfirke/packagemetrics> (for
    comparing among packages)

-   `{devtoolbox}`: <https://martinctc.github.io/devtoolbox/index.html>

-   `{pkgattrs}`: <https://rich-iannone.github.io/pkgattrs/>

-   `{foreman}`: <https://github.com/yonicd/foreman>

-   `{sessioninfo}`: <https://github.com/r-lib/sessioninfo>

# Reverse dependency checks 📡⚰️

-   `{revdepcheck}`: <https://r-lib.github.io/revdepcheck/>

# Docker container 🛍

-   `{containerit}`: <https://o2r.info/containerit/>

-   `{usethat}`: <https://tidylab.github.io/usethat/>

# Gratitude 🙏💌

Thank the contributors or maintainers of packages you rely on.

-   `{thankr}`:
    <https://cran.r-project.org/web/packages/thankr/index.html>

-   `{allcontributors}`: <https://docs.ropensci.org/allcontributors/>

# Integration with other languages 🔗

## C++

-   `{Rcpp}`: <https://cran.r-project.org/web/packages/Rcpp/index.html>

-   `{cpp11}`: <https://cpp11.r-lib.org/index.html>

## Python

-   `{reticulate}`:
    <https://cran.r-project.org/web/packages/reticulate/index.html>

## Rust

-   `{hellorust}`: <https://github.com/r-rust/hellorust>

## .NET Framework

-   `{rClr}`: <https://github.com/rdotnet/rClr>

## JavaScript/HTML/CSS

-   `{htmltools}`:
    <https://rstudio.github.io/htmltools/reference/index.html#section-html-dependencies>
-   `{packer}`: <https://packer.john-coene.com>

## Julia

-   `{JuliaCall}`:
    <https://non-contradiction.github.io/JuliaCall/index.html>

# Sundry 🗒

-   `{TODOr}`: <https://github.com/dokato/todor> (RStudio addin to list
    things that you need to do or change)

-   `{prefixer}`: <https://github.com/dreamRs/prefixer> (prefix function
    with their namespace )

-   `{gitignore}`:
    <https://cran.r-project.org/web/packages/gitignore/index.html> (to
    fetch gitignore templates)

-   `{touchstone}`: <https://lorenzwalthert.github.io/touchstone/>
    (benchmarking pull requests)

-   `{precommit}`: <https://lorenzwalthert.github.io/precommit/>
    (pre-commit hooks)
