![Logo](https://imarticus.org/blog/wp-content/uploads/2021/12/learn-Python-for-data-science.jpg)
# Python for Data science
### DESCRIPTION:

#### we can divide python into 4 stages:

     -> Python Basics
     -> Python Intermediate
     -> Python Advanced
     -> Python Production Level
### what we will learn
 - Understand basics and more advanced concepts in python
   language.
 - Be introduced to data analysis using pandas,numpy
   and data analysis library.
 - walk through the process of interviewing
   and answering technical questions.
 - learn how to build projects on real-world applications
   with the python language.
## Python Basics
 - Print statement
 - variables
 - Operators
 - Data types
 - Control and Condition statemens
  ## Print statement
  ->Print statement is one of the most basic and popular functions in python - the print() statement.

  ->Python print() function is used to print the specified object to the standard output device (screen) or to a text stream file.

   ->The Python print() method is used to print a given message to the screen or to display an object’s value on the terminal.

    for example: print('Hello World!')
  ## variables
 ->A variable is a named memory location in which we can store values for the particular program.

 ->In Python, We don't need to declare explicitly variable in Python. When we assign any value to the variable that variable is declared automatically.

 ->In Python, We don't need to specify the type of variable because Python is a loosely typed language.
 
    -Rules for naming variable:

 ->Variable names can be a group of both letters and digits, but they have to begin with a letter or an underscore.

 ->It is recommended to use lowercase letters for variable name. 'SUM' and 'sum' both are two different variables.

example:

    a=12 #interger
    b=1.2 #float
    c="Hello" #string

->Python allows us to assign a value to multiple variables and multiple values to multiple variables in a single statement which is also known as multiple assignment.

    Assign single value to multiple variables:

    example: a=b=c=10
    
    Assign multiple values to multiple variables:

    example: a,b,c=1,2,3
## Operators
->Operators in Python are special symbols that carry arithmetic or logical operations. The value that the operator operates on is called the operand.

->In python there are 7 different types of Operators:
### Arithmetic Operators:
    + (addition)
    - (subtraction)
    *(multiplication)
    /(divide)
    %(reminder)
    // (floor division)
    ** (exponent)
### Membership Operators:
    in (True, If the value is present in the data structure)   
    not in (True, If the value is not present in the data
    structure)
### Comparison operators:
    == (Equal to)
    != (Not equal to)
    <= (Less than or equal)
    >= (Greater than or equal)
    < (Less than)
    > (Greater than)
### Assignment operators:
    = (Assigns to)
    += (Assignment after Addition)
    -= (Assignment after Subtraction)
    *= (Assignment after Multiplication)
    /= (Assignment after Division)
    %= (Assignment after Modulus)
    **= (Assignment after Exponent)
    //= (Assignment after floor division)
### Bitwise operators:
    & (binary and)
    | (binary or)
    ^ (binary xor)
    ~ (negation)
    << (left shift)
    >> (right shift)
### Logical operators:
    and (logical and)
    or (logical or)
    not (logical not)
### Identity operators:
    is (Returns true if both variables are the same object)
    is not (Returns true if both variables are not the same object)
## Data types
 ->In general, data types specifies what type of data will be in variables

 ->Python provides following standard data types:

    1.Numbers
    2.Strings
    3.Lists
    4.Tuple
    5.Set
    6.Dictionaries
    7.Boolean
    8.None
 #### 1.Numbers:
 ->Numbers store numeric values

 ->There are 3 numeric types in python
 
    1.int:It is a whole number,positive and negative
            without decimals.
      example: a=7,b=-11,c=-23
    2.float:It is a floating number,positive or negative
            with containing one or more decimals.
      example: p=2.12,q=16.0,r=-4.6
    3.complex:Complex numbers are written with a"j" as the
            imaginary part.
      example: a=3+5j,b=-4+9j,c=-27j
  #### 2.Strings:
  ->The string can be defined as a sequence of characters
  represented in quotation marks.
   
      example: s1='Hi', s2="Hello", s3="'world'"
  ->Python strings are immutable which means they cannot
  be changed after they are created.

  -> indexing in strings starts from 0.And in negetive indexing -1 refers to last item,-2 is 2nd last element and so on.

  ->String build-in functions are used for string handling.
  #### 3.Lists
  ->A list is a collection of items that are orderd and mutable.Lists are represented with square bracket and items are separated by commas.

      example: list=[2,3,4,7], list2=[2.4,1.1,30.0]
  ->Indexing in list is as same as in python strings.

  ->Python list build-in functions are used for adding,deleting,updating of items in the list.
  #### 4.Tuple
  ->A tuple is a sequence of immutable element or items and it can store multipleitems in a single variable.

  ->A tuple can be represented in small brackets().

  ->Indexing in tuple is as same as in python strings and lists.

  ->There are only two build-in functions in a tuple for accessing the items 1.count 2.index.

    example: t1=(1,'python',4.2) , t2=('c',)
  #### 5.Set
  ->A set is a unordered collectionof items.Every elementis unique and must be immutable.And are represented by curly braces {}.

  ->Set doesnot have indexing because set is unordered. 

  ->However,the set itself is mutable.We can add or remove items from it.

  ->Sets are used to perform mathematical set operations
  like union,intersection etc.

  ->Set elements can be of different types,like list,tuple,set or dictionary
  
    example: s1={1,2,3}, s2={[1,23,45]}, 
    s3={1.0,'Python',[24,11,2.0]}

  #### 6.Dictionaries
  ->A dictionary is a unorderd collection of key-value pairs.Dictionaries are represented by curly braces {}, key and values are separated by colons ','.

  ->Dictionary is mutable and Dictionaries are indexed by keys.

    example: {"name":"jayanth","age":21}
  #### 7.Boolean
  ->Boolean data type generally has only two values 'True' or 'False'.

    example: input: 24==24
            output: True
             input: 11<7
            output:False
  #### 8.None
  ->Python uses the keyword None to define null objects and variables.

    example: input: a=None
             print(a)
             output: None
## Python Intermediate
    -> Conditional statements
    -> Loop statements
    -> control statements
    -> Functions
## Conditional statements
-> Conditional statements perform different actions and computations based on conditions.

-> In python there are 3 Conditional statements:

    1. if 
    2. if-else
    3. if-elif-else
#### 1. if statement
-> An if statement is used to check a condition,and execute it if the condition holds true.

    Syntax:
            if condition:
              statement 1
              statement 2..
    example: 
            if 2>1:
              print('True')
#### 2. if-else statement
-> An if-else statement is used to execute both true part and false part in the given condition.

    Syntax:
            if condition:
              statement 1
              statement 2..
            else:
              statement 3
              statement 4..
    example:
            a=2
            b=1
            if a>b:
              print('True')
            else:
              print('False)
#### 3.if-elif-else statement
-> we can use if-elif-else statement to tell python to try a different condition if the previous conditions were not met.

    Syntax:
            if condition 1:
              statement 1
              statement 2..
            elif condition 2:
              statement 3
              statement 4..
            elif condition 3:
              statement 5
              statement 6..
            else:
              statement 7
              statement 8..
    example:
            a=1
            b=2
            c=3
            if a>b:
              print('a is Greater than b')
            elif b>c:
              print('b is Greater than c')
            elif c>a:
              print('c is Greater than a')
            else:
              print('all are same')
## Loop statements
-> Looping means repeating something over and over until a particular condition is satisfied.

    Types of Loops
    1. While Loop
    2. For Loop
    3. Nested Loop

  #### 1. While Loop
  -> A while loop allows code to be executed repeatedly,depending on whether a condition is satisfied or not.

    Syntax:
           while condition:
              statement(s)
    example:
           i=1
           while i<=2:
              print(i)
              i=i+1
            output:
            1
            2
  #### 2.For Loop
  -> The for loop in python is used to iterate the statements or a part of program several times.It is frequently used to traverse the data structures like list,tuple,string or dictionary.

    Syntax:
          for iterating_var in sequence:
              statement(s)
    example:
          for i in range(1,4):
              print(i)
          output:
          1
          2
          3
  #### Nested Loop
  -> A nested loop refers to a loop within a loop,an inner loop within the body of an outer one.

    example:
       for i in range(5):
          for j in range(5):
              print('*',end=' ')
              print()
       output:
            * * * * *
            * * * * *
            * * * * *
            * * * * *
            * * * * *
