---
layout: page
permalink: /3
---

# 기하와 벡터(2학기)

<table border="1">
<th>3차고사</th> <th>4차고사</th> 
  <tr>
    <td class="tg-0 lax"><a href="/pdf/2024%20test/%5B풀이%5D%202024%20청수%20기하%203차고사.pdf">[풀이] 2024 청수 기하 3차고사</a></td>
    <td class="tg-0 lax"><a href="https://mathpractice.netlify.app/csg4" target="_self">[풀이] 2024 청수 기하 4차고사</a></td>
  </tr>
  </table>

[[기하 교과서 정리]] &nbsp;&nbsp;&nbsp;&nbsp; [[기하 프린트 정리(2학기)]]

---
# 확률과 통계

<table border="1">
<th>1차고사</th> <th>2차고사</th>  <th>3차고사</th>
  <tr>
	<td class="tg-0 lax"><a href="https://mathpractice.netlify.app/csp1" target="_self">[풀이] 2024 청수 확통 1차고사</a></td>
	<td class="tg-0 lax"><a href="">시험 후 공개</a></td>
	<td class="tg-0 lax"><a href="/pdf/2024%20test/%5B풀이%5D%202024%20청수%20확통%203차고사.pdf">[풀이] 2024 청수 확통 3차고사</a></td>
  </tr>
  </table>
  

[[확통 교과서 정리]] &nbsp;&nbsp;&nbsp;&nbsp; [[확통 프린트 정리]] 

[[확통 부교재 답 및 오타교정]] &nbsp;&nbsp;&nbsp;&nbsp; 

---
# 기하와 벡터(1학기)


<table border="1">
<th>1차고사</th> <th>2차고사</th> 
  <tr>
	<td class="tg-0 lax"><a href="https://mathpractice.netlify.app/csg1" target="_self">[풀이] 2024 청수 기하 1차고사</a></td>
	<td class="tg-0 lax"><a href="https://mathpractice.netlify.app/csg2" target="_self">[풀이] 2024 청수 기하 2차고사</a></td>
  </tr>
  </table>

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
