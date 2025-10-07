````markdown
# STA302 Final Project — NBA Salary Analysis

Analysis of NBA player salaries using data from  
[Social Power NBA Dataset](https://www.kaggle.com/datasets/noahgift/social-power-nba)

## Files
- `Final_project_code.Rmd` — main R Markdown analysis  
- `nba_final.csv` — dataset  
- `docs/index.html` — rendered HTML report (for GitHub Pages)

## How to Run
```r
install.packages(c("tidyverse","MASS","car","lmtest","broom","rmarkdown"))
rmarkdown::render("Final_project_code.Rmd",
  output_format = "html_document",
  output_file = "index.html",
  output_dir = "docs"
)
````

## View Online

After pushing to GitHub, enable **GitHub Pages** → Branch: `main`, Folder: `/docs`
Then open:
`https://<username>.github.io/<repo-name>/`

## Notes

* Add `.nojekyll` inside `docs/` for GitHub Pages.
* PDF knitting requires `latex_engine: xelatex` and `tinytex`.

```
```

