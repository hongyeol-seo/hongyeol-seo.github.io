---
title: 뮤터블(mutable)과 이뮤터블(immutable)
tags: PYTHON
---

## 뮤터블(mutable)
- 변경이 가능한 객체
- 생성 후 자유롭게 값을 변경, 추가, 삭제 등이 가능하다.
- list, set, dictionary 등
- 변수의 값을 변경하면 객체 자체를 업데이트 한다. (값 변경 -> 할당된 메모리에 전달)
- call by reference(참조에 의한 호출)

## 이뮤터블(immutable)
- 변경이 불가능한 객체
- 생성 후 값 변경, 추가, 삭제 등이 불가능하다.
- 숫자, string, tuple 등
- 변수의 값을 변경하면 다른 객체를 생성하고 그 객체에 대한 참조로 업데이트 된다.
  (값 변경 -> 새로운 메모리에 전달)
- call by value(값에 의한 호출)