---
layout: page
title: Home
id: home
permalink: /
---

# 확률과 통계

<a href="https://share.note.sx/iac0kb2l#a8zydRKqr6q3l80VrlXoLLfweb0+5CNgpYIKe77qV0k" target="_self">통계자료분석 수행평가 안내</a>

<table border="1">
<th>1차고사</th> <th>2차고사</th> 
  <tr>
	<td class="tg-0 lax"><a href="https://mathpractice.netlify.app/csp1" target="_self">[풀이] 2023 청수 확통 1차고사</a></td>
	<td class="tg-0 lax"><a href="https://mathpractice.netlify.app/csg2" target="_self">[풀이] 2023 청수 확통 2차고사</a></td>
  </tr>
  </table>
  

[[확통 교과서 정리]] &nbsp;&nbsp;&nbsp;&nbsp; [[확통 프린트 정리]] 

[[확통 부교재 답 및 오타교정]] &nbsp;&nbsp;&nbsp;&nbsp; 

---
# 기하와 벡터


<table border="1">
<th>1차고사</th> <th>2차고사</th> 
  <tr>
	<td class="tg-0 lax"><a href="https://mathpractice.netlify.app/csg1" target="_self">[풀이] 2023 청수 기하 1차고사</a></td>
  </tr>
  </table>
  

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
