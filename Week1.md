## Review
- What is Git?
>Type of version control
- What about GitHub? How are they related?
>Github hosts git so that everyone can have gui to see git requests
- What command moves changes from GitHub to our local repo?
>git clone <url>
- What command moves changes from our local repo to GitHub?
>1) git add <files that were changed>
>2) git commit -m "my message" // or omit the -m and will open editor of your choice 
>3) git push
- What two commands are used in sequence to save changes to our local repo?
>1) git add
>2) git commit
- What is BASH?
>shell program that emulates a command-line terminal interface and interprets user commands
- What does the PATH environment variable do?
>specifies a set of directories where executable programs are located (points your command to the executable)
- What is the JDK and what does it let us do?
>Java Development Kit - allows developers to create java programs that can be executed and run by JVM and JRE
>emphasis on that it is a package of tools for developing Java-based software
- What is the JRE and what does it let us do?
>Tools for running Java code
>Creates the JVM and ensures dependencies are available to your Java programs 
>software layer that runs on top of your OS and provides class libraries and other resources that a specific Java program needs to run 
- What's the name for the code written in .class files?
>bytecode which is instructions for the JVM
- How does Scala relate to Java?
>Scala is built on top of Java and therefore use JVM
- What is sbt (high level)?
>Scala build tool
- How does Scala relate to the JRE and JVM?
> JRE allows compile of scala code into bytecode which is translated by JVM to run actual program

- Is Scala statically or dynamically typed?
- Do we need to declare type for our variables in Scala? always?
- What are integer types in Scala?
- Decimal types?
- What is the size of an Int? a Double? (the default integer and decimal types)
- What is the difference between val and var?
- Why do we make use of programming paradigms like Functional Programming and Object Oriented Programming?
- What are the 4 pillars of OOP: Abstraction, Encapsulation, Inheritance, Polymorphism? (a bit on each)
- What are classes? Objects?
- What is the significance of the Object class in Scala?
- What does it mean that functions are first class citizens in Scala?
- What is a pure function?
- What is a side effect?
- What's the difference between an expression and a statement?
- Is if-else an expression or a statement in Scala?
- What's the difference between a while loop and a do-while loop?
- How does String interpolation work in Scala?
- How do operators work in Scala?  Where is "+" defined?
- What are the ways we could provide default values for a field?
- How do we define an auxiliary constructor?
- What is an enumeration?
- What is a REPL?
- How does the Scala REPL store the results of evaluated expressions?


- What is a higher order function?
- What is function composition?
- Why might we want to write an application using pure functions instead of impure functions?
- Why might we want mutable state (OOP) in our application?  Why might we want immutable state (FP)?
  - This question is open-ended, don't focus on finding the "right" answer
- What are some examples of side effects?
- What is a Lambda?
- How can we write Lambdas in Scala?
- What does map do?
- What does filter do?
- What does reduce do?
- What does it mean that a function returns Unit in Scala?
- What is recursion?
- What do we need to include in any effective recursive function?

- What is the Stack? What is stored on the Stack?
- What is the Heap? What is stored on the Heap?
- What is garbage collection?
- When is an object on the Heap eligible for garbage collection?
- How do methods executing on the stack interact with objects on the heap?
- Know the basics of the following Scala Collections: (mutable? indexed? when to use it?)
  - List
  - Set
  - Map
  - ArrayBuffer
  - Vector
- What is a generic?
  - the phrase "compile time type safety" is useful in this answer
- What is an Option?
- What is found inside an empty Option?
- How do we write an Option that contains a value?
- What are Exceptions?
- What are Errors?
- What is Throwable?
- How would we write code that handles a thrown Exception?
- How do we write code to throw an Exception?

- What does the src folder contain in an sbt project?
- the target folder?
- What is a Trait?
- What is a case class?
- What methods get generated when we declare a case class?
- What does the apply method do?
- What is a Thread?
- What is a Future?
- In what situations might we want to use multiple threads? (just some)
- How can we do something with the result of a Future?
- How does a Future return a value or exception?
- How does the onComplete callback function work?