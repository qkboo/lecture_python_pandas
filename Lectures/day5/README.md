# Day5

[day5_진행 노트북](./day5_진행.ipynb)

##### day5 수업중 실습: 입력된 텍스트의 문장을 역으로 변환해 파일에 저장

- [Day5박고등_prac](./Day5박고등_prac.ipynb)
- [Day5한상근_제출용](./Day5한상근_제출용.ipynb)



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
