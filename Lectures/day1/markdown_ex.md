# 헤더

`#` 으로 `<h>` 태그 표현



```html
<h1></h1>
<h2></h2>
<h3></h3>
<h4></h4>
<h5></h5>
```

# h1 태그

## h2 태그

### h3 태그

#### h4 태그

##### h5 태그

---

# 강조

*안녕하세요*

_안녕하세요_


**안녕하세요**

__안녕하세요__

안녕하세요. **IoT** **_과정_** 여러분 ***반갑***습니다.



# 리스트

- 아이템1
- 아이템2
    - 아이템22

+ 아이템1
+ 아이템2
    - 아이템3
    - 아이템4

- 아이템1
    - 아이템 중에 **중요**한 것으..


---

1. 하나
2. 둘
3. 셋

문장을 써주시거나.

1. 하나
1. 둘
1. 셋
    1. 들여쓰기
    1. 들여쓰기
    1. 들여쓰기
        - 순서없는
        - 순서없는
        
---

# 정리

<h1> 하나 </h1>

<strong>강조</strong>

<ul>
 <li>하나
 <li>둘
</ul>

<ol>
 <li>하나
 <li>둘
</ol>


# 링크

[서브1](./sub1.md)

[서브1](sub1.md)

[서브1](/day2/sub1.md)

[깃헙](https://guides.github.com/features/mastering-markdown/)


<a href="./sub1.md">a link 서브1</a>


# 인용

> 인용은 해당 문서 내용중 외부에서 얻은 자료...
자료....

>인용은 해당 문서 내용중 외부에서
> ```java
> public class java {
> 
> }
> ```

# 이미지

![](https://octodex.github.com/images/yaktocat.png)

<img src='https://octodex.github.com/images/yaktocat.png' width=200>


# Syntax highlighting

```python
def foo():
    if not bar:
        return True
```


# Task lists

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item
