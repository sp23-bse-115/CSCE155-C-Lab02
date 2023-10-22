
# Computer Science I 
## Lab 2.0 Worksheet

Name(s) and Login(s):



1. Dennis Ritchie, the creator of the C programming language,
was born on September 9th, 1941.  If he were still alive,
how old would he be today?  Find out by running the `birthday`
program on the appropriate inputs and enter your solution here.
ANSWER
today is 2023/10/22
your birthday was 1841/09/09
Hello ,Dennis. you are -68years, -2weeks ,and -4 days old today.



2. Bjarne Stroustrup, the creator of the C++ programming
language, the object-oriented extension of C, was born on
December 30th, 1950.  How old is he today?
ANSWER:
 today is 2023/10/22
 your birthday was 1950/12/30
 hello , bjaren. you are -68 years,-2 weeks, and -4 days old today




3. Software testing often involves testing code with known
"bad" input in an attempt to break it (sometimes this is
referred to as *fuzzing*).  Try breaking the `birthday_cli`
program by giving it "bad" input and observe the consequences.
Give at least two examples of potentially bad input and the
results you observe.
ANSWER:
   exampels 1: bad input : abbas khan 1900 4
   result: today was 
   Hello , abbas . you are 0 years,0 weeks, and 0 days old today.
Example 2: Bad input :99 / 0m 12
result: Today is 2023/10/22
Your birthday was 
Hello, 99. You are 0years, 0weeks, and 0 days old today.


4. Complete all the size and range entries below.

* `char`
  size: 1 byte
  range: -128 to 127
* `short int`
  size:2 byte
  range:-32768 to 32767
* `int`
  size:4 byte
  range:-2147483648 to 2147483647
* `long int`
  size:4
  range:-21474838648 to 2147483647
* `float`
  size:4
  range: 7 digits of accuracy
* `double`
  size:4
  range: 15 digits of accuracy


5. Use your working currency conversion to determine
the exchange amounts for the following inputs:

  a) $250.25
ANSWER:Half of the Dollar Exchange to 92.34255 GBP
Half of the Dollar Exchange to 16873.857422 JPY


  b) $1,000.52
answer: Half of the Dollar Exchange to 67463.02500 JPY
Half of the Dollar Exchange to 369.191895 GBP


  c) $968,410.12
Answer:Half of the Dollar Exchange to 357.192017 JPY
Half of the Dollar Exchange to 65270.304688 JPY



6. Suppose that you had used only `int` types
in your conversion program.  Would you be able
to use it to convert the US national debt
(which as of 2020 was \$26,009,754,625,487)?
Why or why not?
Answer: No because int can store the number upto 32 bit and the given number greater so 32 bit not sufficient  for that because it is limited to 32bit.



7. Mixed types

a) Run the `area` program with 3 and 4 as inputs.  
What value do you get?  Is this result correct?
Answer: Value: The area is 0.000000 square units
Not giving the corrent answer use formula incorrectly because the precedance level of / and * same.

b) Execute the program again with inputs 3 and 5.
Does the program give correct results?  Why not?
Answer: Value The area is 0.000000 square units.
Not giving the correct answer use formula  incorrectly because the precedance level of / and * same.


c) Fix the program by editing the `area.c` source
code so that the program produces correct results.
ANSWER:
the area is 8.000000square units.
i increased the precedance level of base*triangle 
by include parenthesis and then divided them by 2 like that 
(base*height)/2
Answer:
The area is 8.000000 square units.
I increase the precedance level of base*triangle  by include parenthesis  and then divide them by 2 like that (base  * heaight)/2.