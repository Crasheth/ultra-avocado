+++
title = "Glossario"
date = "2021-08-06"
aliases = ["glossary"]
[ author ]
  name = "Hugo Authors"
+++

Qui verrà un semplice glossario!
<ul>
{{ range .glossary }}
  <li>{{ . }}</li>
{{ end }}
</ul>