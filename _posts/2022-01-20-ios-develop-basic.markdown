---
layout: post
title:  "Playground test"
date:   2022-01-20 18:30:00 +0900
categories: jekyll update
---


```swift

import UIKit

var greeting = "Hello, playground"


let value = arc4random_uniform(100)
print("--> \(value)")
      
/*


여러줄
코멘트
주르륵

*/


// ---Tuple 서로 관계가 있는 데이터를 사용할때 유용

let coordinates = (4, 6)

let x = coordinates.0
let y = coordinates.1

let coordinatesNamed = (x: 2, y: 3)

let x2 = coordinatesNamed.x
let y2 = coordinatesNamed.y

let (x3, y3) = coordinatesNamed
x3
y3

// --- Boolean

let yes = true
let no = false

let isFourGreaterThanFive = 4 > 5

if isFourGreaterThanFive {
    print(" 참 ")
} else {
    print(" 거짓 ")
}


//if 조건~ {
//    // 조건이 참 일 경우, 수행하는 코드를 여기
//} else {
//    // 조건이 거짓 일 경우, 코드를 여기에 작성
//}


let a = 5
let b = 10

if a > b {
    print (" a가 크다 ")
} else {
    print (" b가 크다 ")
}


let name1 = "Zoey"
let name2 = "Roni"

let isTwoNameSame = name1 == name2

if isFourGreaterThanFive {
    print ("이름이 같다")
} else {
    print ("이름이 다르다")
}


let isRoni = name2 == "Roni"
let isMale = false

let RoniAndMale = isRoni && isMale
let RoniOrMale = isRoni || isMale



//let greetingMessage : String
//if isRoni {
//    greetingMessage = "Hello Roni"
//} else {
//    greetingMessage = "Hello Somebody"
//}
//print("Msg : \(greetingMessage)")


let greetingMessage : String = isRoni ? "Hello Roni" : "Hello Somebody"
print("Msg \(greetingMessage)")



// --- Scope

var hours = 50
let payPerHour = 10000
var salary = 0

if hours > 40 {
    let extraHours = hours - 40
    salary += extraHours * payPerHour * 2
    hours -= extraHours
}

salary += hours * payPerHour

// print(hours) 는 가능, print(extraHours)는 불가능, 코드블럭 Scope 범위를 벗어났기 때문


```


 
