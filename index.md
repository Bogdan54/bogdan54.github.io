---
layout: home
---

**Electronics & Telecommunications Engineer** 

---

## 💼 Experience
-

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

## 📬 Contact
- Email: [bogdan@capitanescu.xyz](mailto:bogdan@capitanescu.xyz)
- GitHub: [github.com/bogdan54](https://github.com/bogdan54)
- LinkedIn: [linkedin.com/in/bogdan54](https://linkedin.com/in/bogdan54)


## 🚀 Latest Projects

{% for repo in site.data.projects limit:5 %}
- [{{ repo.name }}]({{ repo.url }}) – {{ repo.description }}
{% endfor %}

[See all projects →](/projects)

---

## 📝 Latest Posts

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) – {{ post.date | date: "%b %d, %Y" }}
{% endfor %}

---

## 📡 RSS Feed

You can subscribe to my RSS feed: [feed.xml](/feed.xml)

