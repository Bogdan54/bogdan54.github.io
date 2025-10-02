---
layout: home
title: Bogdan Căpitănescu
---

# Bogdan Căpitănescu
**Electronics & Telecommunications Engineer** 

---

**About Me**  
Driven Electronics and Telecommunications Engineer with a passion for building and automating systems. I maintain my own hosted services, develop Python automation tools, and work on hands-on projects bridging software, networking, and embedded systems. Curious and self-motivated, I enjoy creating practical solutions, optimizing workflows, and continuously learning new technologies.

---

## 🎓 Education
B.Sc. Electronics & Telecommunications Engineering – Politehnica University Timișoara 

---

## 🛠 Skills
- Programming: C, Python, Bash
- DevOps: Git, GitHub Actions, Linux sysadmin
- Hardware: Circuit design, microcontrollers
- Tools: Arch Linux, Jekyll, GitHub Pages

---

## 🚀 Latest Projects

{% for repo in site.data.projects limit:5 %}
- [{{ repo.name }}]({{ repo.url }}) – {{ repo.description }}
{% endfor %}

[See all projects →](/projects)

---

## 💼 Professional Experience
- **Summer Practice Trainee** – Hands-on experience with Linux server administration, sensor testing, process automation, Python programming, and C programming

---

## 📝 Latest Posts

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) – {{ post.date | date: "%b %d, %Y" }}
{% endfor %}

[See all posts →](/blog)

---

## 📡 RSS Feed

You can subscribe to my RSS feed: [feed.xml](/feed.xml)

