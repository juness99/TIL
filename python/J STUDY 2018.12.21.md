# J STUDY 2018.12.21

### 홀수 짝수 구별하는 코드

```python
for i in range(1,10): #1~10의 수를 반복
    if i%2==0: #i를 2로나눈 나머지가 0이면 짝수 아니면 홀수
        print("짝수")
    else:
        print("홀수")
```

##### 터미널 출력

```
student@DESKTOP MINGW64 ~/change
$ python python.py
홀수
짝수
홀수
짝수
홀수
짝수
홀수
짝수
홀수
```

##### 홀수짝수 구별하는 코드에서 n=5일때 정지하는 코드

```python
n=0 
for i in range(1,10):
    if i%2==0:
        print("짝수")
    else:
        print("홀수")
    n=n+1
    if n==5:
        break
```

※break 를 걸어주면 for문에서 나가게된다.

##### 터미널 출력

```
student@DESKTOP MINGW64 ~/change
$ python python.py
홀수
짝수
홀수
짝수
홀수
```

몫,나머지를 한번에 구하고싶으면 divmod()를 사용

```python
a=divmod(17,3)
print(a)
```

##### 터미널 출력

```
student@DESKTOP MINGW64 ~/change
$ python python.py
(5, 2) #5는 몫 2는 나머지
```

### 문자열을 숫자로 변환

```python
a= '2018-12-18'
b=a.split('-')
print(b)
c=int(b[0])
print(c)

```

##### 터미널 출력

```
student@DESKTOP MINGW64 ~/change
$ python python.py
['2018', '12', '18']
2018
```



### 문자열 포맷 코드

![1545377006436](C:\Users\student\AppData\Roaming\Typora\typora-user-images\1545377006436.png)

### format 함수를 이용한 포맷팅

```
>>> "I eat {0} apples".format(3)
'I eat 3 apples'
```



```
>>> "I eat {0} apples".format("five")
'I eat five apples'
```

### 왼쪽정렬

```
>>> "{0:<10}".format("hi")
'hi        '
```

### 오른쪽정렬

```
>>> "{0:>10}".format("hi")
'        hi'
```



![1545377208822](C:\Users\student\AppData\Roaming\Typora\typora-user-images\1545377208822.png)



### 문자열 바꾸기

```
a="Life is too short, you need python"
b=a.find("short")
print(b)

a="a:b:c:d"
b=a.split(":")
print(b)
c="#".join(b)
print(c)
```

