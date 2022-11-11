Q1. Why do we call Python as a general purpose and high-level programming language?

    Python is an object-oriented, high-level programming language. Object-oriented means this language is based around objects (such as data) rather than functions, and high-level means it's easy for humans to understand.
    In computer software, a general-purpose programming language (GPL) is a programming language designed to be used for building software in a wide variety of application domains, across a multitude of hardware configurations and operating systems.

Q2. Why is Python called a dynamically typed language?
    
    In the python language we need not to mention statically the datatype of the data,python interpreter takecare
    of the datatype dynamically 

Q3. List some pros and cons of Python programming language?

     
     pros:
     python is easy to learn and read
     python enhances productivity
     python has a vast collection of libraries
     python is free,open_source and has a vibrant community
     python is a portable language
     python is a interpreted language
     
     cons:
     python has speed limitations
     python is not so strong with mobile computing
     python can have runtime errors
     Python consumes a lot of memory space
     Python is not easy to test
     

Q4. In what all domains can we use Python?

     python is used in Artificial inteligence(AI)
     Machine Learning
     Deep Learning
     Data science applications
  

Q5. What are variable and how can we declare them?
    
    an identifier is a word and  it is used to identify variables,methods,functions,classes....etc.
    It can be a variable name,method name,function name,classname..ete
    Variable:variable is a container that contains data
    Rules to declear an identifier:
    1.It can be formed by using alphabets(A to Z &a to z),digits(0 to 9),&underscore symbol(_).
    2.It must start with alphabets and underscore symbol only
    3.length of the identifier(variable) is not limited.
    4.It shoud not contain special symbol other than underscore symbol
    5.it should not contain white space character(space bar,tab&enter keys)

Q6. How can we take an input from the user in Python?
     
     Here we are using the input() function (python In-Build function).

Q7. What is the default datatype of the value that has been taken as an input using input() function?

      "String" litral is the default datatype of the value  when we use input() function as ainput.

Q8. What is type casting?
    
    changing the one datatype to another data type is known as type casting.

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
     
     No,at a time only one input will be taken by using only single input() function.
     yes,when we use split() function along with input() function we can take multiple inputs by the user
      

Q10. What are keywords?

    A set of words reserved by language itself and those words are known as keywords.
    In python there are 36 keywords right now
    
    


```python
import keyword
print(keyword.kwlist)
len(keyword.kwlist)
```

    ['False', 'None', 'True', '__peg_parser__', 'and', 'as', 'assert', 'async', 'await', 'break', 'class', 'continue', 'def', 'del', 'elif', 'else', 'except', 'finally', 'for', 'from', 'global', 'if', 'import', 'in', 'is', 'lambda', 'nonlocal', 'not', 'or', 'pass', 'raise', 'return', 'try', 'while', 'with', 'yield']
    




    36



Q11. Can we use keywords as a variable? Support your answer with reason.
    
    No, we can not use the keywords as a variable
    Keywords are used to define the syntax of the coding. The keyword cannot be used as an identifier, function, and
    variable name. All the keywords in python are written in lower case except True and False

Q12. What is indentation? What's the use of indentaion in Python?
      
      Indentation is basically the leading white space character added at the beginning of statements to indicate
      a block of code.The main purpose of indenting the code is to separate the blocks of code. Besides, it also 
      improves the readability of the code.

Q13. How can we throw some output in Python?

     Using the print() function(In-Build python function) we can print the output.

Q14. What are operators in Python?

      An operator is a special symbol which operates on data.
      In python operators are divided into 8 categories
      1.Arithemetic operators
         +  ---> addition
         -  ---> subtration
         *  ---> multipication
         /  ---> division
         // ---> floor division
         %  --->modulo division
         ** ---> exponential
      2.relational operators (these operators always returns bool type date)
         <  ---> lessthan
         >  ---> greaterthan
         <= ---> lessthan or equals to
         >= ---> greaterthan or equals to
         == ---> equals to
         != ---> not equals to
      3.logical operators (these operators always returns bool type date)
         and  ---> logical AND
         or   ---> logical OR
         not  ---> logical NOT
      4.bitwise operators
         &  ---> bitwise AND
         |  ---> bitwise OR
         ^  ---> bitwise XOR
         << ---> left shift
         >> ---> right shift
         ~  ---> complement(Tilde)
      5.Assignment operators
         =     ---> normal assignment
         a+=b  ---> a=a+b
         a-=b  ---> a=a-b
         a*=b  ---> a=a*b
         a/=b  ---> a=a/b
         a//=b ---> a=a//b
         a%=b  ---> a=a%b
         a**=b ---> a=a**b
         a&=b  ---> a=a&b
         a|=b  ---> a=a|b
         a^=b  ---> a=a^b
         a<<=b ---> a=a<<b
         a>>=b ---> a=a>>b
      6.membership operators
      7.identity operators
      8.unary plus & unary minus operators
      

Q15. What is difference between / and // operators?

       " / " is divison operator it ruturns Quotient in float format
       "//"  is a floor division operator it ruturns quotient in integer format

Q16. Write a code that gives following as an output.

    iNeuroniNeuroniNeuroniNeuron

example:



```python
 print("iNeuron"*4)
```

    iNeuroniNeuroniNeuroniNeuron
    


```python
# Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
x=int(input("enter a number: "))
if x%2==0:
    print("given input number is even number")
#elif:
   # print("given number is odd number ")
else:
    print("given input number is odd")
```

    enter a number: 66
    given input number is even number
    

Q18. What are boolean operator?
   
    Logical And
    logical OR
    logical NOT and relational operatores like >,<,<=,>=,==,!= also  returns bool values(True and false)


```python
# Q19. What will the output of the following?
"""
1 or 0    
0 and 0
True and False and True
1 or 0 or 0 """
print(0 or 1)
print(0 and 0)
print(True and False and True)
print(1 or 0 or 0)

```

    1
    0
    False
    1
    

Q20. What are conditional statements in Python?

       The if statement is a conditional statement in python, that is used to determine whether a block of code will be executed or not
       if conditional statement
       if-else statement
       if-elif---else statement
       Nested if  statement   
       

Q21. What is use of 'if', 'elif' and 'else' keywords?
     
     
     It allows us to check for multiple expressions. If the condition for if is False , it checks the condition of the next          
     elif block and so on. If all the conditions are False , the body of else is executed.

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".


```python
age=int(input("enter the age of the person: "))
if age>=18:
    print("i can vote")
else:
    print(" i cann't vote")
```

    enter the age of the person: 12
     i cann't vote
    

Q23. Write a code that displays the sum of all the even numbers from the given list.

numbers = [12, 75, 150, 180, 145, 525, 50]


```python
numbers=[12, 75, 150, 180, 145, 525, 50]
sum=0
for i in numbers:
    if i%2==0:
        sum=sum+i
        print("sum of the even numbers in a given list: ",sum)
        print(f" after  adding {sum}")
        
```

    sum of the even numbers in a given list:  12
     after  adding 12
    sum of the even numbers in a given list:  162
     after  adding 162
    sum of the even numbers in a given list:  342
     after  adding 342
    sum of the even numbers in a given list:  392
     after  adding 392
    

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

     


```python
a=[200,500,856]
greater_number=0
for i in range(len(a)):
    if a[i]>greater_number:
        greater_number=a[i]
print(greater_number)
```

    856
    

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```


```python
numbers = [12, 75, 150, 180, 145, 525, 50,600,750,652,13,186]
for ele in numbers:
    if ele%5==0:
        if ele>150:
            continue
            if ele>500:
                break
        print(ele)          
        
```

    75
    150
    145
    50
    


```python

```
