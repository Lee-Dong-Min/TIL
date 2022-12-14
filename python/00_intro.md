# PYTHON 입문

## 1. 식별자
변수, 함수, 모듈, 클래스 등 식별시 사용하는 이름 (name)
- 영문 알파벳, 숫자, '_'로 구성
- 첫 글자에 숫자 불가
- 알파벳 대·소문자(case) 구분
- 길이 제한 없음
- 내장함수, 모듈 등의 이름 사용 자제 (`ptint()`, `str()` 등)
- 다음 예약어 사용 불가
```python
False, None, True, and, as, assert, break, class, continue, def, del, elif, else, except, finally, for, from, global, if, import, in, is, lambda, nonlocal, not, or, pass, raise, return, try, while, with, yield
```
## 2. 기초 문법
### 주석 (Comment)
- `#`으로 표현 (ctrl+/)
- 장문의 주석은 ```로 감싸기

## 3. 변수(Variable)와 자료형
- `=`으로 할당(assignment)
- `type()`을 활용하여 자료형 확인
- `id()`로 값의 메모리 주소 확인

### - 숫자형(Numbers)
`int (정수, integers)`
`0b2진수`, `0o8진수`, `0x16진수`

`float(실수, floating point number)`
    ※ 부동소수점을 사용하므로 계산시 오차 발생함

`complex(복소수, complex numbers)`