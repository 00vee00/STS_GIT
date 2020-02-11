# 마크다운(MarkDown) 문서
확장자.md 로 된 파일들 >> HTML(H/T/MarkUp/Languages)의 대체기능을 가지고 있다.
1. 장점
   - 간편하고 쉽다.
   - 다양한 플랫폼에서 지원한다.
   - 개처럼써도 HTML으로 찰떡같이 변환해준다.ㅎㅎ
2. 단점
   - 표준이 없다.... (표현매체마다 다르게 보임)
   - 모든 HTML태그를 대체하지는 못한다.

---
# 제목1
## 제목2
### 제목3
#### 제목4
##### 제목5
###### 제목6

# 수평선 (Horizontal Line)
각 기호를 3개 이상 입력
---
___

***
# 줄바꿈(Line Break)
'두번 띄어쓰기'


# 이텔릭, 굵게
이탤릭은 *별표* 사용혹은 _언더바_ 사용
**굵게**<br>
~~취소선~~ 물결표시
<u>밑줄</u> 은 `<u></u>`사용

# 목록
1. 순서가 필요한목록
1. 순서가 필요한목록
1. 순서가 필요한목록
    - 여기도 순서가 필요없는 목록
2. 순서가 필요한목록
3. 순서가 필요한목록
4. 순서가 필요한목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록


# 링크
[GOOGLE](http://google.com)

[GitHub](https://github.com)

# 이미지
![대체텍스트](https://www.w3schools.com/html/pic_trulli.jpg)

# 이미지에 링크걸수있다.
[![대체텍스트](https://www.w3schools.com/html/pic_trulli.jpg)](https://www.naver.com)


# 코드강조
### 인라인 코드강조
`background` 혹은 `background=image` 속성으로 배경이미지 삽입
### 블럭코드강조
`를 3번이상 입력하고 코드 종류도 적습니다.

```html
<a href="https://www.naver.com" target="_blank">네이버<a>


```css
public static void myFunc(int n,String str){
    System.out.println("HELLO BLOCKDOWN")
}

```
# 표(테이블)
`<table>`로 변환

|aa|bb|
|--|--|
|1|2|
|3|4|

### 열병합
|Col1|Col2|Col3|Col4|
|---|---|---|---|
|다음기회에 ㅋㅋㅋ|

<br>

|값|의미|기본값|
|---|:---:|---:|
|static|배치불가|999|
|static|배불치|999999|
|static|배불가|999999999|


# 인용문
남의 말이나 글에서 직접 따온 문장

> 인용문 작성
>> 중첩인용문 작성
>>> 중중첩인용문 작성 ㅎㅎ
