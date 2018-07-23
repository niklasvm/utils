# utils
Useful utilities

## Snippets

```{r}
dir.create('~/.R/snippets/',recursive = T,showWarnings = F)
download.file(url = 'https://raw.githubusercontent.com/niklasvm/utils/master/r.snippets',
              destfile = '~/.R/snippets/r.snippets',
              mode = 'wb'
)
# then restart rstudio
````
