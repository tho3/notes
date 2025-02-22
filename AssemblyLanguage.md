References for Assembly language.

* http://www.egr.unlv.edu/~ed/assembly64.pdf   x86-64  Assembly Language Programming with Ubuntu
* https://www.tutorialspoint.com/assembly_programming/assembly_tutorial.pdf  Assembly language tutorial
* https://www.ic.unicamp.br/~pannain/mc404/aulas/pdfs/Art%20Of%20Intel%20x86%20Assembly.pdf  The art of assembly language 
* https://johv.dk/blog/bare-metal-assembly-tutorial.html Getting started with bare-metal assembly

Assembly for DOS

* http://www.asmcommunity.net/forums/board/?id=113 ASM Community
* http://qzx.com/pc-gpe/  PC Game Programmer's Encyclopedia


Software optimization
* [Software optimization](https://www.agner.org/optimize/?e=0#testp)
* [AsmUtils](http://asm.sourceforge.net/asmutils.html)  Unix tools written in assembly language.


###Assembly syntax.

There are 2 major one. Intel and AT&T syntax.  Most of the assembler use the Intel syntax for Windows based system,  AT&T syntax used in UNIX environment 
See https://stackoverflow.com/questions/972602/limitations-of-intel-assembly-syntax-compared-to-att 

Some real life optimization. https://stackoverflow.com/questions/25078285/replacing-a-32-bit-loop-counter-with-64-bit-introduces-crazy-performance-deviati?rq=1
Good explanation of AT&T syntax https://stackoverflow.com/questions/4193827/questions-about-att-x86-syntax-design?rq=1

A lot of application had dependency in C library.  https://stackoverflow.com/questions/21290997/is-it-possible-to-convert-c-to-asm-without-link-libc-on-linux?noredirect=1&lq=1  One can ask the compiler to generate the assembly equivalent of the code for educational purpose.

###NASM
https://cs.lmu.edu/~ray/notes/nasmtutorial/
https://liberoscarcelli.net/courses/reverse-engineering/beginners/reverse-engineering-for-beginners/
[NASM x86 assembly language](https://asmtutor.com/) 
[NASM examples](http://libra.cs.virginia.edu/~aaron/08-nasm/nasmexamples.html)
[Another one](https://www.tutorialspoint.com/assembly_programming/index.htm)



### fasm
* [FASM/C++ VS2015 Linking static library](https://www.reddit.com/r/learnprogramming/comments/4zjyrt/fasmc_vs2015_linking_static_library/)
* [eXos](https://github.com/gwoplock/ExOS)
* [XBasic](https://www.github.com/RinkuruAi/XBASIC)
* [Manual](https://flatassembler.net/docs.php?article=manual)
* [FAQ](https://board.flatassembler.net/topic.php?t=2530)
* [tutorial](https://gpfault.net/posts/asm-tut-0.txt.html)

### Linux syscall, it does not use x80
* [x86 calling convention](https://en.wikipedia.org/wiki/X86_calling_conventions#System_V_AMD64_ABI)
* [Linux system call](https://blog.rchapman.org/posts/Linux_System_Call_Table_for_x86_64/)
