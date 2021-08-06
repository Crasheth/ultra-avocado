+++
title = "Glossario"
date = "2021-08-06"
aliases = ["glossary"]
[ author ]
  name = "Hugo Authors"
+++

Qui verrà un semplice glossario!

{{ range .Site.Data.list }}
	<h2>{{ .Acronimo }}</h2>
	<p>{{ .Descrizione }}</p>
{{end}}

