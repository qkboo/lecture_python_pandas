# Day5

- [day5_진행 노트북1](./day5_진행.ipynb)
- [day5_진행 노트북2](./day5_진행2.ipynb)


## Day5 과제

1. 컴퓨터 정수/이진수 조사와 학습후 github 에 정리
2. 컴퓨터 문제세트, 텍스트 파일 인코딩 조사 및 학습후 github 정리
3. 어제 과제인 **최소공배수**에 대한 알고리즘을 학습후 github 정리
4. f literal 예제 코드 해보기
    - 명세서: https://docs.python.org/ko/3/library/string.html#formatspec
    - 샘플: https://bluese05.tistory.com/70
5. 교재 책 p341~371 공부하기

과제는 이메일로 제출!

---

## day5 수업중 실습: 입력된 텍스트의 문장을 역으로 변환해 파일에 저장

- [Day5박고등_prac](./Day5박고등_prac.ipynb)
- [Day5한상근_제출용](./Day5한상근_제출용.ipynb)
- [day5박태민_실습](./day5박태민_실습.ipynb)



---

# 리뷰
 - 과제 리뷰

# 1. 파일


1. open 과 모드
2. with 구문
3. encoding
4. binary
5. exception


#### open()

파일은 open() 명령에서 `<MODE>` 값에 따라 읽고 쓴다. [Python builtin functions](https://docs.python.org/3/library/functions.html)
    
>open(file, mode='rb', buffering=-1, encoding=None, errors=None, newline=None, closefd=True, opener=None)
  - mode는 파일에 대한 액션과 파일 형식을 지정한다: rb, wb, wr
     - 액션 : w(기록), a(추가), r(읽기:기본값)
     - 타입 : t(텍스트:기본값), b(2진 파일)
open 으로 열린 객체는 `.close()` 로 닫아 주어야 한다.


# 2. 모듈 
