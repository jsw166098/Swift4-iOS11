# 반복문

## for 문

~~~
for i in 1...10 {  //범위 연산자 ...
    print(i)
}

for i in stride(from: 1, to : 10, by: 2) {
    print(i)
}

for i in stride(from: 1, to : 10, by: -2) {
    print(i)
}


for j in 2...9{
    for i in 1...9 {
        print(j*i)
    }
}

for j in 2...9{
    print("\(j)단 시작")
    for i in 1...9 {
//        print(String(i) + " X " + String(i) + " = " + String(j*i)) -> 다른 문자열 타입과 계산 안된다.
        print("\(j) X \(i) = \(j * i)")
    }
}
~~~

## while 문

~~~
var i = 0
while i<10 {
    i+=1
    print(i)
}
~~~

## repeat while 문
~~~
i = 0
repeat {
    i+=1
    print(i)
} while i < 10
~~~
