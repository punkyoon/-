# bang-gwi (방귀)

뿡뿡

> [shook-lang](https://github.com/pjongy/shook-lang) 2차 창작물입니다

## Guide

- `뿡` : 변수 대입 선언
- `뿍뿍` : 변수 + 1
- `뽁뽁` : 변수 - 1

- `~` : 변수 = 변수^2

- `뿌직` : 스택 포인터 += 1
- `쀼직` : 스택 포인터 -= 1

- `뽀옹` : 스택 포인터가 가리키는 스택 데이터에 변수 대입
- `뽀뽀옹` : 변수에 스택 포인터가 가리키는 스택 데이터 대입

- `북` : 변수에서 스택 데이터 더하기
- `부북` : 변수에서 스택 데이터 빼기
- `부부북` : 변수에서 스택 데이터 곱하기
- `부부부북` : 변수에서 스택 데이터 나누기

- `=3` : 스택 포인터 변수에 대입 선언
- `==3` 스택 포인터 변수에 대입 완료
- `빵` : 변수를 str로 변환 후, 스택 포인터 위치에서 역순으로 저장 (산술 연산 결과 출력시 사용)
- `빠아앙` : 스택 데이터가 0이거나 스택 포인터가 0이 될때까지 -1을 하며 1byte씩 출력

## Example

print `helloworld`

```
뿡뿍뿍뿍뿍뿍뿍~뿍뿍뽀옹뿌직뿡뿍뿍뿍뿍~~뽀옹뿡뿍뿍뿍뿍뿍뿍~부부북부북부북부북뿍뿍뿍뿍뿍뿍뿍뿍뽀옹뽀뽀옹뽀옹뿡뿍뿍뿍뿍뿍뿍~뽁뽁북뿌직뽀옹뿡뿍뿍뿍뿍~북뿍뿍뿍뿍뿌직뽀옹뽀뽀옹뿌직뽁뽁뽁뽁뽁뽁뽀옹뽀뽀옹뿌직뿌직뽀옹뿡뿍뿍뿍뿍~북뿍뿍뿍뿍뿍뿍뿍뿍쀼직뽀옹쀼직쀼직쀼직뽀뽀옹뿌직뿌직뿌직뿌직뿌직뽀옹쀼직쀼직쀼직쀼직쀼직뽀뽀옹뿌직뿌직뿌직뿌직뿌직뿌직뽀옹뽀뽀옹뽁뽁뽁뽁뽁뽁뽁뽁뿌직뿌직뽀옹뽀뽀옹쀼직뽁뽁뽁뽁뽁뽁뽀옹뿌직뿌직빠아앙
```

## How to use

```sh
$ python3 bang-gwi/main.py --input example/helloworld.bang-gwi

# or
$ python3 bang-gwi/main.py --input example/helloworld.bang-gwi --debug true
```
