---
layout: post
title: Markdown 문법
---


# * 제목 Headers

1. 버전1
# h1
## h2
### h3
#### h4
##### h5
###### h6

2. 버전2

h1
===

h2
—

# * 인용 Blockquotes

> 인용문
>> 인용문안의 인용문

# * 코드 블럭 Code Blocks

```
이것은
코드 블럭
입니다
```

~~~
이것은 
코드 블럭
입니다
~~~

# * 인라인 코드 Inline Code Blocks

`인라인 코드 블럭`

# * 강조 Emphasis

*기울여쓰기(italic)*
_기울여쓰기(italic)_

**굵게쓰기(bold)**
__굵게쓰기(bold)__

# * 수평선

---

***

___

# * 링크 Links


1. 인라인 링크

[Google](http://www.google.co.kr “구글”)

2. 참조 링크

[Google][1]
[Naver][2]
[1]: http://google.com/ “구글”
[2]: http://naver.com/ “네이버”

3. URI링크

<http://google.com/>
<example@gmail.com/>

# * 내부 링크 Internal (Anchored) Links

[목차](#index)

# * 리스트 Lists

1. 순서 있는 리스트 Ordered Lists

1. list item 1
1. list item 2
2. list item 3
0. list item 4
3. list item 5

# * 순서 없는 리스트 Unordered Lists

* list item 1
    * list item 1-1
    * list item 1-2
    
+ list item 1
    + list item 1-1
    + list item 1-2

- list item 1
    - list item 1-1
    - list item 1-2

# * 테이블 Tables

1. 테이블 생성

Header 1 | Header 2
--------- | ---------
Content 1 | Content 3
Content 2 | Content 4

2. 테이블 정렬

| Header 1 | Header 2 | Header 3 |
| :-------- | :--------: | --------: |
| Left | Center | Right |

# * 이미지 Adding Images

1. 인라인 이미지

![alt text](/test.png )
# * 각주 Footnotes

2. 링크 이미지

![alt text](image_URL)

3. 참조 이미지

![alt text][1]
[1]: /test.png

각주입니다[^id]
[^id]: 각주에 대한 설명.
