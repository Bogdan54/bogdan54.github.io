---
layout: default
title: "Projects"
permalink: /projects
---
# 🚀 Projects & Personal Work

I maintain and host my own services, including [this website](https://bogdancapitanescu.xyz), a [Nextcloud Instance](https://nextcloud.capitanescu.xyz), a [SearXNG Instance](https://searx.capitanescu.xyz), and an [AudioBookShelf Instance](https://audiobooks.capitanescu.xyz). These currently run on a [cost-efficient VPS](https://alphavps.com), with plans to split workloads between a main VPS offsite and home servers for improved reliability and learning opportunities.

I also develop automation and data analysis tools using **Python**, such as:  
- [Wikipedia Scraper](https://github.com/Bogdan54/Scrape-Wikipedia-in-Python-and-Beautiful-Soup-and-HTML5Lib.git) – for extracting structured information efficiently.  

**Skills gained:** automation, data analysis, logical problem-solving, and practical experience bridging software and simple electronics projects.

---

## My GitHub Projects

Below are some of my recent repositories, including short descriptions, full README pages, and links to GitHub:


{% for repo in site.data.projects %}
- [{{ repo.name }}]({{ repo.url }}) – {{ repo.description }}
{% endfor %}