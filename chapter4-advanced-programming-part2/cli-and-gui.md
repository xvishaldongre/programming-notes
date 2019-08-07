```
# Console and graphical user interface
```


    `Hello world` is probably the first class of a well-known programming language. When you start writing `Hello world` as an example in the book, you will quickly ask this question. 
    Looking back at the programs that I usually see, they usually have a title bar with menus and toolbars. You can use the mouse to click on it and it seems that there are many other functions. 
    But this program seems completely different, what is the problem? 
    Actually no problem, this is a console program.

    There are various programs in the world. 
    Almost all programs communicate with the user, accept the user's input, and output the results of the run, but the way they accept and output is different. The way the program communicates with the user is called the interface. 
    Remember the huge face of an early science fiction movie that appeared on a computer screen to talk to people? 
    Or the game called "茧" in "The Undead on Baker Street" - that is one of the interfaces. 
    In fact, this interface has not yet been realized, and human imagination can always lead a lot of actual technology.

    There are many kinds of interfaces, some programs do not need an interface, because they do not have to communicate with users at all, they communicate with other programs, you can call it no interface, a typical example is the driver, when did you see the driver running? ? 
    Generally, programs used under Windows and Mac OS X are called GUIs (GUI: Graphics User Interface), and there are also many GUI applications under Linux. 
    Simply put, all input and output are graphical. 
    It accepts graphical input from the user. For example, the user inputs coordinates and draws with a pointing device (mouse, trackball, tablet) and reflects the output of the program on a device that can display graphics, such as a monitor, printer, or head-mounted monitor. Usually, such programs provide menus, toolbars, etc., which are greatly convenient for the user. 
    This kind of program is straightforward, and can be easily used by ordinary users. Most of the tasks can be completed with a single click. 
    World of Warcraft and Word are typical GUI programs.

    Although the GUI program is easy for ordinary people to use, the programming of the graphical interface is quite complicated. 
    You can imagine how hard it is to draw everything on the display every time. 
    When the window moves and zooms, you need to redraw everything in the window; when multiple windows coexist, if your window is blocked by someone else's window (this is a very common situation), you need to control which parts of the window It is displayed and which is occluded; when the mouse moves, you need to cover the part covered by the mouse and redraw the mouse; when the mouse clicks, you need to judge the position of the mouse, and also judge that the click is your program. , or someone else's; when the mouse clicks on the menu, you have to determine whether it is a menu or a button, and which menu item, and then perform the corresponding operation. 
    All of these situations must be resolved one by one. 
    Some of them can be solved by the operating system, but you need to know how to use the resources provided by the operating system to make it work for you, and some have to find your own way, the problems make the programming of the graphical interface very complicated.

    At the same time, due to the needs of graphics processing, the graphical interface has higher requirements on computer hardware. 
    The beautiful 3D game is far more demanding than the Notepad program. 
    Although modern computers have long been able to meet these requirements, early computers were not as powerful. 
    So, in the early days (not very far, about the seventies and eighties of the last century), the interface of the program was not graphics, but characters. 
    The user inputs text on the keyboard, such as dir, the system finds the corresponding command, and then executes, and the result of the execution is also outputted in a line of text on the device that can output the text (of course, mainly the display), and the user reads the text. Go to the next step.

    Some modern sci-fi films, in the performance of hackers or the operation of advanced equipment (such as the US Department of Defense's nuclear weapons system), often appear when the operator is typing fast, and then suddenly a car, you are done, very There will be fewer cartoon menus and toolbars. 
    Think about the operator of the Matrix, have you seen him holding the mouse? 
    This method is called the Command Line Interface (CLI). Since the operator usually sits in front of a console, and this console can control the entire system, it is also called the Console Interface. . 
    The program running under the console is the console program; the system running the console program is called the console environment. 
    The console looks very advanced, cool and dazzling, and the hackers are very high-level when operating. In fact, it is easier to program. 
    Because you only have to process and output characters, the system will naturally place the characters in the appropriate position on the screen. 
    You don't have to worry about font size and color, but also the things that don't exist in windows, menus, and mice, just focus on the functionality of the program. 
    The computer system does not consume resources to draw pictures, and the system is naturally more efficient. 
    Therefore, as soon as the command line interface appears, it has been widely used, and its history is much older than the graphical interface. 
    Compared with GUI programs, command-line programs are usually not so beautiful, and they are not intuitive for ordinary users. 
    **But because of its efficiency and speed, the command-line program is still in use, and the command-line mode has not disappeared. On the contrary, many systems have strengthened this part of the function, such as [Windows PowerShell] under Windows7. (http://en.wikipedia.org/wiki/Windows_PowerShell), press the "Windows" logo button (the bottom left side of the keyboard is similar to a window pattern), enter PowerShell to try, enter ls 
    &
     tab after entering, can be like Linux The terminal is automatically complemented by 噢\~

    In many cases, people prefer to use the command line program to do some work, which is more obvious in BSD, Linux and other UNIX systems. 
    DOS is a standard console environment, Windows operating system, also provides a console environment, but even the chicken ribs are not as good. 
    There are also a lot of GUI programs, borrowing from the console mode, still retain the method of directly using the keyboard. 
    For example, Warcraft, almost every command has shortcuts to speed up the operation.

    In fact, many system administrators prefer console programs. In addition to being more efficient than graphical interface programs, there is another reason: to increase the implementation of an option, the console only needs to add an input character as a switch, and the graphical interface needs at least Add a button. 
    Think about it, is there more buttons that can be added on the screen or more characters that can be added? 
    ** So console programs tend to be more complex, as long as you remember the instructions. 
    **

    Let's open a console environment under Windows and use a few console programs to get a feel for it. 
    A separate screenshot will be shown in the appendix section of Linux. 
    If you are using Windows XP, click Start, find the program -
    >
     attachments, there is a shortcut called "Command Prompt", click to run it. 
    Similar to Windows7, you can also type `cmd` after clicking Start. You can also press and hold the "Windows" logo key and R at the same time, and enter `cmd` in the pop-up window.

    Did you see a window, no menu, no toolbar, only the title bar and the largest minimized button, this is the console environment under Windows, where you can run the console program. 
    Now type `dir` and press Enter. 
    You see the output, this is the console program running. 
    Just type the command and press Enter to run. 
    Run one again, `time`, one more, `ipconfig`. 
    Finally, one more, `help`. 
    He gives the various commands provided by the current system, you can try to see the prompts. 
    In fact, not only can you run these, try `notepad`, what did you find? 
    `explorer`, `calc`, etc. can all be run like this. 
    Play enough, ok, type `exit`, then press Enter, the console environment is closed. 
    Have you found that Windows is not friendly to the command line interface, compared to Linux and MAC OS, the command line interface is more friendly, so there will be software such as cygwin.

    The console program is easy to write and easy to understand, so for beginners, the console program is a good choice. 
    On the basis of learning the console program, it is easier to go to the window program.

    ## Graphical User Interface Programming

    Hackers prefer Console, but for the average user, the graphical interface is more familiar to them. 
    Most of us also like to write GUI programs, because it seems to be more friendly and seems more fulfilling, so how can we write GUI programs?

    For each operating system, a set of APIs is provided. If the system supports GUI, then there will be a graphics subsystem and a window management subsystem in its API. 
    The graphics subsystem includes the drawing of basic graphic elements, such as drawing point lines, displaying text pictures, and color rendering. The window management subsystem first includes the graphics subsystem, and then adds the drawing and window including the window and window components. Covering, moving adjustments, and the handling of events such as mouse clicks. 
    Under Windows, the graphics subsystem is called [GDI] (http://en.wikipedia.org/wiki/%E5%9B%BE%E5%BD%A2%E8%AE%BE%E5%A4%87%E6 %8E%A5%E5%8F%A3)(Graphics Device Interface). 
    In order to handle multimedia programming efficiently, Microsoft developed [DirectX] (http://en.wikipedia.org/wiki/DirectX) on the eve of Windows 95 release - in addition to graphics, it also integrates many other features, using it to come up with A lot of Windows games. 
    Another well-known graphics API is cross-platform 
    &
     cross-programming language [OpenGL] (http://zh.wikipedia.org/wiki/OpenGL), rendering ability is very strong! 
    !

    Also worth mentioning is Microsoft's WPF, which has been widely used for interface development since the release of Vista. WPF is an extension of the next-generation graphics API on the desktop. 
    Writing applications in WPF with higher visual quality, Win7's rich interface effects are largely due to the application of [WPF] (http://en.wikipedia.org/wiki/Windows_Presentation_Foundation).

    Even with the graphical library window management library, GUI programming is quite cumbersome. 
    The first is that to complete a job, you must fill in a lot of step-by-step code, and the code is repeated inside the program and between the programs, which suggests that people should further abstract the graphics library. 
    To put it simply, it is necessary to make a module for drawing a quadratic curve on the basis of drawing a line drawing function. 
    Fortunately, these jobs have already been completed, and there is more than one. 
    These things are based on functional strength, some are called graphical user interface libraries, and some are called application frameworks. 
    Under Windows, people using VC++ can choose [MFC] (http://en.wikipedia.org/wiki/VC%2B%2B) [ATL] (http://en.wikipedia.org/wiki/Active_Template_Library) If you choose the .NET camp, [.NET Framework] (http://en.wikipedia.org/wiki/.NET%E6%A1%86%E6%9E%B6) is your best choice, combined with C \# Development is more convenient.

    If you want the program to be used more than Windows, then cross-platform [Qt] (http://en.wikipedia.org/wiki/Qt), [GTK+](http://en.wikipedia.org/wiki/GTK% 2B), [wxWidgets] (http://en.wikipedia.org/wiki/WxWidgets) is a good choice for you. 
    They ensure proper efficiency while properly abstracting and smoothing the differences in the underlying operating system. 
    For those who are learning C++, the above libraries are available, and of course there are other language support -- such as Python. 
    These three platforms have relatively more information about QT, but there are certain copyright problems, but there is no problem with personal use.



