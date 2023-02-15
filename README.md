# 장영하 포트폴리오 v2023

시작 : _**2023년 02월 15일**_<br/>
종료 : _**2023년**_   gi


## 마크다운 표시

~~ 취소선 ~~  
_이탤릭_  
**두껍게**  
<u>밑줄</u>


## list
1. 순서가 필요한 리스트
1. 순서가 필요한 리스트
    1. 순서가 필요한 목록  (들여쓰기 두번)
    1. 순서가 필요한 목록  (들여쓰기 두번)
1. 순서가 필요한 리스트

- 순서가 필요하지 않는 목록
- 순서가 필요하지 않는 목록
    -순서가 필요하지 않는 목록 (들여쓰기 두번)


## 링크 []()
<a href="하이퍼링크 주소" title="타이틀 명">youngha </a>

[youngha](하이퍼링크 주소 "title")


## 이미지 ! []()
![이미지 이름](링크 주소)

이미지링크일 경우  > [![이미지 이름](링크 주소)](하이퍼링크 주소)


## 인용문
>남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
>(네이버 국어사전)
>> 중첩


## 인라인 코드 강조
css에서 `background` 혹은 `background-image`속성으로 요소에 배경으로 이미지를 삽입할 수 있다. 


 ## 블록 코드 강조 (html, css, javascript, bash, plaintext)

``` html
<a href="하이퍼링크 주소" title="타이틀 명">youngha </a>
```

``` bash
$ git commit -m "study markdown"
```

``` plaintext
$ git commit -m "study markdown" 단순 텍스트일경우
```


## 표

값 | 의미(:센터정렬:) | 기본값(우측정렬:)
-- |:--:|--:
static | 기준없음 | 0
relative| 요소 자신 | x
absolute | 위치상 부모요소 | x
fixed | 뷰포트 | x


## 원시 HTML (Raw HTML)
동해물과  <u>백두산이</u> 마르고 닳도록<br/> 하느님이 보우하사 우리나라 만세


## 수평선 
___

***

---



## git 올리기
TERINAL> BASH
1. git -v
1. git -init
1. git config --global core.autocrlf true
1. git config --global user.name "jang0ha"
1. git config --global user.email "jang0ha@gmail.com"
1. git config --list > q빠져나오기

---여기까지 한번만 하면됨

1. git status
1. git add . 
1. git status (버전관리할 파일 나오겠다)
1. git commit -m "start project"
    1. git log(커밋 로그 확인) > 빠져나오기q
1. git remote add origin 주소
1. git push origin master
