# HTML, CSS, JS 기초

## HTML

> HTML : Hyper Text Markup Language - 마크업(표시) 언어 
> 
> 웹페이지의 구조를 표시
> 
> 웹페이지의 콘텐츠를 표현

### HTML Elements

> Element: 요소 - 의미적
> 
> Tag : 태그 - 기술적  

> 문법(Syntax)
> 
> <>로 감싸즘
> 
> 소문자 사용
> 
> 시작태그와 종료태그 세트로 구성됨.
```
<tagname>contents</tagname>
```

> 예외) 시작태그만 존재하는 경우 : 빈 요소(Empty Element)
> 포함 관계(Nested)
```
<body> 
  <div>
    text
  </div>
</body>
```

### HTML Attribute

> HTML 속성
> HTML 요소의 부가 정보
> 속성이름 = "속성값"

```
<a href="http://www.naver.com">naver</a> 
```

### 제목 태그

> heading -> h
> 
> h1~ h6
> 
> h1이 가장 큰 제목


### HTML 기본 구조

```
<!DOCTYPE html> - 1
<html> - 2
  <head> - 3
    <meta charset="utf-8"> - 4
    <title>My test page</title> -5
  </head>
  <body> - 6
    <p>This is my page</p>
  </body>
</html>
```

1. 웹 문서의 버전 : HTML5
2. html 문서의 가장 바깥쪽 요소
3. 웹 문서를 설명하는 정보가 담기는 영역 요소
4. 웹 문서의 정보를 표시하는 요소
5. 웹 문서의 제목을 표시 요소
6. 웹 문서의 콘텐츠 요소들이 담기는 영역 요소

### 단락 태그

> p(Paragraph) : 단락을 표시
>
> 단락과 단락 사이를 구분하는 수평선
```
<hr> - Horizontal Rule
```
> 단락을 구분하지 않고 줄 바꿈
```
<br> - Break 
```
### 목록 태그

> 순서없는 목록 ul(Unordered List)
> 순서있는 목록 ol(Ordered List)
> 목록 항목 li(List Item)

```
<ul>
  <li>HTML</li>
  <li>CSS</li>
</ul>

<ol>
  <li>HTML</li>
  <li>CSS</li>
</ol>
```
> 포함관계(Nested)로 구성된 목록 - 코딩할때 밖에서 안쪽 방향 순서로 
- HTML
  - HTML4
  - HTML5
- CSS
  - CSS2
  - CSS3
```
<ul>
  <li>
  HTML
   <ul>
    <li>HTML4</li>
    <li>HTML5</li>
   </ul>
  </li>
  <li>
  CSS
   <ul>
    <li>CSS2</li>
    <li>CSS3</li>
   </ul>
  </li>
</ul>
```

> 설명목록(Description List) - dl

```
<dl>
  <dt>HTML</dt> (dt : Description Title)
  <dd>표준 마크업 언어</dd> (dd : Description Date)
</dl>
```

### HTML Hyper Link

> 하이퍼링크 a(anchor)
> 
> attribute(속성) : href(Hypertext Reference) : 연결되는 웹 문서의 URL
```
<a href="http://www.naver.com">네이버로 이동</a>
```
> 북마크 기능
>
> 외부 페이지 연결이 아닌 같은 페이지에서 특정위치로 이동할 수 있게 해주는 기능
>
> 도착지점에 id attribute를 사용하여 이름을 지정
```
<a href="#ti"></a>
```
```
<h2 id="t1">제목</h2>
```








