---
layout: page
title: Home
id: home
permalink: /
---
# 선택과목 미리보기
[[확률과 통계 미리보기]]&nbsp;&nbsp;&nbsp;&nbsp;[[미적분 미리보기]]
<a href="https://cheonantest.netlify.app/" target="_self">천안 고등 기출 정리</a>

***
# 수학2
### 시험 문제 다시보기

<table border="1">
<th>3차고사</th> <th>4차고사</th> 
  <tr>
    <td class="tg-0 lax"><a href="/pdf/2023%20test/%5B풀이%5D%202023%20청수%20고2%203차고사.pdf">[풀이] 2023 청수 고2 3차고사</a></td>
    <td class="tg-0 lax"><a href="https://mathpractice.netlify.app/cs4" target="_self">[풀이] 2023 청수 고2 4차고사</a></td>
  </tr>
  </table>


[[수학2 교과서 정리]] &nbsp;&nbsp;&nbsp;&nbsp;[[수학2 실전문제 정리]]

***
# 수학1
### 시험 문제 다시보기
<table border="1">
<th>1차고사</th> <th>2차고사</th> 
  <tr>
    <td class="tg-0lax"><a href="/pdf/2023 test/%5B풀이%5D%202023%20청수%20고2%201차고사.pdf">[풀이] 2023 청수 고2 1차고사</a></td>
    <td class="tg-0lax"><a href="/pdf/2023 test/[풀이] 2023 청수 고2 2차고사.pdf">[풀이] 2023 청수 고2 2차고사</a></td>
  </tr>
  </table>

### 수업 내용 정리

[[수학1 교과서 정리]] &nbsp;&nbsp;&nbsp;&nbsp;[[수학1 판서 정리]]

[[수업 중 질문 답변]] &nbsp;&nbsp;&nbsp;&nbsp;[[수학1 중단원 대단원 판서]]


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
