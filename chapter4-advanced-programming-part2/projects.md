```
#工程与单文件的关系
```

```

One obvious thing is that when a software project becomes very large, it is unrealistic to use just one file to complete all the content. 
Take the game of "World of Warcraft" as an example. The game needs materials such as sound, animation, and pictures. It also needs different modules such as map editing, artificial intelligence, and light and shadow rendering. In the production, different departments need to be different. The work, the files and tools used in the work are different, it is impossible to generate the same file. 
At this time, there is a problem of coordination. 
Therefore, for large development tools, they are not processed on a per-file basis, but on a project basis. 
A development project consists of one to several projects, each project contains a large number of files, source code, resources such as picture music used by the program, and various parameters that need to be recorded at compile time. 
The entire project must be fully compiled for each compilation (of course, in the optimization state, only the part of the update change can be considered).

Obviously the project is necessary for the writing of large projects like World of Warcraft, but in the small program of the novice practice, using the project is like you just want to put a nest for your puppy at home, but it pulls the whole China Yangtze River Three Gorges Project Development Corporation is really a bit of a big problem. 
Moreover, in the future we have to write a lot of such small programs, if each new project, how many junk files will be generated! 
So, we need a way to compile only a single file. 
Fortunately, no matter which development tool, they provide such a method. 
Although this method usually does not appear directly on the menu, it is indeed a common and correct method.

### Functions, APIs, Classes, Controls, Development Kits, and Software Reuse

It is also obvious that as engineering projects become more and more vast, it is unrealistic and unrealistic to write a project from scratch every time. 
We noticed that both the program and the source code have the following two features. 
First, they are the result of human intelligence. Each line of source code embodies the programmer's ingenuity and costs the developer's time and money. 
Second: Almost every line of source code itself can be copied to another location at no cost, another block of code, another program, or even another project. 
Based on this feature, we realize that if we can reuse the programs and source code that have already been written, especially those that have been proven to be robust and correct in use, we can save huge manpower, material resources and time. 
Even if you can only use a small part of it, it is a great achievement, which is called software reuse.

The most important benefit of software reuse is that it allows programmers to stop putting limited intelligence on long-solved problems, but to devote themselves to new problems: ** Don't reinvent the wheel. 
** An important reason for open source is for software reuse. 
An effective way to reuse software is to use functions. 
The so-called function is to combine some code segments with fixed functions and give a name. 
When you need these features, just fill in the name of the function in the appropriate place. 
Using functions instead of hand-made in programming is like using bricks instead of clay in the building – it's no small improvement. 
The bricks used in building the building can be manufactured by themselves or purchased on the market. 
Purchased bricks, although with some differences, always follow certain common characteristics. 
Although these bricks are used in pieces, they are always purchased in large quantities. 
The same is true for functions. There are always professional companies in the market that provide functions for sale. The functions they sell are grouped together according to functions and become function libraries. 
Although the libraries of different companies may have the same name and function, the internals are different.

Most modern programming languages ​​specify a library of functions while specifying the syntax and vocabulary of the language itself (including the use of functions, of course). 
This library only specifies the name and purpose of each function. 
As for the specific implementation of the function, some are directly defined by the language itself, and some are provided by the manufacturer of the compiler that implements the language. 
Users who use this language can use it whenever they need it, without having to worry about problems inside the library, which greatly improves efficiency. 
This library is called the standard function library. 
Often, off-the-shelf libraries are proven to be efficient and robust through a lot of practice tests, and are much more useful than their own hands-on functions. 
** So make full use of existing libraries, especially standard libraries, where possible. 
One of the reasons why the C language is so powerful is that it has a powerful and complete library of standard functions. 
Python is also a powerful language with a powerful standard library and countless third-party libraries! 
The functions of third-party libraries cover many areas of scientific computing, web development, database interfaces, and graphics systems.

Software is usually run under the operating system. From the perspective of software reuse, if the operating system can provide some common services, the program can concentrate on doing its own thing. 
These services include file reading and writing, device operations, network communication, window drawing, and more. 
Otherwise, the program will waste a lot of energy on these basic tasks. 
Fortunately, almost all modern operating systems offer such services. 
These services come in the form of functions that the program uses, just like using functions. 
These system services in the form of functions are called Application Programing Interfaces. 
Unfortunately, the APIs provided by different operating systems are usually different. 
When a program written using an operating system's API is moved to another operating system, the API cannot be run because it cannot correspond to each other. 
This is one of the reasons why programming is targeted at the platform.

Some large programs, such as Autodesk's AutoCAD, offer the possibility of programming changes when you are dissatisfied with some of its features or feel better, compared to the first development, this is called secondary development. . 
At the time of secondary development, the services provided by the original program are also called APIs.

It's really convenient to use bricks to build a building, but if you can use prefabricated panels, it's more convenient! 
A program module that can be reused one level higher than a function is called a class. The use of a class is more complicated than a function, but it can be more widely reused and is a more advanced form of software reuse. 
Classes can also be aggregated into class libraries. 
The ability to use the language of the class will dictate the standard class library. 
C++ is more powerful and harder to learn than C. One reason is that C++ has a complete and powerful standard library in addition to C's library. 
In the class library, there is a very special class called control. 
Controls are especially useful in fast window development, which enables drag-and-drop programming. 
For example, if you want to write a window program with a button, then just create a window program project, this project will bring a window control, and directly display in the workspace, and then use the mouse to put the button control from Drag the control panel to the desired position in the window and the button will be placed. 
As for the function corresponding to the button, the programmer needs to programmatically implement it. 
After compiling and running in the future, the appearance of the program will be exactly the same as the design. 
The control greatly improves the programming efficiency, but because it needs to automatically generate some code, it needs the support of the editing environment. The editing environment that supports the control is generally less. 
The sum of the controls is the control library.

All of these, functions, APIs, classes, and even controls, must be developed, just like the luggage that must be carried when traveling, so they are collectively referred to as the Development Kit (SDK: Software Development Kit).

Some development kits come with the compiler, such as the standard library, etc. Some packages are provided by third-party vendors. 
Most development kits require support from the integrated development environment (with compiler), some require the compiler to provide internal implementation, some require the compiler to give the connection, and some require the compiler to generate code. 
Different compilers provide different methods, which creates differences between compilers and sometimes even causes a development kit to not be used on a compiler. 
In order to further improve the programmer's work efficiency, many integrated development environments have invented other methods, which is equivalent to directly using a house to be stacked together to make a residential building. You can finish it almost by brushing the exterior paint. This is called the application framework. 
Unfortunately, the methods of different vendors are fundamentally different, which further expands the gap between integrated development environments. 
Regardless of the future, at least for now, the scale of programming is getting bigger and bigger, and more and more people need wisdom. 
Everyone's wisdom is limited, should not be wasted, and make full use of everyone's wisdom to achieve maximum success. 
Software reuse is one way to integrate the wisdom of everyone. 
From the first day of your programming, please keep in mind: ** Software reuse**. 
To reuse 
&
 reuse 
&
&
 reuse.

### Function, API, library summary

The equivalent of historical allusions, proverbs, and cultural backgrounds are the interfaces and libraries on various compilers and platforms. 
Suppose now that there is a program to read and write files, don't mistakenly think that you need to write a program to control the head expansion of the hard disk, or the lens movement of the optical drive or the address of the USB disk, unless you want to be a Linux or Windows Operating system. 
Otherwise, all file operations, network communication, and human-machine interface are ready-made modules provided by the operating system, and are only waiting for you to use them. 
These modules are often referred to as APIs (Application Programming Interfaces), and different operating systems provide different APIs. 
On the basis of the interface, many compilers and programmers have further packaged the libraries, and you can use these libraries more easily than directly using the interface to achieve the same functionality.

Because of the inconsistency of the system, the compiler is different, so before the library, you must first determine the platform and environment you want to work on, as well as the application direction. 
The libraries for editing games under Windows and the databases for doing databases under Linux are quite different. 
Then there is the same set of steps, looking for teaching materials and doing exercises. 
This textbook is usually the official document. The Unix/Linux platform has a large number of documents distributed on the man page and various manuals. The best and most complete under Windows is MSDN. Other platforms search for themselves. 
You can go to the exercises, but the better solution is to find a practical small application that is unmatched in its use. 
Writing a QQ or BT will definitely give you a good grasp of the network operations. 
There are many open source projects on the web, and you are interested to find it yourself.

The learning library and learning algorithms can be performed simultaneously, and you are already a qualified or even good programmer when you complete these two phases.

Excellent literary works have a common feature. Although they are based on different national cultures, they are concerned with the common thoughts and feelings of all mankind, reflecting the ultimate humanistic concern. We will all be in *The Old Man and the Sea*. The touch of Santiago is not what it is. 
**Excellent programs, although applied in different directions and different platforms, must be fully compliant with computer principles and presented with the most reasonable mathematical models. 
** If you want to be a qualified programmer, the computer composition principle and related mathematics are the theoretical lessons that must be supplemented.

In addition to reading and doing the work, there is another content that is indispensable, that is, reading other people's programs. 
No writer doesn't read a lot of other people's works, and you can also draw nutrition from other people's code. 
Code is all about the program, it is the real implementation method, everything is in the code, and sometimes even a long and cumbersome description is not as clear as a few lines of code. 
Today's programmers are fortunate, and the development of the open source movement has enabled them to get the world's best and actually working code for free and in almost any application. 
As long as you have the heart, you can find any code you want. 
But reading the code is also a test of your perseverance. Reading good code is a pleasure. 
But please read the code that is comparable to your level. The gap will be a serious physical and psychological blow. 
You won't tell me that you want to be proficient in the Linux kernel before you even learn C?

The episode of the extraordinary theme is actually the application direction of your program. 
If you are practicing before, then now is the time for your own innovation. 
Many people just passively do something that they don't like and have no value for their wages under the arrangement of the boss. A few people have the opportunity to do what they like. 
Think about it, 3DMAX, WOW, Firefox, Nginx, Linux, and even Mac OS X are all well-known programs, and maybe your program will be as well known as they are. 
However, I still have to pour cold water on you. This requires unremitting efforts, a keen eye and a small amount of luck. Only a handful of programmers can do this. 
However, there are dreams to keep moving forward, isn't it? 
:-)
```



