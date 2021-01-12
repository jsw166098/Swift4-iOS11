# 조건문

## if 문
~~~
let dust = 35

if dust <= 30 {
    print("아 공기 상쾌하다~~")
}
else if dust > 30 && dust <= 50 {
    print("뭐 이정도면 나쁘지 않군")
}
else if dust > 50 && dust <= 100 {
    print("헉 최악이다! ㅜ")
}
~~~

## switch 문

* default 생략시 오류
* 조건문에 여러 조건 가능

~~~
let weather = "비"
switch weather {
case "맑음":
    print("☀️")
case "흐림":
    print("☁️")
case "비", "장마", "소나기":
    print("☔️")
case "눈":
    print("☃️")
    
default:
    print("⛅️")
}
~~~
