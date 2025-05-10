{{ with .Page.Params.doi }}
- [DOI: {{ . }}](https://doi.org/{{ . }})
{{ end }}
