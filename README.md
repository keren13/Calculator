# Calculator
Adding, multiplying, and subtracting numbers in python in intervals of one.

##CalculatorProjectForAdditionAndSubtraction
def adding(number1,number2):
    currentSum = 0
    for i in range(number2):
        currentSum = number1 + 1
        number1 = number1 + 1
        return currentSum
firstNumber = 5
secondNumber = 6
print(adding(firstNumber,secondNumber))

def subtracting(number1, number2):
    currentSub = 0
    for i in range(number2):
        currentSub = number1 - 1
        number1 = number1 - 1
        return currentSub
fNumber = 10
sNumber = 5
print(subtracting(fNumber, sNumber))

def multiplying(number1, number2):
    currentMult = number1
    for i in range(number2-1):
        currentMult = currentMult + number1
    return currentMult
fNumber = 2
sNumber = 3
print(multiplying(fNumber,sNumber))
