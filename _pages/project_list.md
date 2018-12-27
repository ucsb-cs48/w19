---
title: Project
permalink: "/project_list/"
---

# {{site.course}}, {{site.quarter}}

# Projects:

<ul>
    {%- for p in site.project -%}
        {%- if p.num -%}
	{%- elsif p.title -%}
          <li><a href="{{p.url | relative_url}}">{{p.title}}</a></li>	
	{%- endif -%}
    {%- endfor -%}
</ul>

{% include project_table.html %}

