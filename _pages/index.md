---
layout: page
title: Home
id: home
permalink: /
---

# 온양여고 공통수학 1 정리


[[9월 모의고사 대비 1단원 다항식]]


---

[[10. 고차방정식 모고]] &nbsp;&nbsp;&nbsp;&nbsp; [[10. 고차방정식 모고 해설|해설]]

[[11. 일차부등식 모고]] &nbsp;&nbsp;&nbsp;&nbsp; [[11. 일차부등식 모고 해설|해설]]

[[삼차방정식의 근과 계수의 관계 모고]] &nbsp;&nbsp;&nbsp;&nbsp; [[삼차방정식의 근과 계수의 관계 모고 해설]]

[[12. 연립부등식 모고]] &nbsp;&nbsp;&nbsp;&nbsp; [[12. 연립부등식 모고 풀이]]

[[13. 경우의 수 모고]] &nbsp;&nbsp;&nbsp;&nbsp; [[13. 경우의 수 모고 해설]]



# 고급수학

[[고급수학 역행렬 학습지 답안]]

[[고급수학 행렬 수행 문제 답안]]




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
