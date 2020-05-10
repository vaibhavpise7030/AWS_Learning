## How to run CPP PRogram on Linux

* First we have to connect EC-2 (created on AWS) using mobaXterm. 
-------
## STEPS:
### 1) Open CMD and check whether gcc is isntall or not by command: 
  * `"gcc -v"` if it will display
  * `"gcc : command not found"`
  then run 
  * `sudo su yum -y install gcc-c++` .
  -------
  
### 2) Now, after that check whether gcc tool installed or not by 
   * `command: gcc -v`
   ![gcc -v](https://github.com/vaibhavpise7030/AWS_Learning/blob/master/Day%203/Images/gcc-v.png)
    
---------
             
### 3) Make Directory: 
* command: ` mkdir`

 ![MAKE DIRECTORY](https://github.com/vaibhavpise7030/AWS_Learning/blob/master/Day%203/Images/2.png)
------------
### 4) create cpp file
* `vi vaibhav.cpp` (create a cpp file)
---------
### 5) Enable code
* `press-i` to enable code.
---------
### 6) Enter demo code
* `#include<iostream> using namespace std; int main() { cout<<"Demo"<<endl};`


![Code](https://github.com/vaibhavpise7030/AWS_Learning/blob/master/Day%203/Images/3.png)
----------

### 7) Press 
* `Esc`
----------
### 8) press 
* `:wq` ( w= save written code and q= exit control).
---------
### 9) compile code
* `g++ vaibhav.cpp -o vaibhav` (compile code)
---------
### 10) Rune code
* `./vaibhav` 


![Output](https://github.com/vaibhavpise7030/AWS_Learning/blob/master/Day%203/Images/4.png)
--------
