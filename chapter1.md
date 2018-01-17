# Introduction to c++

###### （Excerpt from Wikipedia\)

### What is C++?

C++\(C plus plus\) is a general-purpose programming language. It has imperative, object-oriented and generic programming features, while also providing facilities for low-level memory manipulation.

It was designed with a bias toward system programming and embedded, resource-constrained and large systems, with performance, efficiency and flexibility of use as its design highlights. C++ has also been found useful in many other contexts, with key strengths being found useful in many other contexts, with key strengths being software infrastructure and resource-constrained applications,including [desktop applications](https://en.wikipedia.org/wiki/Application_software), servers \(e.g.[e-commerce](https://en.wikipedia.org/wiki/E-commerce),[web search](https://en.wikipedia.org/wiki/Web_search_engine) or [SQL](https://en.wikipedia.org/wiki/SQL) servers\), and performance-critical applications \(e.g.[telephone switches](https://en.wikipedia.org/wiki/Telephone_switches) or [space probes](https://en.wikipedia.org/wiki/Space_probes)\).[\[7\]](https://en.wikipedia.org/wiki/C%2B%2B#cite_note-applications-7)C++ is a [compiled language](https://en.wikipedia.org/wiki/Compiled_language), with implementations of it available on many platforms. Many vendors provide [C++ compilers](https://en.wikipedia.org/wiki/List_of_compilers#C.2B.2B_compilers), including the [Free Software Foundation](https://en.wikipedia.org/wiki/Free_Software_Foundation),[Microsoft](https://en.wikipedia.org/wiki/Microsoft),[Intel](https://en.wikipedia.org/wiki/Intel), and [IBM](https://en.wikipedia.org/wiki/IBM).

C++ is standardized by the [International Organization for Standardization](https://en.wikipedia.org/wiki/International_Organization_for_Standardization)\(ISO\), with the latest standard version ratified and published by ISO in December 2017 as [ISO/IEC 14882](https://en.wikipedia.org/wiki/C%2B%2B#Standardization):2017\(informally known as [C++17](https://en.wikipedia.org/wiki/C%2B%2B17)\).[\[8\]](https://en.wikipedia.org/wiki/C%2B%2B#cite_note-isocpp2017-8)The C++ programming language was initially standardized in 1998 as ISO/IEC 14882:1998, which was then amended by the [C++03](https://en.wikipedia.org/wiki/C%2B%2B03),[C++11](https://en.wikipedia.org/wiki/C%2B%2B11) and [C++14](https://en.wikipedia.org/wiki/C%2B%2B14) standards. The current [C++17](https://en.wikipedia.org/wiki/C%2B%2B17) standard supersedes these with [new features](https://en.wikipedia.org/wiki/C%2B%2B17) and an enlarged [standard library](https://en.wikipedia.org/wiki/C%2B%2B#Standard_library). Before the initial standardization in 1998, C++ was developed by [Bjarne Stroustrup](https://en.wikipedia.org/wiki/Bjarne_Stroustrup) at [Bell Labs](https://en.wikipedia.org/wiki/Bell_Labs) since 1979, as an extension of the [C language](https://en.wikipedia.org/wiki/C_%28programming_language%29) as he wanted an efficient and flexible language similar to C, which also provided high-level features for program organization.[C++20](https://en.wikipedia.org/wiki/C%2B%2B20) is the next planned standard thereafter.

Many other programming languages have been influenced by C++, including [C\#](https://en.wikipedia.org/wiki/C_Sharp_%28programming_language%29),[D](https://en.wikipedia.org/wiki/D_%28programming_language%29),[Java](https://en.wikipedia.org/wiki/Java_%28programming_language%29), and newer versions of C.



### History of C++

In 1979,[Bjarne Stroustrup](https://en.wikipedia.org/wiki/Bjarne_Stroustrup), a Danish [computer scientist](https://en.wikipedia.org/wiki/Computer_scientist), began work on "C with [Classes](https://en.wikipedia.org/wiki/Class_%28computer_programming%29)", the predecessor to C++.[\[9\]](https://en.wikipedia.org/wiki/C%2B%2B#cite_note-invention3-9)The motivation for creating a new language originated from Stroustrup's experience in programming for his Ph.D. thesis. Stroustrup found that [Simula](https://en.wikipedia.org/wiki/Simula) had features that were very helpful for large software development, but the language was too slow for practical use, while [BCPL](https://en.wikipedia.org/wiki/BCPL) was fast but too low-level to be suitable for large software development. When Stroustrup started working in [AT&T Bell Labs](https://en.wikipedia.org/wiki/AT%26T_Bell_Labs), he had the problem of analyzing the [UNIX](https://en.wikipedia.org/wiki/Unix)[kernel](https://en.wikipedia.org/wiki/Kernel_%28computer_science%29) with respect to [distributed computing](https://en.wikipedia.org/wiki/Distributed_computing). Remembering his Ph.D. experience, Stroustrup set out to enhance the [C](https://en.wikipedia.org/wiki/C_%28programming_language%29) language with [Simula](https://en.wikipedia.org/wiki/Simula)-like features.[\[10\]](https://en.wikipedia.org/wiki/C%2B%2B#cite_note-evolving-10)C was chosen because it was general-purpose, fast, portable and widely used. As well as C and Simula's influences, other languages also influenced C++, including [ALGOL 68](https://en.wikipedia.org/wiki/ALGOL_68),[Ada](https://en.wikipedia.org/wiki/Ada_%28programming_language%29),[CLU](https://en.wikipedia.org/wiki/CLU_%28programming_language%29) and [ML](https://en.wikipedia.org/wiki/ML_%28programming_language%29).

Initially, Stroustrup's "C with Classes" added features to the C compiler, Cpre, including [classes](https://en.wikipedia.org/wiki/Class_%28computer_programming%29),[derived classes](https://en.wikipedia.org/wiki/Derived_class),[strong typing](https://en.wikipedia.org/wiki/Strong_typing), [inlining](https://en.wikipedia.org/wiki/Inlining) and [default arguments](https://en.wikipedia.org/wiki/Default_argument).[\[11\]](https://en.wikipedia.org/wiki/C%2B%2B#cite_note-hopl2-11)

In 1983, "C with Classes" was renamed to "C++" \(`++`being the [increment operator](https://en.wikipedia.org/wiki/Increment_operator) in C\), adding new features that included [virtual functions](https://en.wikipedia.org/wiki/Virtual_function), function name and [operator overloading](https://en.wikipedia.org/wiki/Operator_overloading), references, constants, type-safe free-store memory allocation \(new/delete\), improved type checking, and BCPL style single-line comments with two forward slashes \(`//`\). Furthermore, it included the development of a standalone compiler for C++,[Cfront](https://en.wikipedia.org/wiki/Cfront).

In 1985, the first edition of [The C++ Programming Language](https://en.wikipedia.org/wiki/The_C%2B%2B_Programming_Language) was released, which became the definitive reference for the language, as there was not yet an official standard.[\[12\]](https://en.wikipedia.org/wiki/C%2B%2B#cite_note-1st-edition3-12)The first commercial implementation of C++ was released in October of the same year.[\[9\]](https://en.wikipedia.org/wiki/C%2B%2B#cite_note-invention3-9)

In 1989, C++ 2.0 was released, followed by the updated second edition ofThe C++ Programming Language in 1991.[\[13\]](https://en.wikipedia.org/wiki/C%2B%2B#cite_note-2nd-edition3-13)New features in 2.0 included multiple inheritance, abstract classes, static member functions,[const member functions](https://en.wikipedia.org/wiki/Const_correctness), and protected members. In 1990,The Annotated C++ Reference Manual was published. This work became the basis for the future standard. Later feature additions included [templates](https://en.wikipedia.org/wiki/Template_%28programming%29),[exceptions](https://en.wikipedia.org/wiki/Exception_handling),[namespaces](https://en.wikipedia.org/wiki/Namespaces), new [casts](https://en.wikipedia.org/wiki/Cast_%28computer_science%29), and a [boolean type](https://en.wikipedia.org/wiki/Boolean_datatype).

After the 2.0 update, C++ evolved relatively slowly until, in 2011, the [C++11](https://en.wikipedia.org/wiki/C%2B%2B11) standard was released, adding numerous new features, enlarging the standard library further, and providing more facilities to C++ programmers. After a minor [C++14](https://en.wikipedia.org/wiki/C%2B%2B14) update released in December 2014, various new additions were introduced in [C++17](https://en.wikipedia.org/wiki/C%2B%2B17), and further changes planned for 2020.[\[14\]](https://en.wikipedia.org/wiki/C%2B%2B#cite_note-herbsutter.com-14)

As of 2017, C++ remains the third most popular programming language, behind [Java](https://en.wikipedia.org/wiki/Java_%28programming_language%29) and C.[\[15\]](https://en.wikipedia.org/wiki/C%2B%2B#cite_note-15)[\[16\]](https://en.wikipedia.org/wiki/C%2B%2B#cite_note-16)

On January 3, 2018, Stroustrup was announced as the 2018 winner of the [Charles Stark Draper Prize](https://en.wikipedia.org/wiki/Charles_Stark_Draper_Prize) for Engineering, which comes with $500,000, "for conceptualizing and developing the C++ programming language."[\[17\]](https://en.wikipedia.org/wiki/C%2B%2B#cite_note-17)



### Etymology of C++

According to Stroustrup: "the name signifies the evolutionary nature of the changes from C".[\[18\]](https://en.wikipedia.org/wiki/C%2B%2B#cite_note-name-18)This name is credited to Rick Mascitti \(mid-1983\)[\[11\]](https://en.wikipedia.org/wiki/C%2B%2B#cite_note-hopl2-11)and was first used in December 1983. When Mascitti was questioned informally in 1992 about the naming, he indicated that it was given in a [tongue-in-cheek](https://en.wikipedia.org/wiki/Tongue-in-cheek) spirit. The name comes from C's`++`[operator](https://en.wikipedia.org/wiki/Operator_%28programming%29)\(which [increments](https://en.wikipedia.org/wiki/Increment_and_decrement_operators) the [value](https://en.wikipedia.org/wiki/Value_%28computer_science%29) of a [variable](https://en.wikipedia.org/wiki/Variable_%28programming%29)\) and a common [naming convention](https://en.wikipedia.org/wiki/Naming_convention) of using "+" to indicate an enhanced computer program.

During C++'s development period, the language had been referred to as "new C" and "C with Classes"[\[11\]](https://en.wikipedia.org/wiki/C%2B%2B#cite_note-hopl2-11)[\[19\]](https://en.wikipedia.org/wiki/C%2B%2B#cite_note-19)before acquiring its final name.



### Philosophy of C++

Throughout C++'s life, its development and evolution has been informally governed by a set of rules that its evolution should follow:[\[10\]](https://en.wikipedia.org/wiki/C%2B%2B#cite_note-evolving-10)

* It must be driven by actual problems and its features should be useful immediately in real world programs.
* Every feature should be implementable \(with a reasonably obvious way to do so\).
* Programmers should be free to pick their own programming style, and that style should be fully supported by C++.
* Allowing a useful feature is more important than preventing every possible misuse of C++.
* It should provide facilities for organizing programs into well-defined separate parts, and provide facilities for combining separately developed parts.
* No implicit violations of the [type system](https://en.wikipedia.org/wiki/Type_system) \(but allow explicit violations; that is, those explicitly requested by the programmer\).
* User-created types need to have the same support and performance as built-in types.
* Unused features should not negatively impact created executables \(e.g. in lower performance\).
* There should be no language beneath C++ \(except [assembly language](https://en.wikipedia.org/wiki/Assembly_language)\).
* C++ should work alongside other existing [programming languages](https://en.wikipedia.org/wiki/Programming_language), rather than fostering its own separate and incompatible
  [programming environment](https://en.wikipedia.org/wiki/Programming_environment).
* If the programmer's intent is unknown, allow the programmer to specify it by providing manual control.

### 

### Standardization of C++

C++ is standardized by an [ISO](https://en.wikipedia.org/wiki/International_Organization_for_Standardization) working group known as [JTC1/SC22/WG21](https://en.wikipedia.org/wiki/ISO/IEC_JTC_1/SC_22). So far, it has published five revisions of the C++ standard and is currently working on the next revision,[C++20](https://en.wikipedia.org/wiki/C%2B%2B20).

In 1998, the ISO working group standardized C++ for the first time as ISO/IEC 14882:1998, which is informally known as C++98. In 2003, it published a new version of the C++ standard called ISO/IEC 14882:2003, which fixed problems identified in [C++98](https://en.wikipedia.org/wiki/C%2B%2B98).

The next major revision of the standard was informally referred to as "C++0x", but it was not released until 2011.[\[24\]](https://en.wikipedia.org/wiki/C%2B%2B#cite_note-0xapprove-24)[C++11](https://en.wikipedia.org/wiki/C%2B%2B11)\(14882:2011\) included many additions to both the core language and the standard library.[\[22\]](https://en.wikipedia.org/wiki/C%2B%2B#cite_note-isocpp2011-22)

In 2014,[C++14](https://en.wikipedia.org/wiki/C%2B%2B14)\(also known as C++1y\) was released as a small extension to [C++11](https://en.wikipedia.org/wiki/C%2B%2B11), featuring mainly bug fixes and small improvements.[\[25\]](https://en.wikipedia.org/wiki/C%2B%2B#cite_note-The_Future_of_C-25)The Draft International Standard ballot procedures completed in mid-August 2014.[\[26\]](https://en.wikipedia.org/wiki/C%2B%2B#cite_note-26)

After C++14, a major revision [C++17](https://en.wikipedia.org/wiki/C%2B%2B17), informally known as C++1z, was completed by the ISO C++ Committee in mid July 2017 and was approved and published in December 2017.[\[27\]](https://en.wikipedia.org/wiki/C%2B%2B#cite_note-Toronto_meeting_report-27)

As part of the standardization process, ISO also publishes [technical reports and specifications](https://en.wikipedia.org/wiki/International_Organization_for_Standardization#International_Standards_and_other_publications):

* ISO/IEC TR 18015:2006[\[28\]](https://en.wikipedia.org/wiki/C%2B%2B#cite_note-28) on the use of C++ in embedded systems and on performance implications of C++ language and library features,
* ISO/IEC TR 19768:2007[\[29\]](https://en.wikipedia.org/wiki/C%2B%2B#cite_note-29) \(also known as the [C++ Technical Report 1](https://en.wikipedia.org/wiki/C%2B%2B_Technical_Report_1)\) on library extensions mostly integrated into [C++11](https://en.wikipedia.org/wiki/C%2B%2B11)
  ,
* ISO/IEC TR 29124:2010[\[30\]](https://en.wikipedia.org/wiki/C%2B%2B#cite_note-30) on special mathematical functions,
* ISO/IEC TR 24733:2011[\[31\]](https://en.wikipedia.org/wiki/C%2B%2B#cite_note-31) on [decimal floating point](https://en.wikipedia.org/wiki/Decimal_floating_point) arithmetic,
* ISO/IEC TS 18822:2015[\[32\]](https://en.wikipedia.org/wiki/C%2B%2B#cite_note-32) on the standard file system library,
* ISO/IEC TS 19570:2015[\[33\]](https://en.wikipedia.org/wiki/C%2B%2B#cite_note-33) on [parallel](https://en.wikipedia.org/wiki/Parallel_computing) versions of the standard library algorithms,
* ISO/IEC TS 19841:2015[\[34\]](https://en.wikipedia.org/wiki/C%2B%2B#cite_note-34) on software [transactional memory](https://en.wikipedia.org/wiki/Transactional_memory),
* ISO/IEC TS 19568:2015[\[35\]](https://en.wikipedia.org/wiki/C%2B%2B#cite_note-35) on a new set of library extensions, some of which are already integrated into [C++17](https://en.wikipedia.org/wiki/C%2B%2B17),
* ISO/IEC TS 19217:2015[\[36\]](https://en.wikipedia.org/wiki/C%2B%2B#cite_note-36) on the C++ [Concepts](https://en.wikipedia.org/wiki/Concepts_%28C%2B%2B%29)

More technical specifications are in development and pending approval, including concurrency library extensions, a networking standard library, ranges, and modules.[\[37\]](https://en.wikipedia.org/wiki/C%2B%2B#cite_note-37)

