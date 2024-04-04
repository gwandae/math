---
layout: page
title: Home
id: home
permalink: /
---

# 확률과 통계

[[확통 교과서 정리]] &nbsp;&nbsp;&nbsp;&nbsp; [[확통 프린트 정리]] 

[[확통 중단원 대단원 부교재]] &nbsp;&nbsp;&nbsp;&nbsp; 

---
# 기하와 벡터

[[기하 수행평가 공지]]

[[기하 교과서 정리]] &nbsp;&nbsp;&nbsp;&nbsp; [[기하 프린트 정리]] 

---

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
