+++
title = "Glossario"
date = "2021-08-06"
aliases = ["glossary"]
[ author ]
  name = "Hugo Authors"
+++

Qui verrà un semplice glossario!

{{ range .Site.Data.countries.continent.africa.country }}
  <li>
    <input class="material-icons" type="checkbox" />
    <label>{{ .name }}</label>
    </input>
  </li>
{{ end }}