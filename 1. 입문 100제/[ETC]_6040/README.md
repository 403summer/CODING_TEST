# [기초-산술연산] 정수 2개 입력받아 나눈 몫 계산하기

[문제링크](https://codeup.kr/problem.php?id=6040)



## 1. 문제설명

정수 2개(a, b) 를 입력받아 a를 b로 나눈 몫을 출력해보자.




## 2. 문제풀이

```python
a, b = input().split()
c = int(a)//int(b)
print(c)
```



## 3. 참고

python언어에서는 나눈 몫을 계산하는 연산자(//, floor division)를 제공한다.
a//b 와 같이 작성하면, a를 b로 나눈 몫(quotient)을 계산해준다.
프로그래밍언어에 따라 이렇게 몫을 계산해주는 연산자가 없는 경우도 있다.

