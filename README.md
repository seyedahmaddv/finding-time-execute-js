# finding-time-execute-js
finding the Measure JavaScript Execution Time
------------------------------------------------
We can find the time taken to execute a function by using:

The Date.now() object
The console.time and console.timeEnd()
The performance.now() function

#Using the Date.now() object
----------------------------

We use the Date.now() method to get the current time in milliseconds. The method helps us get the time before and after executing a function. We find the difference between the time after executing the function and the time before executing the function. This will result in the time taken to execute the function.

#Using console.time and console.timeEnd()
-----------------------
We call the console.time() to initiate a timer with a name. We call the console.timeEnd() to stop the timer. This is used to get the time taken to execute a function.

#Using performace.now
-----------------------
The performance.now method returns the time passed (Read about time origin here). This method returns the time as floating-point numbers with up to microsecond precision.

The performance.now method is the most efficient way to calculate the execution time because we can calculate the execution time with microsecond precision.
