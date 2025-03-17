---
layout: page
title: Home
id: home
permalink: /
---

[[타과목 수행평가 정리]]


# 공통수학1

[[최소성취 대비 수업]]

[[수업 ppt 정리]] &nbsp;&nbsp;&nbsp;&nbsp; [[중단원 대단원 풀이]]

[[학습자료 정리]]

<a href ="https://skitter-windscreen-bb9.notion.site/2025-1-1accef6dbe5480cc9d73d26d57d25a4e">4반부터 7반까지 진도 정리 링크</a>

---

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
