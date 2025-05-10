{{ with .Page.Resources.GetMatch "*.pdf" }}
- [pdf]({{ .Permalink }})
{{ end }}