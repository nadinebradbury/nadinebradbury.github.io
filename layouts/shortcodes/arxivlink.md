{{ with .Page.Params.arxiv }}
- [arXiv:{{ . }}](https://arxiv.org/abs/{{ . }})
{{ end }}
