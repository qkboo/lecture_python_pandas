# 실습: html 파일을 받아 문자 개수를 출력하는 프로그램을 작성하자. 

> 프로그램 파라미터 사용 예: https://wikidocs.net/36

html 파일에서 순수한 텍스트의 글자수를 출력하도록 작성한다.

- 프로그램명: html_count.py
- 입력파일: 1개 이상의 html 파일
    - naver.com 의 news, sports
- html tag 제거,
- 결과를 텍스트 result.txt에 저장하고 화면에도 출력.
    - 결과를 result.txt 에 아래 같이 저장
    
        ```
        news.html html = 211319, text = 76413, nospace = 4609
        test.html html = 2124, text = 67, nospace = 123
        ```

예)

```terminal
$ python html_count.py news.html it.html
```
