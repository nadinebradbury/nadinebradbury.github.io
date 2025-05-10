{{ with .Page.Resources.GetMatch "*.pdf" }}
- [slides]({{ .Permalink }})
{{ end }}