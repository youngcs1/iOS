


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

