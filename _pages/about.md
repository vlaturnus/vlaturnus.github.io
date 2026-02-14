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


# Research Interests

- Financial Technology
- Blockchain Economics, Decentralized Finance
- Corporate Finance, Corporate Governance
- Data Science, Machine Learning, Artificial Intelligence (AI)
<br>
<br>



# Publications

{% include base_path %}

{% if site.publication_category %}
  {% for category in site.publication_category  %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        <h2>{{ category[1].title }}</h2><hr />
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %}



Published Papers
======

<strong style="color: #007acc; font-weight: bold;">
  Conflicted Analysts and Initial Coin Offerings
</strong>  
(with <span style="text-decoration: underline; color: #4e555b;">Andreas Barth</span>, <span style="text-decoration: underline; color: #4e555b;">Sasan Mansouri</span>, and <span style="text-decoration: underline; color: #4e555b;">Alexander F. Wagner</span>),  
<i>Management Science</i>, Vol. 69, No. 11 (2023), pp. 6417–7150.
<br>

<strong style="color: #007acc; font-weight: bold;">
  Conflicts of Interest and Market Failures in Unregulated Capital Markets: Evidence from ICO Analysts
</strong>  
(with <span style="text-decoration: underline; color: #4e555b;">Andreas Barth</span>, <span style="text-decoration: underline; color: #4e555b;">Sasan Mansouri</span>, and <span style="text-decoration: underline; color: #4e555b;">Alexander F. Wagner</span>),  
Chapter in <i>Blockchain Scholars Book</i>, Forthcoming, edited by Daniel Liebau and Simon Trimborn, Springer Nature.



Working Papers
======

<strong style="color: #007acc; font-weight: bold;">
  Financial Market Misconduct and Public Enforcement: The Case of Cum-Ex Trading
</strong>  
(with <a href="https://www.old.wiwi.uni-frankfurt.de/abteilungen/finance/lehrstuhl/prof-dr-mark-wahrenburg/team/prof-dr-wahrenburg.html" style="text-decoration: underline; color: #4e555b;">Mark Wahrenburg</a>), 2024.  
Media: <a href="https://www.bloomberg.com/news/articles/2023-05-05/finland-s-missing-millions-show-traders-are-still-exploiting-tax?embedded-checkout=true">Bloomberg</a>
<br>

<strong style="color: #007acc; font-weight: bold;">
  How Do Shareholder Defaults Influence Corporate Governance in DeFi Lending?
</strong>  
(with <a href="https://www.timcrypto.com/" style="text-decoration: underline; color: #4e555b;">Le (Tim) Dong</a> and <a href="https://scholar.google.com/citations?user=7yWh0ucAAAAJ&hl=de" style="text-decoration: underline; color: #4e555b;">Hao Zhang</a>), 2025.
<br>

<strong style="color: #007acc; font-weight: bold;">
  Credit Cycles in Tokenized Real Estate Markets
</strong>  
(with <a href="https://sites.google.com/view/daniel-ruf" style="text-decoration: underline; color: #4e555b;">Daniel Ruf</a> and <a href="https://scholar.google.com/citations?user=LsaCmFgAAAAJ&hl=en" style="text-decoration: underline; color: #4e555b;">Wenqian Huang</a>), 2025.
<br>

<strong style="color: #007acc; font-weight: bold;">
  The Market for Corporate Control in DeFi
</strong>  
(with <a href="https://michelefabi.com/" style="text-decoration: underline; color: #4e555b;">Michele Fabi</a> and <a href="https://scholar.google.com/citations?user=Mnhti80AAAAJ&hl=fr" style="text-decoration: underline; color: #4e555b;">Romain Rossello</a>), 2025.
<br>

<strong style="color: #007acc; font-weight: bold;">
  The Economics of Decentralized Autonomous Organizations</strong>, 2023.  
Media: <a href="https://www.youtube.com/watch?v=QZyDRweEl1w">YouTube</a>
<br><br>






