---
layout: default
title: Tools
---

{:class="table table-bordered"}
|Name|Type|Category|
|---|---|---|
|"Name..."|... is a "type" tool ...|... that supports test within "category"|
{% for tool in site.tools -%}
{% if tool.name -%}
|[{{ tool.name }}]({{ tool.url }})|{{ tool.type }}|{{ tool.category }}|
{% endif %}
{%- endfor -%}
{:.table-striped}