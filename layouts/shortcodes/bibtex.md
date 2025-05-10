
{{ with .Page.Resources.GetMatch "*.bib" }}
```BibTeX
{{ .Content }}
```
{{ end }}
