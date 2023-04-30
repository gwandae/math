---
layout: page
title: Home
id: home
permalink: /
---
## 시험 문제 다시보기
<table border="1">
<th>문제</th> <th>풀이</th> 
  <tr>
    <td class="tg-0lax"><a href="/pdf/2023 test/2023 청수 고2 1차고사.pdf">2023 청수 고2 1차고사</a></td>
    <td class="tg-0lax"><a href="/pdf/2023 test/%5B풀이%5D%202023%20청수%20고2%201차고사.pdf">[풀이] 2023 청수 고2 1차고사</a></td>
  </tr>
  </table>
# 수업 내용 정리

[[수학1 교과서 정리]] &nbsp;&nbsp;&nbsp;&nbsp;[[수학1 판서 정리]]

[[수업 중 질문 답변]] &nbsp;&nbsp;&nbsp;&nbsp;[[수학1 중단원 대단원 판서]]

[[실전 문제를 연습하고 싶다 → 유형 문제 연습]]

[[이전 단원 기초가 부족하다 → 개념 문제 연습]]


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
