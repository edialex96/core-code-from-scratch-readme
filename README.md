# core-code-from-scratch-readme

create an explanation about Interpreted And Compiled Programming Languages in your README.

interpreted lenguages are those that are executed on time. the interpreter reads the code line by line while it is executed

in compiled programs we install the version and the computer runs it directly

mission statement

My name es Edilson Granados i am from colombia, i am currently working in construction as a tower crane operator, i am 26 years old. i am a industrial maintenance mechanic.
i want to be an excelent software developer and help create solutions to solve enviromental and social issues, generate value for the people 
 
my main values are passion, a desire to leave this world better than i found it, tolerance, honesty, vission, 


  Starting point: START
  Input: READ, GET
  Output: PRINT
  Math: +, -, *, /
  Assignation: <--
  Initialize: SET, INIT
  Add one: INCREMENT
  End point: END

input: 1btc = 23.712dls


amount --< read
BTCprice <-- GET FROM(https://www.coindesk.com/price/bitcoin/)
Total <-- Amount * BTCprice
PRINT Total
END

my date of birth in binary

03         07         19996
011       111         11111001010


Based on the guide and the examples of the low-level language, create the following

1. Create a program that adds any two given numbers provided by the user
2. Create a program that displays your name

1
  .data
	      number1: .asciiz "\nIngrese el primer numero: "
	      number2: .asciiz "\nIngrese el segundo numero: "
  .text
	      main:
              li $v0, 4
              la $a0, number1
              syscall

              li $v0, 5
              syscall

              move $t0, $v0

              li $v0, 4
              la $a0, number2
              syscall

              li $v0, 5
              syscall

              move $t1, $v0

              li $v0, 1
              move $a0, $t0
              syscall


JAVASCRIPT-WEEK 2 

![code wars multiplicasion](https://user-images.githubusercontent.com/75593932/182041639-1af37cc9-09c9-4d34-a837-1941a9086f68.png)



