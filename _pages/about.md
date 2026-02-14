---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am an Assistant Professor of Finance at Durham University Business School. I obtained my Ph.D. in Financial Economics from Goethe University Frankfurt in April 2023.
<br>
<br>


Research Interests
======

- Financial Technology
- Blockchain Economics, Decentralized Finance
- Corporate Finance, Corporate Governance
- Data Science, Machine Learning, Artificial Intelligence (AI)
<br>
<br>



Publications
======

{% include base_path %}

{%- comment -%}
Working papers first (assumes category key is "manuscripts").
Everything else goes under "Publications".
{%- endcomment -%}

{%- assign wp_key = "manuscripts" -%}

{%- comment -%}Working papers{%- endcomment -%}
{%- for post in site.publications reversed -%}
  {%- if post.category == wp_key -%}
    {%- include archive-single.html -%}
  {%- endif -%}
{%- endfor -%}

<br>
<br>


Working Papers
======
{%- comment -%}All other categories{%- endcomment -%}
{%- for post in site.publications reversed -%}
  {%- if post.category != wp_key -%}
    {%- include archive-single.html -%}
  {%- endif -%}
{%- endfor -%}









