+++
title = "Glossario"
date = "2021-08-06"
aliases = ["glossary"]
[ author ]
  name = "Hugo Authors"
+++

Qui verrà un semplice glossario!

<div>Short Description of {{.Site.Data.glossary}}: <p>{{ index .Site.Data.grlossary "glossary" | markdownify }}</p></div>