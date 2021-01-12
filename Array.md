# 배열

* 각 값들이 메모리에 연속적으로 저장되지 않는다.
* 배열내에서 추가 삭제가 용이하다.
* insert, append, remove 함수 

~~~
let month = 3
let toDo = "Travel"

var toDoArray = ["Travel", "Work", "Call"]  //var toDoArray: Array[String] = ["Travel", "Work", "Call"]
var evenNumber = [2,4,6,8]  //var evenNumber: Array[Int] = [2,4,6,8]

//값 가져오기
toDoArray[0]
toDoArray[1]
toDoArray[2]

//값 변경
toDoArray[0] = "Play"
toDoArray[1]
toDoArray[2]

//append -> 값을 마지막 인덱스 배열에 추가한다.
evenNumber.append(10)

//insert -> 값 중간에 추가
evenNumber.insert(12, at: 0)

//remove -> 값 삭제
evenNumber.remove(at: 0)

for toDo in toDoArray {
    print(toDo)
}

~~~
