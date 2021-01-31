
## 1. What will happen at line 11 and why?
console.log() is line of code that is a print key or the value pass or display to user. 
However in line 11 it does not print anything unless we declare or sign to any integer. In order to be able to show in console. The value of i is var and can be used in both inside and  outside the loop.
##  2. What will happen at line 12 and why?
In line 12 the code console.log() suppose to print discountedPrice  in the console because the value discountedPrice is passed to console, However in the console we don’t get anything because in line above nothing has been passed. 

##  3. What will happen at line 13 and why?
	When line 13 executed as result we still didn't see anything in console because nothing has been passed to line 11 and 12, therefore in all three lines compile without getting any runtime error because all values inside the console.log have been declared in code. 
##. 4 What will the function return for discountPrices([100, 200, 300], .5)? Give a brief explanation.
	After we executed those number to function in terminal we get 3, 150, 150
	Which is 3 for line 11, 150 for line 12 and 150 for line 13. 
	console.log(i) will print 3
	console.log(discountedPrice) wil print 150
	console.log(finlaPrice) will print also 150 

## 5. What will happen at line 11 and why?
	In this line nothing will be printed by calling console.log(i). Also it wont get a compile error depending on which system(compiler ) the user is going to use. However, in general it is supposed to get a compile error since ‘i’ is only available inside of the scope block loop. However when the function is called it will cause an error.
“Error: ReferenceError: i is not defined”  Because the type of i is let and we only can use i inside the loop scope not outside the loop. 

## 6. What will happen at line 12 and why?
	Line 12 will not be executed after the function call because line 11 is declared as a type of let. Therefore it will cause line 12 not to run. If we take line 11 then 150 will be printed after using the function. 

## 7. What will happen at line 13 and why? 
	As a result of the above base of the compiler I used noting it will be printed and no compile error. Line 13 is print the code in the console. Will not be executed after passing the function because in line 11 the ‘i’ is declared as let and it won't be available outside the scope. 
## 8. What will the function return for discountPrices([100, 200, 300], .5)? Give a brief explanation. 
	After executing the function we get an error because of line 11 as ‘i’ declared inside the loop as a type of let. Because of that line 12 and 13 will not be executed.  This will be on terminal “Error: ReferenceError: i is not defined”
depending on the compiler user is using. 


## 9. 	What will happen at line 11 and why?
The line 11 suppose to happen the same as question 5 no error until the function being use. When function use i will get error because i declared as type of let in the loop. And that i will be only available inside that loop. 

## 10 	What will happen at line 12 and why?	
Line 12 will be executed and no compile error until the function call. When the function passes it will cause an error because we can’t change the value of const after declare. Therefore we will see an error message on console . 

## 11.  What will happen at line 13 and why? 
	Line 11 will not be executed because it ‘i’ declared as a type of let in loop and will not be readable outside the loop. Also the type of ‘finalPrice’ is the wrong type to be const. 

## 12. What will the function return for discountPrices([100, 200, 300], .5)? Give a brief explanation. 
	We will see an error on the console because the value finalPrice is const and it can not be changed. 
This is the error base of the compile I use 
‘error: TypeError: invalid assignment to const 'finalPrice'’

## 13. Given the above Object, write the notation for:  
 ### A. Accessing the value of the name property in the student object
	studnet.name 
### B. Accessing the value of the Grad Year property in the student object
	student[“Grade Year”]
### C. Calling the function for the greeting property in the student object
	student.greeting();  

### D. Accessing the name property of the object in the Favorite Teacher property in student
	studnet[“Favorite Teacher”].name
### E. Access the first index in the array of the courseLoad property of the student object
studnet.courseLoad[0] 

## 14. Arithmetic
	A ) 
The output for ‘3’ + 2 will be ‘32’ the compiler add character ‘3’ to number 2 will added to number 2 string and will be read ‘32’ see it as character by concatenate number 2 as string 
	B ) 
	The output ‘3’ - 2 will be 1. 	The number inside ‘ ‘ will be ignore after using - 
	C )
	The output 3 + null  will be 3. Because null in javaScript is considered as 0 noting. 
	D ) 
	The output ‘3’ + null will be ‘3null’ the javascript will add anything after + sign and concatenate with 3 
	E )
	The output true + 3 is 4. The javascript will read true as number 1 and will be added to 3. That’s why we get 4
	F )
	The output false + 3 is 3. The javaScript will read false as number 0 and will be added to 3. That’s why 0 + 3 = 3 
	G ) 
the output “3” + undefined is ‘3undefined’.  Concatenate inside “ “ and added to undefined


H ) 
The output “3” - undefined is NaN the word undefined in javascript is mean undefined and the console can’t concatenate 3 to value is not assigned yet. 

## 15 ) Comparison
A ) ‘2’ > 1  output is  true because the value in char is treated as number and 2 > 1 therefore the result will be true. 

B) ‘2’ < ‘12’ output is true the value in ‘ ‘ is < the value ‘ ‘ right side therefore is true

C )  2 == ‘2’ output true it is true because the value inside the ‘ ‘ is treated as number and 2 == 2 so it is true

D ) 2 === ‘2’ output false because the value on both sides is the same but the type is not. Therefore is false. In order both side to be true both sides must be the same value and same type. 

E ) true == 2 output false. Because javaScript read true as 1 and in reality 1 is not equal to 2. So the output will be false

F ) true === Boolean(2) the output ‘ReferenceError: boolean is not defined’ because the value of boolean is not defined. 

## 16 ) Explain the difference between the == and === operators.
	== is design to compare two variables but ignore the database of the variable.
	=== compare the two variables and the type as well

 ## 17 ) .  The output of the code above will be How are you? Because the first if is not true therefore it will never run. The else if will is 2 and that will run as true, any number in else will cause the program except number 0. If we put 0 to else if it will not be executed. Because 0 is treated as false. Last statement will never run because the else if is already true. 

## 18 ) for { var i = 0; i < statistics.length(); i++ ) {
	console.log(i);
}
		

## 19 ) First when we pass [1,2,3] to function  modifyArray( array, callback ) in return we get value[6,8,10]. Inside the modifyArray there is const newArr = [ ]  that it will not be change the value being passed into it. Inside the loop the size of the i is the size of the array which is the array we are going to pass [1,2,3] so this is 3 and it will increment until ‘i’ reaches the point that is i not < the size. In the line 4 the function push is put the value inside the function as long as the loop runs. Run 5 will multiply x by 2. After the loop ends the line 8 will be executed and return the newArr. 

	
	## 20. The 3 lines above print the current time in the console. However it will not update the time. The console.log(time) in line 8 is show time in console. Line 2 time will be assigned to d.of the current time function. 

	## 21. 
1, 4, 3, 2 
each will take one line. Each number in a different line.  





