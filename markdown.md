# markdown 이란? 
  - 텍스트를 서식있는 문서로 쉽게 변환 할 수 있는 마크업 언어.
  - HTML으로 변환하기 쉽게 설계되었다.

 # 마크업 언어란?
  - 텍스트에 태그를 사용하여 문서의 구조와 서식을 정의하는 언어.
  - 문서를 체계적으로 작성하고 읽을 수 있도록 함.(HTML, XML...)

  1. **헤더(Headers)** :

```
    백틱(') <-- 3개 코드라인 markdown 문법이 적용안되는 영역
    # 헤더1
    ## 헤더2
    ###헤더 3
```
## 헤더2

2.굵게

```
    **굵게**
```
**굵게**

3.기울임

```
    *기울임*
```
*기울임*

4.목록
#### 순서가 있는
```
1.첫 번째
2.두 번째
```
1. 첫 번째
2. 두 번째
#### 순서가 없는
```
 - 1
 - 2
 ```
 - 1
 - 2

 5. 링크
 ```
    [링크 텍스트](https://www.naver.com)
```
[네이버로 가기](https://www.naver.com)

6.이미지
```
![이미지 설명](http://~)
```
![영화포스터](![alt text](https://img0.yna.co.kr/etc/inner/KR/2010/12/23/AKR20101223043800005_01_i_P4.jpg))

7. 인용구

```
    > 이것은 인용구 입니다.
     >> 중첩된 인용구 입니다.

8.특정언어의 코드 블록

```python
    print('hi')
```
9.구분선
```---```
---

10.체크박스

``` - [] 할일 - [x] 완료한 일```
 - [ ] 할일
 - [x] 완료한 일

 11.테이블

 | 제목1 | 제목 2|
 |-------|-------|
 | 내용1 | 내용 2 |

 12.이모지 추가하기

 [이모지 검색](https://emojipedia.org)

  - 오늘 날씨는?⛅
  - 오늘 저녁에 🦕!? or 📖

  13.배지 추가
  [배지 추가](https://simpleicons.org)



<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="67" height="20" role="img" aria-label="Python"><title>Python</title><g shape-rendering="crispEdges"><rect width="0" height="20" fill="#555"/><rect x="0" width="67" height="20" fill="#3776ab"/></g><g fill="#fff" text-anchor="middle" font-family="Verdana,Geneva,DejaVu Sans,sans-serif" text-rendering="geometricPrecision" font-size="110"><image x="5" y="3" width="14" height="14" xlink:href="data:image/svg+xml;base64,PHN2ZyBmaWxsPSJ3aGl0ZSIgcm9sZT0iaW1nIiB2aWV3Qm94PSIwIDAgMjQgMjQiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+PHRpdGxlPlB5dGhvbjwvdGl0bGU+PHBhdGggZD0iTTE0LjI1LjE4bC45LjIuNzMuMjYuNTkuMy40NS4zMi4zNC4zNC4yNS4zNC4xNi4zMy4xLjMuMDQuMjYuMDIuMi0uMDEuMTNWOC41bC0uMDUuNjMtLjEzLjU1LS4yMS40Ni0uMjYuMzgtLjMuMzEtLjMzLjI1LS4zNS4xOS0uMzUuMTQtLjMzLjEtLjMuMDctLjI2LjA0LS4yMS4wMkg4Ljc3bC0uNjkuMDUtLjU5LjE0LS41LjIyLS40MS4yNy0uMzMuMzItLjI3LjM1LS4yLjM2LS4xNS4zNy0uMS4zNS0uMDcuMzItLjA0LjI3LS4wMi4yMXYzLjA2SDMuMTdsLS4yMS0uMDMtLjI4LS4wNy0uMzItLjEyLS4zNS0uMTgtLjM2LS4yNi0uMzYtLjM2LS4zNS0uNDYtLjMyLS41OS0uMjgtLjczLS4yMS0uODgtLjE0LTEuMDUtLjA1LTEuMjMuMDYtMS4yMi4xNi0xLjA0LjI0LS44Ny4zMi0uNzEuMzYtLjU3LjQtLjQ0LjQyLS4zMy40Mi0uMjQuNC0uMTYuMzYtLjEuMzItLjA1LjI0LS4wMWguMTZsLjA2LjAxaDguMTZ2LS44M0g2LjE4bC0uMDEtMi43NS0uMDItLjM3LjA1LS4zNC4xMS0uMzEuMTctLjI4LjI1LS4yNi4zMS0uMjMuMzgtLjIuNDQtLjE4LjUxLS4xNS41OC0uMTIuNjQtLjEuNzEtLjA2Ljc3LS4wNC44NC0uMDIgMS4yNy4wNXptLTYuMyAxLjk4bC0uMjMuMzMtLjA4LjQxLjA4LjQxLjIzLjM0LjMzLjIyLjQxLjA5LjQxLS4wOS4zMy0uMjIuMjMtLjM0LjA4LS40MS0uMDgtLjQxLS4yMy0uMzMtLjMzLS4yMi0uNDEtLjA5LS40MS4wOXptMTMuMDkgMy45NWwuMjguMDYuMzIuMTIuMzUuMTguMzYuMjcuMzYuMzUuMzUuNDcuMzIuNTkuMjguNzMuMjEuODguMTQgMS4wNC4wNSAxLjIzLS4wNiAxLjIzLS4xNiAxLjA0LS4yNC44Ni0uMzIuNzEtLjM2LjU3LS40LjQ1LS40Mi4zMy0uNDIuMjQtLjQuMTYtLjM2LjA5LS4zMi4wNS0uMjQuMDItLjE2LS4wMWgtOC4yMnYuODJoNS44NGwuMDEgMi43Ni4wMi4zNi0uMDUuMzQtLjExLjMxLS4xNy4yOS0uMjUuMjUtLjMxLjI0LS4zOC4yLS40NC4xNy0uNTEuMTUtLjU4LjEzLS42NC4wOS0uNzEuMDctLjc3LjA0LS44NC4wMS0xLjI3LS4wNC0xLjA3LS4xNC0uOS0uMi0uNzMtLjI1LS41OS0uMy0uNDUtLjMzLS4zNC0uMzQtLjI1LS4zNC0uMTYtLjMzLS4xLS4zLS4wNC0uMjUtLjAyLS4yLjAxLS4xM3YtNS4zNGwuMDUtLjY0LjEzLS41NC4yMS0uNDYuMjYtLjM4LjMtLjMyLjMzLS4yNC4zNS0uMi4zNS0uMTQuMzMtLjEuMy0uMDYuMjYtLjA0LjIxLS4wMi4xMy0uMDFoNS44NGwuNjktLjA1LjU5LS4xNC41LS4yMS40MS0uMjguMzMtLjMyLjI3LS4zNS4yLS4zNi4xNS0uMzYuMS0uMzUuMDctLjMyLjA0LS4yOC4wMi0uMjFWNi4wN2gyLjA5bC4xNC4wMXptLTYuNDcgMTQuMjVsLS4yMy4zMy0uMDguNDEuMDguNDEuMjMuMzMuMzMuMjMuNDEuMDguNDEtLjA4LjMzLS4yMy4yMy0uMzMuMDgtLjQxLS4wOC0uNDEtLjIzLS4zMy0uMzMtLjIzLS40MS0uMDgtLjQxLjA4eiIvPjwvc3ZnPg=="/><text x="425" y="140" transform="scale(.1)" fill="#fff" textLength="390">Python</text></g></svg>
<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="85" height="20" role="img" aria-label="JavaScript"><title>JavaScript</title><g shape-rendering="crispEdges"><rect width="0" height="20" fill="#555"/><rect x="0" width="85" height="20" fill="#f7df1e"/></g><g fill="#fff" text-anchor="middle" font-family="Verdana,Geneva,DejaVu Sans,sans-serif" text-rendering="geometricPrecision" font-size="110"><image x="5" y="3" width="14" height="14" xlink:href="data:image/svg+xml;base64,PHN2ZyBmaWxsPSJ3aGl0ZSIgcm9sZT0iaW1nIiB2aWV3Qm94PSIwIDAgMjQgMjQiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+PHRpdGxlPkphdmFTY3JpcHQ8L3RpdGxlPjxwYXRoIGQ9Ik0wIDBoMjR2MjRIMFYwem0yMi4wMzQgMTguMjc2Yy0uMTc1LTEuMDk1LS44ODgtMi4wMTUtMy4wMDMtMi44NzMtLjczNi0uMzQ1LTEuNTU0LS41ODUtMS43OTctMS4xNC0uMDkxLS4zMy0uMTA1LS41MS0uMDQ2LS43MDUuMTUtLjY0Ni45MTUtLjg0IDEuNTE1LS42Ni4zOS4xMi43NS40Mi45NzYuOSAxLjAzNC0uNjc2IDEuMDM0LS42NzYgMS43NTUtMS4xMjUtLjI3LS40Mi0uNDA0LS42MDEtLjU4Ni0uNzgtLjYzLS43MDUtMS40NjktMS4wNjUtMi44MzQtMS4wMzRsLS43MDUuMDg5Yy0uNjc2LjE2NS0xLjMyLjUyNS0xLjcxIDEuMDA1LTEuMTQgMS4yOTEtLjgxMSAzLjU0MS41NjkgNC40NzEgMS4zNjUgMS4wMiAzLjM2MSAxLjI0NCAzLjYxNiAyLjIwNS4yNCAxLjE3LS44NyAxLjU0NS0xLjk2NiAxLjQxLS44MTEtLjE4LTEuMjYtLjU4Ni0xLjc1NS0xLjMzNmwtMS44MyAxLjA1MWMuMjEuNDguNDUuNjg5LjgxIDEuMTA5IDEuNzQgMS43NTYgNi4wOSAxLjY2NiA2Ljg3MS0xLjAwNC4wMjktLjA5LjI0LS43MDUuMDc0LTEuNjVsLjA0Ni4wNjd6bS04Ljk4My03LjI0NWgtMi4yNDhjMCAxLjkzOC0uMDA5IDMuODY0LS4wMDkgNS44MDUgMCAxLjIzMi4wNjMgMi4zNjMtLjEzOCAyLjcxMS0uMzMuNjg5LTEuMTguNjAxLTEuNTY2LjQ4LS4zOTYtLjE5Ni0uNTk3LS40NjYtLjgzLS44NTUtLjA2My0uMTA1LS4xMS0uMTk2LS4xMjctLjE5NmwtMS44MjUgMS4xMjVjLjMwNS42My43NSAxLjE3MiAxLjMyNCAxLjUxNy44NTUuNTEgMi4wMDQuNjc1IDMuMjA3LjQwNS43ODMtLjIyNiAxLjQ1OC0uNjkxIDEuODExLTEuNDExLjUxLS45My40MDItMi4wNy4zOTctMy4zNDYuMDEyLTIuMDU0IDAtNC4xMDkgMC02LjE3OWwuMDA0LS4wNTZ6Ii8+PC9zdmc+"/><text x="515" y="140" transform="scale(.1)" fill="#333" textLength="570">JavaScript</text></g></svg>
