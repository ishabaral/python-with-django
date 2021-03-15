# Projects Q&A :
[Project Q&A is also available on Colab](https://colab.research.google.com/drive/1xOVex2ZZLf9_ub-SEu3bdi3ntAQ3ntVe?usp=sharing#scrollTo=g5RW89-P01bg)

1. Open a Python shell, enter the following expressions, and observe the results:
    
    a. 8

    b. 8 * 2

    c. 8 ** 2

    d. 8/12
    
    e. 8 // 12
    
    f. 8/0
    
    ```python
    8
    ```
    `Output:`
    >8
    ```python
    8*2
    ```
    `Output:`
    >16
    ```python
    8**2
    ```
    `Output:`
    >64
    ```python
    8/12
    ```
    `Output`
    >0.6666666666666666
    ```python
    8//12
    ```
    `Output`
    >0
    ```python
    8/0
    ```
    `Output`
    >ZeroDivisionError <br>                        Traceback (most recent call last)<ipython-input-6-b75faf41dc75> in <module>() <br>
     ----> 1 8/0 <br>
   ZeroDivisionError: division by zero

2. Write a Python program that prints (displays) your name, address, and telephone number.
   ```python
    print("My name is Isha Baral. \nI am from Pokhara. \nMy contact number is 9856000001 ")
   ```
   `Output:` 
   >My name is Isha Baral. <br> 
   I am from Pokhara. <br> 
   My contact number is 9856000001 

3. Evaluate the following code at a shell prompt: print("Your name is", name). Then assign name an appropriate value, and evaluate the statement again.
   ```python
   name= input("Your name is ")
   print("Your name is", name)
   ```
   `Output:`
   >Your name is Isha Baral <br>
   Your name is Isha Baral

4. Write and test a program that accepts the user's name(as text) and age(as a number) as input. The program should output a sentense containing the user's name and age.
   ```python
    name= input("Enter your name :")
    age = int(input("Enter your age :"))
    print("Your name is {name} and your age is {age}".format(age=age, name=name))
   ```
   `Output:`
   >Enter your name :Isha <br/>
   Enter your age :20 <br/>
   Your name is Isha and your age is 20 

5. Write and test a program that computes the area of a circle. This program should request a number representing a radius as input from the user. It should use the formula 3.14radius*2 to compute the area and then output this result suitably labeled.
   ```python
   radius= int(input("Enter the radius of a circle :"))
   area= 3.14*radius**2
   print("The area of circle is ", area)
   ```
   `Output:`
   >Enter the radius of a circle :7 <br>
   The area of circle is  153.86

6. Enter an input statement using the input function at the shell prompt. When the prompt asks you for input, enter a number. Then, attempt to add 1 to that number, observe the results and explain what happened.
   ```python
    num = input("Enter a number :")
    num = num+1
   ```
   `Output:`
   > Enter a number :6 <br>
   TypeError: can only concatenate str (not "int") to str <br><br>
   #Here we are entering a string not a number but we are trying to perform addition operation of the string(num) and a integer(1). That's why we got the error.

7. Enter the expression help() at the shell prompt. Follow the instructions to browse the topics and modules.
    
    ![alt text](https://drive.google.com/file/d/1ZeZeBsa2A7FGJHCT6LI3I3hStEOF3QgR/view?usp=sharing)
    >Figure shows the topics
    >Similarly type modules to see the result 

8. The tax calculator program of the case study outputs a floating-point number that might show more than two digits of precision. Use the round function to modify the program to display at most two digits of precision in the output number.
   ```python
    num= 79.3222232
    print(round(num, 2))
      ```
      `Output:`
      >79.32

9.  You can calculate the surface area of a cube if you know the length of an edge. Write a program that takes the length of an edge(an integer) as input and prints the cube's surface area as output.
    ```python
    length = int(input("Enter the length of an edge :"))
    area = 6*length**2
    print("The cube's surface area is :", area)
    ```
    `Output:`
    >Enter the length of an edge :6 <br>
    The cube's surface area is : 216

10. Five Star Retro Video rents VHS tapes and DVDs to the same connoisseurs who like to buy LP record albums. The store rents new videos for  3.00anight,andoldiesfor 2.00 a night.
Write a program that the clerks at Five Star Retro Video can use to calculate the total charge for a customer’s video rentals.
The program should prompt the user for the number of each type of video and output the total cost.
    ```python
    a = float(input("Enter the number of new videos: "))
    b= float(input("Enter the no. of andoldies videos: "))
    c= 3.0*a+2.0*b
    print("The cost is ", c)
    ```
    `Output:`
    >Enter the number of new videos: 7 <br>
    Enter the no. of andoldies videos: 8 <br>
    The cost is  37.0


11. Write a program that takes the radius of a sphere(a floating point number) as input and then outputs the sphere's diameter, circumference, surface area and volume.
    ```python
    r= float(input("Enter the radius of a sphere :"))
    d = 2*r
    c = 2*3.14*r
    a= 4*3.14*r**2
    v= 4/3*3.14*r**3
    ```
    `Output:`
    >print("The sphere's diameter is {d}, circumference is {c}, surface area is {a} and volume is {v} ".format(d=d, c=c, a=a, v=v))

12. Instructions An object's momentum is its mass multiplied by its velocity. Write a program that accepts an object's mass (in kilograms) and velocity (in meters per second) as inputs, and then outputs its momentum.
    ```python
    mass = float(input("Enter mass in kilograms: "))
    velocity = float(input("Enter velocity in meters per second: "))
    m = mass*velocity
    print("Momentum is ", m)
    ```
    `Output:`
    >Enter mass in kilograms: 5 <br>
   Enter velocity in meters per second: 7 <br>
   Momentum is  35.0

13. The kinetic energy of a moving object is given by the formula KE = ½mv2 where m is the object’s mass and v is its velocity.
Modify the program you created in Project 5 so that it prints the object’s kinetic energy as well as its momentum.
    ```python
    mass = float(input("Enter mass in kilograms: "))
    velocity = float(input("Enter velocity in meters per second: "))
    m = mass*velocity
    KE = 1/2*mass*velocity**2
    print("Momentum is %s and kinetic energy is %s " %(m, KE))
    ```
    `Output:`
    >Enter mass in kilograms: 5 <br>
    Enter velocity in meters per second: 7 <br>
    Momentum is 35.0 and kinetic energy is 122.5 

14. An employee’s total weekly pay equals the hourly wage multiplied by the total number of regular hours plus any overtime pay. Overtime pay equals the total overtime hours multiplied by 1.5 times the hourly wage. Write a program that takes as inputs the hourly wage, total regular hours, and total overtime hours and displays an employee’s total weekly pay.
    ```python
    h= float(input("Enter the total no of regular hours: "))
    w= float(input("Enter the hourly wage "))
    oth = float(input("Enter the total overtime hours: "))
    ot= oth*1.5*w
    s = w*h+ot
    print("Total weekly pay is ",s)
    ```
    `Output:`
    >Enter the total no of regular hours: 2 <br>
    Enter the hourly wage 7 <br>
    Enter the total overtime hours: 8 <br>
    Total weekly pay is  98.0