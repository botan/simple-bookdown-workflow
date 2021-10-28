# Simple Bookdown Workflow

1. Create a bookdown project in Rstudio
2. Run `usethis::use_git()`
3. Set `repo` and delete unnecessary parts in `_output.yml`
5. Add `output_dir: "docs"` in `_bookdown.yml` file
6. Add `_bookdown_files` in `.gitignore`
7. Build book
8. Commit all changes
9. Run `usethis::use_github()`
10. Set **Source** to `main /docs` in **Pages**



