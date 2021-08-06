+++
title = "Glossario"
date = "2021-08-06"
aliases = ["glossary"]
[ author ]
  name = "Hugo Authors"
+++

Qui verrà un semplice glossario!


{{ $dataJ := getJSON "https://tools.learningcontainer.com/sample-json-file.json" }}

{{ $data := getJSON "https://example.org/api" (dict "Authorization" "Bearer abcd")  }}