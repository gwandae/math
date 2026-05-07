---
layout: page
title: Home
id: home
permalink: /
---

# 온양여고 공통수학 1 정리

[[10. 고차방정식 모고]]



---

---


[[index4|2025 청수 고1 수업 정리]]

[[index3|2024 청수 기하, 확통 수업 정리]]

[[index2|2023 청수 고2 수업 정리]]

<strong>최근 업데이트된 노트</strong>

<ul>
  {% assign recent_notes = site.notes | sort: "last_modified_at_timestamp" | reverse %}
  {% for note in recent_notes limit: 3 %}
    <li>
      {{ note.last_modified_at | date: "%Y-%m-%d" }} — <a class="internal-link" href="{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>

<style>
  .wrapper {
    max-width: 46em;
  }
</style>
