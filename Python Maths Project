"""
Here I created an program to improve an mathematical skills 
like addition / substraction / multiplication / Division  
"""
import random

def main():
    conti = 1   #intial value is 1 to implement 1st while loop

    name = input("Enter your Name : ")
    print("Welcome "+str(name)+" !")
    
    #if user gives 0 after 1st round the stop if gives 0 then again disaply list and continue
    while conti != 0:
        print_list()    #print list for user to choose get choise from user
        choice = int(input("Enter your choice "+name+" which arithmatic operation you want to practice : "))
        
        #check enterd choice is valid or not 
        if choice ==1 or choice ==2 or choice ==3 or choice ==4:
            
            if choice == 1 :
                addition_practise(name)
            
            if choice == 2 :
                substraction_practise(name)
            
            if choice == 3 :
                multi_practise(name)
            
            if choice == 4 :
                division_practise(name)
            
        else:
            print("Please Enter Valid Choice ")

        #ask user he want's to continue or not 
        conti = int(input("You want to continue practise (1 for Yes/ 0 for No) : "))
    


def print_list():
    print("\n1. Addition \n2. Substraction \n3. Multiplication \n4. Division ")

def addition_practise(name):
    count=0
    while count != 3:
        #generate 2 random numbers here 
        num1 = random.randint(10,99)
        num2 = random.randint(10,99)

        #sum of that 2 random numbers
        total = num1 + num2
        #ask user for their answer
        print("What is "+str(num1)+" + "+str(num2)+"?") 
        ans = input("Your answer: ")

        #check if user press enter the quit user from practise  
        if ans == "" :
            print(name+" You Quit practise. \n Thank You! \n ")
            break

        if ans == str(total) :
            count += 1
            print("Correct! You've gotten "+str(count)+" correct in a row")
        else :
            print("Incorrect. The expected answer is "+str(total))
            count = 0 
            
    #user gives 3 correct answers contineously 
    if count == 3:
        print("Congratulations! You mastered addition.")

def substraction_practise(name):
    count=0
    while count != 3:
        #generate 2 random numbers here 
        num1 = random.randint(100,999)
        num2 = random.randint(10,99)

        #substraction of that 2 random numbers
        substract = num1 - num2
        #ask user for their answer
        print("What is "+str(num1)+" - "+str(num2)+"?") 
        ans = input("Your answer: ")

        #check if user press enter the quit user from practise  
        if ans == "" :
            print(name+" You Quit practise. \n Thank You!")
            break

        if ans == str(substract) :
            count += 1
            print("Correct! You've gotten "+str(count)+" correct in a row")
        else :
            print("Incorrect. The expected answer is "+str(substract))
            count = 0 
            
    #user gives 3 correct answers contineously 
    if count == 3:
        print("Congratulations! You mastered addition.")

def multi_practise(name):
    count=0
    while count != 3:
        #generate 2 random numbers here 
        num1 = random.randint(10,99)
        num2 = random.randint(1,10)

        #Multiplication of that 2 random numbers
        mul = num1 * num2
        #ask user for their answer
        print("What is "+str(num1)+" * "+str(num2)+"?") 
        ans = input("Your answer: ")

        #check if user press enter the quit user from practise  
        if ans == "":
            print(name+" You Quit practise. \n Thank You!")
            break

        if ans == str(mul):
            count += 1
            print("Correct! You've gotten "+str(count)+" correct in a row")
        else:
            print("Incorrect. The expected answer is "+str(mul))
            count = 0 
            
    #user gives 3 correct answers contineously 
    if count == 3:
        print("Congratulations! You mastered addition.")

def division_practise(name):
    count=0
    while count != 3:
        #generate 2 random numbers here 
        num1 = random.randint(10,99)
        num2 = random.randint(1,10)

        #Division of that 2 random numbers
        div = num1 // num2
        #ask user for their answer
        print("What is "+str(num1)+" / "+str(num2)+"?") 
        ans = input("Your answer: ")

        #check if user press enter the quit user from practise  
        if ans == "":
            print(name+" You Quit practise. \n Thank You!")
            break

        if ans == str(div):
            count += 1
            print("Correct! You've gotten "+str(count)+" correct in a row")
        else:
            print("Incorrect. The expected answer is "+str(div))
            count = 0 
            
    #user gives 3 correct answers contineously 
    if count == 3:
        print("Congratulations! You mastered addition.")


if __name__ == '__main__':
    main()
