# 700745488-Assignment-3-Ashwin-Kumar-Reddy-Cherukupally

Below is the video recording which clearly describes the info regarding the codes.
https://drive.google.com/file/d/1SN2AS4lVCRpS_CQLl0TOw56OcF-5-we3/view?usp=share_link

In class programming:
1). Create a class Employee and then do the following
    • Create a data member to count the number of Employees
    • Create a constructor to initialize name, family, salary, department
    • Create a function to average salary
    • Create a Fulltime Employee class and it should inherit the properties of Employee class
    • Create the instances of Fulltime Employee class and Employee class and call their member functions.
    
A) First we need to create a class known as Employee and then need to create a data member to count the number of Employees and then__init__ method is declared within a class and is used to initialize the attributes of an object as soon as the object is formed. While giving the definition for an __init__(self) method, a default parameter, named 'self' is always passed in its argument. This self represents the object of the class itself. Here self.name = name is used to take a name, like one a user inputs, and assign it to the name associated with the object.Then we are defining a function average salary and storing all the employees salaries in add variable and then defining a class fulltimeemployee which is a subclass of employee and we are using a super() function to access the data from the parent class and further defining a main function and then we are appending both fulltimeemployee data and employee data in the femployee[] and employee[] function and then printing the average salary of both fulltimeemployees and employees.


2). Numpy
Using NumPy create random vector of size 20 having only float in the range 1-20.
Then reshape the array to 4 by 5
Then replace the max in each row by 0 (axis=1)
(you can NOT implement it via for loop)

A) First create a random vector of size 20 having in a float range of 1-20 and in the code we are importing all the numpy modules and using them as np, and we are using np.random.uniform() function to create arrays filled with random samples which are from a uniform distribution. Additionally we are using a reshape() function which allows to reshape an array and also using maximum function to finding the element maximum of array elements and repalcing maximum elements with 0 and keepdims parameter of NumPy mean enables you to control the dimensions of the output and axis =1 which states the directions of rows along columns and finally printing the vector.
