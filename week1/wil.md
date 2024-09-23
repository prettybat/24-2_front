
# html에 대해 알아보자


## html의 탄생
텍스트 기반의 정보를 인터넷에서 쉽게 검색 교환하기 위해 '팀 버너스리'가 양식을 통일함 -> html 탄생

## html 뜻

Hyper Text Markup Language

* hyper    넘어서
* text     하이퍼텍스트는 링크를 사용해 텍스트를 통해 다른 페이지로 넘어갈 수 있음
* markup   태그를 사용해서 구조적인 문서를 만듬
* language 마크업 언어는 구조적이고 텍스트 외에 의미를 부여

### tag 예시

<!DOCTYPE html>             html5로 작성된 문서라는 의미
<html>                     html 문서 내용

<head>                      브라우저가 사용하는 정보

<title>Hello</title>        문서의 제목은 Hello
 </head>

<body>                      사용자가 보는 정보

<h1>신짱구

(h1 heading 1) </h1>                

<p>안녕하세요. 전 떡잎마을에      
사는 신짱구입니다. 5살이예요.</p>
p paragraph 

<h2>                        
 가족 관계 

(h2 heading 2)

</h2>

<p>엄마, 아빠, 저, 동생,         
그리고 흰동이와 함께 살아요.</p>(p paragraph)
</body>


</html>

### hypertext 예시
<!DOCTYPE html>
 <html lang="ko">
 <head>

<title>Father</title>
 </head>

<body>

<h1>아빠 : 신형만</h1>

<p>여우같은 아내, 토끼같은 자식, 강아지를 위해 일하는 가장</p>
 <p>35세. 180cm A형</p>

<p>회사원 - 떡잎상사 영업2과 계장</p>

<p>특기 - 발냄새 공격</p>

</body>
 </html>

---
 
### a 태그를 사용해 링크를 걸기
---
<p>엄마,<a href="/father.html">아빠</a>,저,동생, 그리고 흰둥이와 함께 살아요


## 웹문서란 무엇일까

* 페이지가 거미줄처럼 연결되어 a태그만 함께라면 다르 문서로 계속 넘어갈 수 있음
-> 목차의 중요성

### 목차

목차 페이지는 '첫 시작점'
따라서 index.html 페이지는 생략됨

ex) google.com == google.com/index.html
    naver.com == naver.com/index.html