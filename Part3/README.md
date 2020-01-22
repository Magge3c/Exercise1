# Reasons for concurrency and parallelism


To complete this exercise you will have to use git. Create one or several commits that adds answers to the following questions and push it to a repository to complete the task. Remember to also submit your answers to Blackboard

When answering the questions, remember to use all the resources at your disposal. Asking the internet isn't a form of "cheating", it's a way of learning.

 ### What is concurrency? What is parallelism? What's the difference?
 > The defenition of concurrency is that multiple computations are computed simultaniously. E.g. Multiple computers on a network, multiple applications on a computer, multiple cores or processes on a computer or a single chip.
 
> In parallelism executions of precesses are carried out simultaneously. E.g. bit-level, instruction-level, data and task parallelism. Often the processes are subtasks or subprocesses of a larger process. 

> These terms are closly related, but there is a difference. In parallelism, a computational task is typically broken down into several, often many, very similar sub-tasks that can be processed independently and whose results are combined afterwards, upon completion. 
And for concurrency, the various processes often do not address related tasks, but if they do, they might require inter-process communication during excecution.
 
 ### Why have machines become increasingly multicore in the past decade?
 > By Moore's law the amount of transistors, hence the amount of power, in a chip doubled every year. But in the past decade the amount of energy has increased to a point where the chip would overheat or melt during use. Multiple cores has sucessfully been implemented to circumvent this problem in the last decade.
 
 ### What kinds of problems motivates the need for concurrent execution?
 (Or phrased differently: What problems do concurrency help in solving?)
 > Limited resource problems
 > Lost updates
 > Uncommitted Data
 > Inconsistent Retrievals
 
 ### Does creating concurrent programs make the programmer's life easier? Harder? Maybe both?
 (Come back to this after you have worked on part 4 of this exercise)
 > *Your answer here*
 
 ### What are the differences between processes, threads, green threads, and coroutines?
 > *Your answer here*
 
 ### Which one of these do `pthread_create()` (C/POSIX), `threading.Thread()` (Python), `go` (Go) create?
 > *Your answer here*
 
 ### How does pythons Global Interpreter Lock (GIL) influence the way a python Thread behaves?
 > *Your answer here*
 
 ### With this in mind: What is the workaround for the GIL (Hint: it's another module)?
 > *Your answer here*
 
 ### What does `func GOMAXPROCS(n int) int` change? 
 > *Your answer here*
