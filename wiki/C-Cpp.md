
# C/Cpp

----

* [GCC, the GNU Compiler Collection](http://gcc.gnu.org/)
* [C++ Language Tutoral](http://www.cplusplus.com/doc/tutorial/)
    [C++ 基础教程](http://www.prglab.com/)
* [老手是这样教新手编程的](http://coolshell.cn/?p=2420)
* [Linux之父炮轰C++：糟糕程序员的垃圾语言](http://blog.csdn.net/turingbook/archive/2007/09/07/1775488.aspx)
* [C 语言常见问题集 (中文)](http://c-faq-chn.sourceforge.net/)
* [Linux 常用 C 函数(中文版)](http://net.pku.edu.cn/~yhf/linux_c/)
* [C Programing](http://www.cprogramming.com/)
* [The Biggest Changes in C++11 (and Why You Should Care)](http://www.softwarequalityconnection.com/2011/06/the-biggest-changes-in-c11-and-why-you-should-care/)

## Note

《学习linux/unix编程方法的建议》
http://www.chinaunix.net/jh/23/1070966.html
作者:zhlzn  发表于：2009-07-03 08:54:13

首先先学学编辑器，vim, emacs什么的都行。
然后学make file文件，只要知道一点就行，这样就可以准备编程序了。

然后看看《C程序设计语言》K&R，这样呢，基本上就可以进行一般的编程了，顺便找本数据结构的书来看。

如果想学习UNIX/LINUX的编程，《APUE》绝对经典的教材，加深一下功底，学习《UNP》的第二卷。这样基本上系统方面的就可以掌握了。

然后再看Douglus E. Comer的《用TCP/IP进行网际互连》第一卷，学习一下网络的知识，再看《UNP》的第一卷，不仅学习网络编程，而且对系统编程的一些常用的技巧就很熟悉了，如果继续网络编程，建议看《TCP/IP进行网际互连》的第三卷，里面有很多关于应用协议telnet、ftp等协议的编程。
如果想写设备驱动程序，首先您的系统编程的接口比如文件、IPC等必须要熟知了，再学习《LDD》2。

对于几本经典教材的评价：

《The C Programing Language》K&R 经典的C语言程序设计教材，作者是C语言的发明者，教材内容深入浅出。虽然有点老，但是必备的一本手册，现在有时候我还常翻翻。篇幅比较小，但是每看一遍，就有一遍的收获。另外也可用谭浩强的《C语言程序设计》代替。

《Advanced Programing in Unix Envirement》 W.Richard Stevens：也是非常经典的书（废话，Stevens的书哪有不经典的！），虽然初学者就可以看，但是事实上它是《Unix Network Programing》的一本辅助资料。国内的翻译的《UNIX环境高级编程》的水平不怎么样，现在有影印版，直接读英文比读中文来得容易。

《Unix Network Programing》W.Richard Stevens：第一卷讲BSD Socket网络编程接口和另外一种网络编程接口的，不过现在一般都用BSD Socket，所以这本书只要看大约一半多就可以了。第二卷没有设计到网络的东西，主要讲进程间通讯和Posix线程。所以看了《APUE》以后，就可以看它了，基本上系统的东西就由《APUE》和《UNP》vol2概括了。看过《UNP》以后，您就会知道系统编程的绝大部分编程技巧，即使卷一是讲网络编程的。国内是清华翻译得《Unix网络编程》，翻译者得功底也比较高，翻译地比较好。所以建议还是看中文版。

《TCP/IP祥解》一共三卷，卷一讲协议，卷二讲实现，卷三讲编程应用。我没有怎么看过。，但是据说也很经典的，因为我没有时间看卷二，所以不便评价。

《用TCP/IP进行网际互连》Douglus.E.Comer 一共三卷，卷一讲原理，卷二讲实现，卷三讲高级协议。感觉上这一套要比Stevens的那一套要好，就连Stevens也不得不承认它的第一卷非常经典。事实上，第一卷即使你没有一点网络的知识，看完以后也会对网络的来龙去脉了如指掌。第一卷中还有很多习题也设计得经典和实用，因为作者本身就是一位教师，并且卷一是国外研究生的教材。习题并没有答案，留给读者思考，因为问题得答案可以让你成为一个中级的Hacker，这些问题的答案可以象Douglus索取，不过只有他只给教师卷二我没有怎么看，卷三可以作为参考手册，其中地例子也很经典。如果您看过Qterm的源代码，就会知道Qterm的telnet 实现部分大多数就是从这本书的源代码过来的。对于网络原理的书，我推荐它，而不是Stevens的《TCP/IP祥解》。

《Operating System - Design and Implement》这个是讲操作系统的书，用Minix做的例子。作者母语不是英文，所以英文看起来比较晦涩。国内翻译的是《操作系统 设计与实现》，我没看过中文版，因为翻译者是尤晋元，他翻译的《APUE》已经让我失望头顶了。读了这本书，对操作系统的底层怎么工作的就会
有一个清晰的认识。

《Linux Device Driver》2e ，为数不多的关于Linux设备驱动程序的好书。不过内容有些杂乱，如果您没有一些写驱动的经验，初次看会有些摸不着南北。国内翻译的是《Linux设备驱动程序》第二版，第一版，第二版的译者我都有很深的接触，不过总体上来说，虽然第二版翻译的有些不尽人意，但是相比第一版来说已经超出了一大截。要读这一本书，至少应该先找一些《计算机原理》《计算机体系结构》的书来马马虎虎读读，至少应该对硬件和计算机的工作过程有一些了解。

* DLL
    * [Building and Using DLLs](http://www.cygwin.com/cygwin-ug-net/dll.html)

## 编译器/编辑器(Compiler,IDE,Editor)

* [MinGW](http://www.mingw.org/)
* [Cygwin](http://www.cygwin.com/) [2](http://sourceware.org/cygwin/)
* [Dev-Cpp](http://sourceforge.net/projects/dev-cpp/)


## Tools

* [Doxygen](http://www.stack.nl/~dimitri/doxygen/) [doxygen.org](http://www.doxygen.org) [doxygen.sf.net](http://sourceforge.net/projects/doxygen/)
* [doxygen+VIM文档实用指南for C/C-liked Programmers](http://blog.csdn.net/clarkZHUO/archive/2006/12/31/1471573.aspx)


## RegExp

* [boost](http://www.boost.org/)
* [PCRE](http://www.pcre.org/)
* [Text Processing Library(TPL)](http://code.google.com/p/libtpl/)
    ![pic](http://cpp.winxgui.com/cn:tpl-1-0-00)
* [deelx](http://www.regexlab.com/)
* [C++ 正则表达式](http://msdn.microsoft.com/zh-cn/library/4384yce9.aspx)


## Books

* [Advanced Programming in the UNIX Environment](http://www.kohala.com/start/apue.html) - Addison-Wesley.
    [@github](http://github.com/mantovani/apue)
* [UNIX Network Programming](http://www.kohala.com/start/unpv12e.html)
* [C语言编程](http://book.douban.com/subject/1786294/)

## Blog

* [云风的 BLOG](http://blog.codingnow.com/)
* [孩子气 | C++, Lua, 大连,程序员-sunxiunan](http://sunxiunan.com/)