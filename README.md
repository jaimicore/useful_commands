# useful_commands

&nbsp;

Just a bunch of code that I consider useful and do not remember every time I need it.

&nbsp;

The commands are separated in 3 files, but there are also templates for github actions.

&nbsp;

  1. R_uselful_commands.Rmd : `R`-only commands
  2. Miscellaneous_useful_commands.Rmd :  includes commands for mutlitple tools such as `aws`, `bash`, `jupyter` and other.
  3. python_useful_commands.ipynb : `python`-only commands

## How to run it?

### R commands

```bash
Rscript -e 'library(rmarkdown); rmarkdown::render("R_useful_commands.Rmd", "html_document")'
```

&nbsp;

### Miscellaneous commands

```bash
Rscript -e 'library(rmarkdown); rmarkdown::render("Miscellaneous_useful_commands.Rmd", "html_document")'
```

&nbsp;

### `python` commands

```bash
jupyter nbconvert --to html --TagRemovePreprocessor.remove_cell_tags="hide_input" python_useful_commands.ipynb
```

&nbsp;
