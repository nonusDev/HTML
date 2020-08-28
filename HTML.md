# HTML(Hyper Text Markup Language)

> 웹 페이지를 구조적으로 작성하기 위한 언어

* Hyper Text

  > 참조(hyperlink)를 통해 한 문서에서 다른 문서로 즉시 접근할 수 있는 텍스트

* HTTP(Hyper Text Transfer Protocol)

  > Hyper Text를 주고 받는 규칙

* Markup

  > 태그 등을 이용하여 문서나 데이터의 구조를 명기하는 언어



기본 2space



### HTML 기본 구조

> DOM(Document Object Model) 트리

<img src="HTML.assets/1024px-DOM-model.svg.png" alt="1024px-DOM-model.svg" style="zoom:50%;" />



#### 요소 (Element)

> <여는태그>Contents<닫는태그>

#### 속성(Attribute)

> <여는태그 속성명="속성값"><닫는태그>
>
> 태그별로 사용할 수 있는 속성이 다름



#### head

> 문서 제목, 문자 인코딩 등의 문서 정보를 담고 있음
>
> 메타데이터를 통해 웹 문서에 대한 추가 정보 선언
>
> 외부 파일 연결
>
> CSS 파일 혹은 자바스크립트 파일



메타 데이터를 표현하는 새로운 규약, Open Graph Protocol

> HTML 문서의 메타데이터를 통해 문서의 정보를 전달
>
> 페이스북에서 만들었으며, 메타정보에 해당하는 제목, 설명 등을 쓸 수 있도록 정의

https://metatags.io



#### 시맨틱태그

> HTML5에서 의미론적 요소를 담음 태그의 등장
>
> 개발자 및 사용자 뿐만 아니라 검색엔진 등에 의미 있는 정보의 그룹을 태그로 표현
>
> 단순히 구역을 나누는 것 뿐만 아니라 의미를 가지는 태그들을 활용하기 위한 노력
>
> Non semantic 요소는 div, span 등이 있으며, h1, table 태그 들도 시맨틱 태그로 볼 수 있음
>
> 검색엔진최적화(SEO)를 위하여는 메타태그, 시맨틱트개 등을 통한 마크업을 효과적으로 할 필요가 있음

* header

  > 문서 전체나 섹션의 헤더(머릿말 부분)

* nav

  > 네비게이션

* aside

  > 사이드에 위치한 공간, 메인 콘텐츠와 관련성이 적은 콘텐츠

* section

  > 문서의 일반적인 구분, 컨텐츠의 그룹을 표현

* article

  > 문서, 페이지, 사이트 안에서 독립적으로 구분되는 영역

* footer

  > 문서 전체나 섹션의 푸터(마지막 부분)



#### 인라인 / 블록 요소



#### 그룹 컨텐츠

> p
>
> hr
>
> 목록 ol, ul
>
> pre bloackquote
>
> figure
>
> div



#### 텍스트 관련 요소

> a
>
> b vs strong 강조 strong많이 쓰임
>
> i vs em 기울기?? em 많이 쓰임
>
> span br img
>
> 기타 등등



#### table

> tr td th
>
> thead tbody tfoot
>
> caption
>
> 셀 병합 속성: colspan rowspan
>
> scope 속성
>
> col colgroup



#### from

> form은 서버에서 처리될 데이터를 제공하는 역할
>
> form의 기본 속성
>
> action method



#### 웹 사이트 분석

크롬 웹 스토어에서 'Web Developer' 검색 및 추가



#### MDN

https://developer.mozilla.org/ko/