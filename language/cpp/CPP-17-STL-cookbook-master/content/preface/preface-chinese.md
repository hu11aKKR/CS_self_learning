# 前言 

《C++17 STL Cookbook》将结合C++代码实例和标准库(STL)，教会你如何充分使用C++17。这里要说明的是，本书会尽可能的去使用STL，从而教会大家使用C++17。

C++是一门伟大且具有力量的语言。它使用简单的高级接口，将隐藏复杂的解决方式隐藏于背后，不过这样就意味着需要编写高效和低开销的底层代码实现。国际标准化组织(ISO)C++标准委员会致力于改进C++标准。C++11标准为C++带来了大量不错的特性，C++14和C++17也为C++加入了些新的特性。

目前为止，C++作为一门编程语言提供了语言相应的语言特性个标准库工具，用于处理复杂的标准数据结构和算法，包括：智能指针、Lambda表达式、常量表达式、便捷式可控线程的并发编程、正则表达式、随机数发生器、异常、可变参数模板(C++的部分模板类是图灵完备的!)、自定义文字、便捷式文件系统遍历等等。这些功能使它成为一种通用的语言，并在软件行业的所有领域，用于实现高质量和高性能的软件。

不过，很多编程者只将C++当做一门编程语言学习，而不太重视标准库(STL)的使用。不使用C++所带的标准库，将会让C++看起来就像是具有class的C语言，21世纪的现代化程序不应该写成这样。并且，这样的使用令人沮丧，就像是卸掉了它的一条手臂一样。

Bjarne Stroustrup(C++之父)在他的《C++程序设计语言》(C++11版本)中写到

> 请牢记，标准库和语言功能都是为了支撑以软件质量为目标的编程技术。他们应被组合起来发挥作用——如同建房子的砖块——而非个别地采用来相对孤立地去解决某个特定问题。

这段话能很明确的概括我写这本书的目的。本书的所有例子都与实际息息相关，处理这些问题时，只依赖与STL，不依赖其他的库。少了其他库的依赖，就能很容易的将程序运行起来，不必去为开发环境所困扰。 我希望你们受这些例子的启发，找到使用标准库的灵感，用伟大的编程语言作为解决更高级问题的基石。