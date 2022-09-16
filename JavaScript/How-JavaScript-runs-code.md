## There are four main things involved in the code execution of JavaScript.
1. Thread of Execution.
2. Memory.
3. Execution Context of Functions.
4. Call Stack.

### Thread of Execution
When JavaScript runs code it goes through line by line and executes each line this process is known as the thread of execution.
### Memory
While the thread of execution encounters any variables in its process it stores them in a place known as memory. Thread of execution stores variables in memory with their labels so they can be called or used again.<br>
Strings, integers, objects etc all of them are stored in memory while functions are also stored in memory when they are declared and when they are called using 
functionName()
they run code that was stored in memory.
### Execution Context
Execution context is needed for every function to execute. It consists of two main parts <br>
**Thread of execution <br>
 Memory<br>**
We have already seen them in action before. There is always a global execution context with global memory
and when a function executes it creates its own execution context besides the global execution context with its own local variables but it has also access to global memory.
### Call Stack
JavaScript keeps track of functions using a call stack. A call stack is the same as a stack data instruction it is FILO. It means that when JavaScript executes a function it adds it to the call stack when that function is done executing JavaScript removes it from the stack. <br>
This means that JavaScript is single-threaded as it has only a call stack to work with so it can run only one function at a time.

