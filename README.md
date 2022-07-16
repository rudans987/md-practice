#  마크다운(Markdown)의 문법(사용법)
### 1. 제목(Header)
# 제목1 ```# 제목1 ``` | ```<h1>제목1</h1>```
> ```
> 제목1
> =====
> ```
## 제목2 ```## 제목2 ``` | ```<h2>제목2</h2>```
> ```
> 제목2
> -----
> ```
### 제목3 ```### 제목3 ``` | ```<h3>제목3</h3>```
#### 제목4 ```#### 제목4 ``` | ```<h4>제목4</h4>```
##### 제목5 ```##### 제목5 ``` | ```<h5>제목5</h5>```
###### 제목6 ```###### 제목6 ``` | ```<h6>제목6</h6>```
---

### 2. 강조(Emphasis)
- *이텔릭체* : ```*별표*``` | ```_언더바_```
- **볼드체** : ```**별표**``` | ```__언더바__```
- **_이텔릭체_ & 볼드체** 함께 사용 : ```**_이텔릭체_ & 볼드체**```
- ~~취소선~~ : ```~~물결표시~~```
- `<u>밑줄</u>` : ```<u>밑줄 표현</u>```

---

### 3. 목록(List)
**순서있는 목록 : 숫자와 점 이용**
```
1. 첫번째
2. 두번째
3. 세번째
```
1. 첫번째
2. 두번째
3. 세번째


**순서없는 목록 : 기호 `*`, `+`, `-` 지원**
* 빨강
  * 녹색
    * 파랑

+ 빨강
  + 녹색
    + 파랑

- 빨강
  - 녹색
    - 파랑

* 1단계
  - 2단계
    + 3단계
      + 4단계

```
* 빨강
  * 녹색
    * 파랑
+ 빨강
  + 녹색
    + 파랑
- 빨강
  - 녹색
    - 파랑
* 1단계
  - 2단계
    + 3단계
      + 4단계
```

### 4. 들여쓰기
```
This is a normal paragraph:
    This is a code block.
    
end code block.
```
This is a normal paragraph:

 This is a code block.
    
end code block.

> 한 줄 띄어쓰기 안한 경우
> ```
> This is a normal paragraph:
>  This is a code block.
> end code block.
> ```
> This is a normal paragraph:
>  This is a code block.
> end code block.

### 5. 코드블럭
> - ```<pre><code>{code}</code></pre>``` 이용방식
> - 코드블럭코드 "빽틱```" 이용방법
> ```
> ```python(언어는 생략가능)
> code```
> ```
### 6. 수평선
```
* * *
***
*****
- - -
---------------------------------------
```
* * *

***

*****

- - -

---------------------------------------


### 7. 링크
```
* 외부링크 : [Google](https://google.com, "google link")
* 외부링크: <http://example.com/>
* 이메일링크: <address@example.com>
```
* 외부링크 : [Google](https://google.com, "google link")
* 외부링크: <http://example.com/>
* 이메일링크: <address@example.com>


### 8. 이미지
```
![Alt text](/path/to/img.jpg)
![Alt text](/path/to/img.jpg "Optional title")
<img src="/path/to/img.jpg" width="" height="" title="" alt=""></img>
```
![Alt text](/path/to/img.jpg)
![Alt text](/path/to/img.jpg "Optional title")
<img src="/path/to/img.jpg" width="" height="" title="" alt=""></img>
