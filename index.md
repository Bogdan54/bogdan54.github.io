---
layout: home
---

**Electronics & Telecommunications Engineer** 

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

