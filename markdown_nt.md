#  markdown  문법 필기

## heading

* h1-> `#`  -> html <h1>내용물</h1>
* h2 -> `##`
* h3 -> `###`
* h4 -> `####`
* h5 -> `#####`
* h6 -> `######`

= html에 들어갈 기본문법

= `ctrl` + 숫자



## list

### unordered list

*/-  : 개요에 보여지지 않음

* a
  * b
    * c
      * d
        * e
          * f

`<ul></ul>`

### ordered list 

숫자 + .

1. 순서가 있는 리스트 1
2. 순서가 있는 리스트 2
   1. 순서가 있는 리스트 2-1

`<ol></ol>`



## text style

### bold

`**`글자`**`

`ctrl`+`b`

​	ex) 안녕하세요 **권소희**입니다.

### italic 

`*`기울기`*`

`ctrl`+`i`

​	ex) 안녕하세요 *권소희*입니다.



* bold + italic : `***` 글자`***` 
  * 안녕하세요 ***서울 8반***입니다.



## hyperlink

### link

`[이름](링크)`

[google](http://www.google.com)

[네이버](http://www.naver.com/)

### img

`![대체 텍스트](이미지링크)

![잔망루피](C:\Users\SSAFY\Desktop\TIL\assets\images.jpeg)

1. 이미지 크기 조절 불가
2. 이미지가 잘 안보이는 경우가 많아 대체 텍스트 투입
   * 이유 : 경로가 폴더 안에 없어서.



## Code Block

### inline code block

빽킷을 활용하여 인라인 코드 생성 가능

글1, 글2, 글3, `코드1` 

### code block

빽킷 세 번 치고 엔터 -> 언어 선택하기

```java
// TIL/introl.java
class Sample{
    public static void main(String args[]){
        system.out.println("Hello, World!");
    }
}
```



## Table

bar를 이용(|)

| 이름 | 학년 | 기수 | 전공 | 연락처 |
| :--: | :--: | :--: | :--: | ------ |
|      |      |      |      |        |
|      |      |      |      |        |
|      |      |      |      |        |
|      |      |      |      |        |
|      |      |      |      |        |

