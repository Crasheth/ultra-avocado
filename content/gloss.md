+++
title = "Glossario"
date = "2021-08-06"
aliases = ["glossary"]
[ author ]
  name = "Hugo Authors"
+++

Qui verrà un semplice glossario!
<table>
<thead><tr><th>Termine</th><th>Descrizione</th></tr></thead>
<tbody>
{% assign gs = site.data.glossary | sort:[0] %}
{% for kv in gs %}
<tr> <td>{{ kv[0] }} </td><td> {{ kv[1] }} </td></tr>
{% endfor %}
</tbody>
