---
title: "마크다운 언어 문법 정리"
layout: post
date: 2021-06-15 16:40
image: /assets/images/markdown.jpg
headerImage: false
tag:
- markdown
- firstCommit
star: true
category: blog
author: GiSeok Song
description: Markdown first using in the blog
---

# md언어 사용법(문법)

## 1. header H1~H6
---
    문자 아래 H1
    ========
    
    문자 아래 H2
    --------
    
    # 가나      H1
    ## 가나     2
    ### 가나    3
    #### 가나   4
    ##### 가나  5
    ###### 가나 6

문자 아래
========  

문자 아래 
--------
<br>

# 가나
## 가나 
### 가나
#### 가나
##### 가나
###### 가나

<br>

## 2. 인용문
---
    > 첫번째 블럭
    >> 두번째 블럭
    >>> 세번째 블럭

    > 이 안에 다른 요소 추가 가능 
    > * list 
    >   ```
    >   가나다라마바사
    >   ```

    
> 첫번째 블럭
    >> 두번째 블럭
    >>> 세번째 블럭 


> 이 안에 다른 요소 추가 가능 
> * list 
>   ```
>   가나다라마바사
>   ```

<br>

## 3. 목록
---
* ## 순서 있는 목록 
    ```
    1. 첫번째
    2. 두번째 
    3. 세번째
    ```
    1. 첫번째
    2. 두번째 
    3. 세번째  

    ## 어떤 순서로 하든 내림차순으로 적용.

    ```
    1. 첫번째
    3. 두번째
    2. 세번째
    ```

    1. 첫번째
    3. 두번째
    2. 세번째

---
* ## 순서 없는 목록 

```
* 목록1
    * 목록2
        * 목록3
- 목록1
    - 목록2
        - 목록3
+ 목록1
    + 목록2  
        + 목록
* 목록1
    - 목록2
        + 목록3
- 목록1
    * 목록2
        +목록3
섞어서 사용 가능
```
* 목록1
    * 목록2
        * 목록3
- 목록1
    - 목록2
        - 목록3
+ 목록1
    + 목록2  
        + 목록
* 목록1
    - 목록2
        + 목록3
- 목록1
    * 목록2
        + 목록3

<br>

## 4. 링크 및 이미지
--------------------
### 4.1 링크
    [GOOGLE](https://www.google.com/)
    [NAVER](https://www.naver.com "링크에 대한 설명")
    [상대적 참조](../)
    [다음][daum link]
    [GitHub][1]
    문서 안에 [참조링크] 사용 가능

    구글 홈페이지: https://google.com  

    네이버 홈페이지: <https://naver.com>  
    [참조 링크]: https://naver.com "네이버로 이동합니다!"


    [daum link]: https://daum.net

    [1]: https://github.com

[GOOGLE](https://www.google.com/)

[NAVER](https://www.naver.com "링크에 대한 설명")

[상대적 참조](../projects/)

[다음][daum link]

[GitHub][1]

문서 안에 [참조 링크] 사용 가능

구글 홈페이지: https://google.com  

네이버 홈페이지: <https://naver.com>  

[참조 링크]: https://naver.com "네이버로 이동"

[daum link]: https://daum.net

[1]: https://github.com

---
  

### 4.2 이미지
### 링크와 비슷 하게 !만 앞에 붙혀 서 사용
    
    ![대체 텍스트](https://a.disquscdn.com/1623278138/images/noavatar92.png)

    ![대체 텍스트2][사진]

    [사진]: https://img1.daumcdn.net/thumb/R720x0.q80/?scode=mtistory2&fname=http%3A%2F%2Fcfile7.uf.tistory.com%2Fimage%2F24283C3858F778CA2EFABE "강아지"

    
    이미지에 링크 걸기
    [![대체 텍스트](https://a.disquscdn.com/1623278138/images/noavatar92.png)](https://song014.github.io//how-to-use-md/)
    
![대체 텍스트](https://a.disquscdn.com/1623278138/images/noavatar92.png)

![대체 텍스트2][사진]

[사진]: https://img1.daumcdn.net/thumb/R720x0.q80/?scode=mtistory2&fname=http%3A%2F%2Fcfile7.uf.tistory.com%2Fimage%2F24283C3858F778CA2EFABE "강아지"


[![대체 텍스트](https://a.disquscdn.com/1623278138/images/noavatar92.png)](https://song014.github.io//how-to-use-md/)

<br>

## 5. 수평선
------------
### 각 가호를 3개씩 붙혀 사용

```
---
(Hyphens)

***
(Asterisks)

___
(Underscores)
```

---
(Hyphens)

***
(Asterisks)

___
(Underscores)


    
