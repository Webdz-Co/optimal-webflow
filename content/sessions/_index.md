+++
title = "Sessions"
+++
{{ define "title" }}
  {{ .Title }} - {{ .Site.Title }}
{{ end }}
{{ define "main" }}
  {{ partial "sessions.html" . }}
{{ end }}
{{ define "footer" }}
  {{ partial "footer/site-footer.html" . }}
{{ end }}
