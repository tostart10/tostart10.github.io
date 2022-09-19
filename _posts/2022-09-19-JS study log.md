[변수와 상수]

< 변수에 적용할 수 있는 연산자 >
1. 복합 대입연산자
2. 증감 연산자

두 개 모두 변수에 적용한다
상수에는 적용할 수 없다!!


<복합 대입 연산자>
let a = 100
a += 100   //(a = a + 100  과 같다)

#복합 대입 연산자 사용 시 주의 사항
- a = a+100 같은 형식이므로 a가 변수여야함
- - (a+=100는 a = a + 100이 되므로 lvalue와 rvalue로 모두 사용된다.)

const a =100처럼 a를 상수로 지정하면 실행시 오류 발생!!!


<증감 연산자>
변수에 사용하기 때문에 변수를 만들어 주고 사용해야한다.
let a = 0
// a++ a--   이 형태를 더 많이 사용함 (아래나 위나 같은 거임)
// ++a —a

a++   > a에 1을 더한 값을 출력함으로 1이 출력됨
a--   > a에 1을 빼기 때문에 (위에서 a값이 1이였으므로) 0이 나온다

let a = 0
a++
a++
a++
console.log(a)
>>>3


< undefined 자료형 >
1. 상수와 변수로 선언하지 않은 식별자
    typeof(a)
 >>>undefined
 
 
2. 값이 없는 변수 (를 나타낼 때)
let b
typeof(b)
>>>undefined


상수를 선언할 때 사용하는 키워드는?
▶ const

상수는 상수를 선언할 때 바로 값을 넣어줘야한다
const r
r=10
console.log(r)
>>> 오류


const r = 10
console.log(r)
>>>> 10



a++
=> 현재 문장을 실행한 후에 a +=1
let a = 0
console.log(a++)  //0 // console.log(a) -> a +=1
console.log(a)   //1  


++a
=> 현재 문장을 실행하기 전에 a+= 1
let b = 0
console.log(++b) // 1 // b += 1 -> console.log(b) 
console.log(b)   // 1

