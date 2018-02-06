---
layout: post
comments: true
title: 안녕하세요?
---

안녕하세요?
테스트중입니다.

["jekyll 가이드"](https://jekyllrb.com/docs/posts/)

"kramdown 가이드"](https://kramdown.gettalong.org/syntax.html)


##이게 h2인가##

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

이렇게하면 뭐가 나오나??
오 전체 포스트 목록이 나오네!!!

짱이다...

이건 테이블?

|-----------------+------------+-----------------+----------------|
| Default aligned |Left aligned| Center aligned  | Right aligned  |
|-----------------|:-----------|:---------------:|---------------:|
| First body part |Second cell | Third cell      | fourth cell    |
| Second line     |foo         | **strong**      | baz            |
| Third line      |quux        | baz             | bar            |
|-----------------+------------+-----------------+----------------|
| Second body     |            |                 |                |
| 2 line          |            |                 |                |
|=================+============+=================+================|
| Footer row      |            |                 |                |
|-----------------+------------+-----------------+----------------|
