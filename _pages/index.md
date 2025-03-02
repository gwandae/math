---
layout: page
title: Home
id: home
permalink: /
---
<a href="https://www.youtube.com/channel/UCkvgc8fqKkBkfnu30DQiXIQ" target="_self">유튜브 채널</a> 

# 공통수학1

[[수업 ppt 정리]] &nbsp;&nbsp;&nbsp;&nbsp; [[중단원 대단원 풀이]]

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
