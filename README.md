# Simple Bookdown Workflow

1. Create a bookdown project in Rstudio
1. Run `usethis::use_git()`
1. In `index.Rmd` 
    1. Set `title`
    1. Set `author`
    1. Set `url`
    1. Add `description`
1. In `_output.yml`
    1. Set `repo`
    1. Set `colour`
    1. Delete any output you won't use
1. Add `output_dir: "docs"` in `_bookdown.yml`
1. Add `_bookdown_files` in `.gitignore`
1. In **terminal**
    1. Run `git add .`
    1. Run `git commit -m "Change bookdown defaults"`
1. Build book
1. In **terminal**
    1. Run `git add .`
    1. Run `git commit -m "Build"`
1. Run `usethis::use_github()`
1. Set **Source** to `main /docs` in **Pages**



