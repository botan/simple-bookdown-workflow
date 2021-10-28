# Simple Bookdown Workflow

1. Create a bookdown project in Rstudio
2. Run `usethis::use_git()` without committing
3. Delete unnecessary parts in `_output.yml` file
4. Add `output_dir: "docs"` in `_bookdown.yml` file
5. Build the book at least for once
6. Add `_bookdown_files` in `.gitignore`
7. Make your initial commit
9. Run `usethis::use_github()`
10. Build book
11. Commit and push
12. Set **Source** to `main /docs` in **Pages**
13. Update index.Rmd



