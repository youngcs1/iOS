
/*## Question
- 두 개의 정수를 입력받아 두 수를 하나로 합친 결과를 출력하는 함수 (1, 5 입력 시 15 반환)
- 문자열 두 개를 입력받아 두 문자열이 같은지 여부를 판단해주는 함수
- 학점을 입력받아 각각의 등급을 반환해주는 함수 (4.5 = A+,  4.0 = A, 3.5 = B+ ...)
- 여러 등급을 입력받아 그 학점의 평균을 반환해주는 함수
- 윤년 구하기 (2월 29일이 있는 해.  매 4년 마다 윤년. 매 100년 째에는 윤년이 아님. 매 400년 째에는 윤년)
- 세 수를 입력받아 세 수의 곱이 양수이면 true , 음수이면 false 반환하는 함수
- 특정한 달을 숫자로 입력 받아 문자로 반환해주는 함수 (1 = "Jan" , 2 = "Feb")


두 개의 정수를 입력받아 두 수를 하나로 합친 결과를 출력하는함수(1, 5 입력시 15 반환)
문자열 두 개를 입력받아 두 문자열이 같은지 여부를 판단해주는 함수
학점을 입력받아 각각의 등급을 반환해주는 함수 (4.5 = A+ , 4.0)
여러 등급을 입력받아 그 학점의 평균을 반환해주는 함수
윤년 구하기 (2월 29일이 있는 해, 매 4년 마다 윤년. 매 100년 째에는 윤년이 아님. 매 400년 째에는 윤년)
세 수를 입력받아 세 수의 곱이 양수이면 true , 음수이면 false 반환하는 함수
특정한 달을 숫자로 입력 받아 문자로 반환해주는 함수 (1 = "Jan" , 2 = "Feb")
*/










//- 문자열 두 개를 입력받아 두 문자열이 같은지 여부를 판단해주는 함수






//- 학점을 입력받아 각각의 등급을 반환해주는 함수 (4.5 = A+,  4.0 = A, 3.5 = B+ ...)






//- 여러 등급을 입력받아 그 학점의 평균을 반환해주는 함수





//- 윤년 구하기 (2월 29일이 있는 해.  매 4년 마다 윤년. 매 100년 째에는 윤년이 아님. 매 400년 째에는 윤년)






//- 세 수를 입력받아 세 수의 곱이 양수이면 true , 음수이면 false 반환하는 함수







//- 특정한 달을 숫자로 입력 받아 문자로 반환해주는 함수 (1 = "Jan" , 2 = "Feb")

//
//func returnMonth(month: Int) -> String {
//
//    switch month {
//    case 1:
//    print("Jan")
//    case 2:
//    print("Feb")
//    case 3:
//    print("Mar")
//    case 4:
//    print("Apr")
//    case 5:
//    print("May")
//    case 6:
//    print("Jun")
//    case 7:
//    print("Jul")
//    case 8:
//    print("Aug")
//    case 9:
//    print("Sep")
//    case 10:
//    print("Oct")
//    case 11:
//    print("Nov")
//    case 12:
//    print("Dec")
//
//    default:
//        break
//    }
//    return month
//
//}
//


for index in 1...4{
    print("\(index) times 5 is \(index * 5)")
}


for _ in 0...3 {
    print("Hello")
}


for chr in "Hello"{
    print(chr,terminator: " ")
}
print()



//power = 0
//t = 3
//
//for _ in 1...10{
//
//    power *= t
//}


//1~9 사이의 숫자를 입력받아 해당 숫자에 해당하는 구구단의 내용을 출력하는 함수

//dan = 0
//
//
//for i in 1...10{
//    print( )
//}


//정수 하나를 입력받아 그 수의 Factorial을 구하는 함수




//let fruits =["A": "Apple","B":"Banana","C": "Cherry"]




//1 ~ 9 사이의 숫자를 입력받아 해당 숫자에 해당하는 구구단의 내용을 출력하는 함수

func multiPle(dan: Int){

        for i in 1...9{
            print( "\(dan) X \(i) = \(i*dan)")
        }
}


multiPle(dan: 5)




//정수 하나를 입력받아 그 수의 Factorial 을 구하는 함수

func factRial(num: Int) -> Int{
    
    var sumFact: Int = 0
    
    for i in 1 ... num {
        
        sumFact *=  (num - i)
    }
    
    return sumFact
}

print("Now", factRial(num: 10))




//정수 두개를 입력받아 첫 번째 수를 두 번째 수의 횟수만큼 곱한 값을 반환하는 함수

func inputTwoNum(num: Int, num2: Int)->Int{
    
    var result: Int = 0
    
    for _ in 1 ... num2 {
        result *= num
    }
    
    return result
}

inputTwoNum(num: 5 , num2: 5)





//정수 하나를 입력받아 각 자리수 숫자들의 합을 반환해주는 함수

//func inNum(num: Int)->Int {
//    //785 7+8+5 =
//    
//}




//100 이하의 자연수 중 3과 5의 공배수를 모두 출력하는 함수




//정수 하나를 입력받아 그 정수의 약수를 모두 출력하는 함수

//func measure(num: Int)-> Int{
//
//    // 1, 2, 5, 10
//
//
//}



//2 이상의 정수를 입력받아, 소수인지 아닌지를 판별하는 함수




//정수를 입력받아 입력받은 수에 해당하는 자리의 피보나치 숫자를 반환하는 함수







//
//## Question
//- 두 개의 정수를 입력받아 두 수를 하나로 합친 결과를 출력하는 함수 (1, 5 입력 시 15 반환)



func inputNum(Num1: Int , Num2: Int)->Int {
    
    var sum: Int = 0
    sum = Num1 + Num2
    return sum
    
}


print(inputNum(Num1: 10, Num2: 20))




/*
func greet(person: String)->String{
    let greeting = "Hello, " + person + "!"
    return greeting
}

print(greet(person: "Anna"))
 */









//- 문자열 두 개를 입력받아 두 문자열이 같은지 여부를 판단해주는 함수

func difChar(inChar1: String , inChar2: String) ->Bool {
    
    if  inChar1 == inChar2 {
        return true
    }
    return false
}

difChar(inChar1: "AAA", inChar2: "BBB")
difChar(inChar1: "AAA", inChar2: "AAA")







//- 학점을 입력받아 각각의 등급을 반환해주는 함수 (4.5 = A+,  4.0 = A, 3.5 = B+ ...)

func inGrade(sPoint: Float){
    
    switch  sPoint {
    case 4.5 :
            print ("A+")
    case 4.0 :
            print ("A")
    case 3.5 :
            print ("B+")
    case 3.0 :
            print ("B")
    case 2.5 :
            print ("C+")
    case 2.0 :
            print ("C")
    case 1.0 :
            print ("D")
    case 0.0 :
            print ("F")
    default  :
            print ("Valid Input")
        
    }
}

inGrade(sPoint: 12)



//- 여러 등급을 입력받아 그 학점의 평균을 반환해주는 함수


func inGradeToAvg(grades: String...) -> Double {

    var avg: Double = 0

    for number in grades {

        switch number {
        case "A+":
            avg += 4.5
        case "A":
            avg += 4.0
        case "B+":
            avg += 3.5
        case "B":
            avg += 3.0
        case "C+":
            avg += 2.5
        case "C":
            avg += 2.0
        case "D+":
            avg += 1.5
        case "D":
            avg += 1.0
        case "F":
            avg += 0.0
        default:
            print("Invalid Input")
            break
        }
    }
    let gradeAvg: Double = avg / Double(grades.count)
    return gradeAvg
}


print(inGradeToAvg(grades: "A+","A+","A+","KK"))



//여러개의 grade를 입력받아서 grade의 평균을 반환해주는 함수







//- 윤년 구하기 (2월 29일이 있는 해.  매 4년 마다 윤년. 매 100년 째에는 윤년이 아님. 매 400년 째에는 윤년)







//- 세 수를 입력받아 세 수의 곱이 양수이면 true , 음수이면 false 반환하는 함수
//- 특정한 달을 숫자로 입력 받아 문자로 반환해주는 함수 (1 = "Jan" , 2 = "Feb")

func transMonth(mon: Int) {
    
    switch mon {
    case 1 :
        print("Jan")
    case 2 :
        print("Feb")
    case 3 :
        print ("Mar")
    case 4 :
        print ("Jun")
    case 5 :
        print ("May")
    case 6 :
        print ("Jun")
    case 7 :
        print ("Jul")
    case 8 :
        print ("Aug")
    case 9 :
        print ("Sep")
    case 10 :
        print ("Oct")
    case 11 :
        print ("Nov")
    case 12 :
        print ("Dec")
    default :
        print("Invalid value")
    }
}

transMonth(mon: 11)



