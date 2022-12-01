# Fibonacci Benchmark(Iterative and Recursive)

A series of integers known as the Fibonacci sequence begins with a zero, a one, and another one. The numbers then gradually rise. Each number in the series is equal to the sum of the two numbers before it.

There are two ways to calculate a fibonacci number: iteratively and recursively.
# How to Run the code
Before running the code, we must to this first
```
make clear
```
after that running this code will create a mylib.o automatically and create main.out aswell
```
make all
```
and lastly after running this code it will ask for an input of the fibonnaci and it will instantly give you the results of both fibonacci.
```
./main.out
```
the results:
```
Input the integer:10
Fibonacci Iterative of 10 = 55
Fibonacci Recursive of 10 = 55
```

# Time Complexity Benchmark
Running these code will describe the amount of time it takes for the computer to run the code or algorithm.
Disclaimer: If you haven't run the code above before, the benchmark won't work. and thus to run this first:

```
make mylib.o
```
to to see the time complexity of Fibonacci Iterative, you need to run this:
```
make timei
```
and then this:
```
./timei.out
```
then the program will ask you to put the number what you want.
```
Input the integer:10
```
Lastly, the program asks you to put the number what you want.
```
Time taken Fibonacci Iterative of 10 :0.000002 seconds 
```
To see the time complexity in Recursive Fibonacci, do this:
```
make timer
```
and 
```
./timer.out
```
same as last time the program ask for the input.
```
Input the Integer:10
```
and thus the program will display the results.
```
Time taken Fibonacci Recursive 10:0.000003 seconds 
```
# Space Complexity Benchmark
This will show the total space taken by the algorithm with respect to the input size.

Disclaimer: if you haven't run the code it wont works so just like the previous, run this code first.
```
make mylib.o
```
to check the space complexity of Fibonacci Iterative, run this code below:
```
make spacei
```
and then
```
./spacei.out
```
The program will display this
```
press Ctrl + C to interrupt the process
parameter: 100000
```
Lastly, To check the CPU Usage, go to task manager and find VmmemWSL.
<img width="461" alt="iterativefibonacci" src="https://user-images.githubusercontent.com/114371873/205090732-894bf2a8-ed38-4707-a18b-a92075810c2d.png">

To check the space complexity of the Fibonacci Iterative, run this code below:
```
make spacer
```
and then
```
./spacer.out
```
The program will display this.

```
press Ctrl + C to interrupt the process
parameter: 100000
```
And lastly, to check the CPU Usage, go to manager and find VmmemWSL.
<img width="457" alt="recursive fibonacci" src="https://user-images.githubusercontent.com/114371873/205093315-5583d7e5-524f-4702-9e96-13045d9ba750.png">
# Conclusion
In conclusion from this experiment the iterative method is much practical and faster solution in counting the fibonacci sequences, and to know the faster one is by checking the space complexity or the size of the program on above the bigger the file the more time complexity, and space complexity 
