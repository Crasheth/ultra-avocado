+++
title = "Glossario"
date = "2021-08-06"
aliases = ["glossary"]
[ author ]
  name = "Hugo Authors"
+++

Qui verrà un semplice glossario!

{{ range $.Site.Data.glossary.list }}
  
{{ end }}

<p>{{ index .Site.Data.glossary "Short Description" | markdownify }}</p>