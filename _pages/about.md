---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am an Assistant Professor of Finance at Durham University Business School. 
# This is the front page of a website that is powered by the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the repository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. Incidentally, these same features make it a great template for anyone that needs to show off a professional template!

# You can fork [this template](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and Markdown files, add your own PDFs and other content, and have your own site for free, with no ads!

Working Papers
======
Financial Market Misconduct and Public Enforcement: The Case of Cum-Ex Trading'' (with [Mark Wahrenburg](https://www.old.wiwi.uni-frankfurt.de/abteilungen/finance/lehrstuhl/prof-dr-mark-wahrenburg/team/prof-dr-wahrenburg.html)), 2024.
Media: [Bloomberg](https://www.bloomberg.com/news/articles/2023-05-05/finland-s-missing-millions-show-traders-are-still-exploiting-tax?embedded-checkout=true)

How Do Shareholder Defaults Influence Corporate Governance in DeFi lending?'' (with [Le (Tim) Dong](https://www.timcrypto.com/) and [Hao Zhang]([https://pages.github.com/](https://scholar.google.com/citations?user=7yWh0ucAAAAJ&hl=de))), 2025.

Credit Cycles in Tokenized Real Estate Markets (with [Daniel Ruf](https://sites.google.com/view/daniel-ruf) and [Wenqian Huang](https://scholar.google.com/citations?user=LsaCmFgAAAAJ&hl=en)), 2025.

The Market for Corporate Control in DeFi'' (with [Michele Fabi](https://michelefabi.com/) and [Romain Rossello](https://scholar.google.com/citations?user=Mnhti80AAAAJ&hl=fr)), 2025.

The Economics of Decentralized Autonomous Organizations'', 2023.
Media: [YouTube](https://www.youtube.com/watch?v=QZyDRweEl1w)

# Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured Markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various Markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

# Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your Markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the Markdown files! You can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

# For those users that need more advanced functionality, the template also supports the following popular tools:
# - [MathJax](https://www.mathjax.org/) for mathematical equations
# - [Mermaid](https://mermaid.js.org/) for diagraming
# - [Plotly](https://plotly.com/javascript/) for plotting

Published Papers
======
Conflicted Analysts and Initial Coin Offerings (with Andreas Barth, Sasan Mansouri, and Alexander F. Wagner), Management Science, Vol. 69, No. 11 (2023), pp.6417‑7150

Conflicts of Interest and Market Failures in Unregulated Capital Markets: Evidence from ICO Analysts (with Andreas Barth, Sasan Mansouri, and Alexander F. Wagner), Chapter in Blockchain Scholars Book, Forthcoming, edited by Daniel Liebau and Simon Trimborn, Springer Nature

# Site-wide configuration
# ------
# The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

# Create content & metadata
# ------
# For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

# **Markdown generator**

# The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
# ) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

# How to edit your site's GitHub repository
# ------
# Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

# Example: editing a Markdown file for a talk
# ![Editing a Markdown file for a talk](/images/editing-talk.png)

# For more info
# ------
# More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
