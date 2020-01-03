# Awesome-Program-Analysis
A curated list of Program Analysis resources(Papers, Books, Courses, Tools).

## Register allocation and SSA form
Sebastian Hack and Gerhard Goos. Optimal register allocation for SSA-form programs in polynomial time. In Information Processeing Letters 98(4): 150-155, 2006.  
Fernando Magno Quintao Pereira and Jens Palsberg. Register allocation via coloring of chordal graphs. In Proceedings of APLAS'05, Asian Symposium on Programming Languages and Systems, pages 315-329, Tsukuba, Japan, November 2005.  
Fernando Magno Quintao Pereira and Jens Palsberg. Register allocation after classical SSA elimination is NP-complete. In Proceedings of FOSSACS'06, Foundations of Software Science and Computation Structures. Springer-Verlag (LNCS), Vienna, Austria, March 2006.  
Vijay S. Menon, Neal Glew, Brian R. Murphy, Andrew McCreight, Tatiana Shpeisman, Ali-Reza Adl-Tabatabai, Leaf Petersen. A verifiable SSA program representation for aggressive compiler optimization. In Proceedings of POPL'06, pages 397-408.  

## Static analysis
Sreedhar, Vugranam C., et al. "Translating out of static single assignment form." International Static Analysis Symposium. Springer, Berlin, Heidelberg, 1999.  
Braun, Matthias, et al. "Simple and efficient construction of static single assignment form." International Conference on Compiler Construction. Springer, Berlin, Heidelberg, 2013.  
Jens Palsberg and Michael I. Schwartzbach. Object-oriented type inference. In Proceedings of OOPSLA'91, ACM SIGPLAN Sixth Annual Conference on Object-Oriented Programming Systems, Languages and Applications, pages 146-161, Phoenix, Arizona, October 1991.  
Jeffrey Dean, David Grove, Craig Chambers. Optimization of Object-Oriented Programs Using Static Class Hierarchy Analysis. In Proceedings of ECOOP'95, pages 77-101.  
L. Peter Deutsch and Allan M. Schiffman. Efficient Implementation of the Smalltalk-80 System. In Proceedings of POPL'84, pages 297-302.  
David Bacon and Peter Sweeney. Fast Static Analysis of C++ Virtual Function Calls, In Proceedings of OOPSLA'96, ACM SIGPLAN Conference on Object-Oriented Programming Systems, Languages and Applications, pages 324-341, 1996.  
Frank Tip and Jens Palsberg. Scalable Propagation-based Call Graph Construction Algorithms. In Proceedings of OOPSLA'00, ACM SIGPLAN Conference on Object-Oriented Programming Systems, Languages and Applications, pages 281-293, Minneapolis, Minnesota, October 2000.  

## Dynamic Analysis
Nethercote, Nicholas, and Julian Seward. "Valgrind: a framework for heavyweight dynamic binary instrumentation." ACM Sigplan notices. Vol. 42. No. 6. ACM, 2007.  
Saudel, Florent, and Jonathan Salwan. "Triton: A dynamic symbolic execution framework." Symposium sur la sécurité des technologies de l’information et des communications, SSTIC, France, Rennes. 2015.  
[Dynamio](http://www.dynamorio.org/) is a runtime code manipulation system that supports code transformations on any part of a program, while it executes.  
[Pin Tool](https://software.intel.com/en-us/articles/pin-a-dynamic-binary-instrumentation-tool) is a dynamic binary instrumentation framework for the IA-32, x86-64 and MIC instruction-set architectures that enables the creation of dynamic program analysis tools.  
[Java Path Finder](https://github.com/javapathfinder/jpf-core) is an extensible software analysis framework(basic VM, model checking module, detect concurrency defect, unhandled exception) for Java bytecode.  

## Pointer Analysis
Nevin Heintze and Olivier Tardieu. Ultra-fast Aliasing Analysis using CLA: A Million Lines of C Code in a Second. In Proceedings of PLDI'01, pages 254-263.  

## Taint Analysis
Arzt, Steven, et al. "Flowdroid: Precise context, flow, field, object-sensitive and lifecycle-aware taint analysis for android apps." Acm Sigplan Notices. Vol. 49. No. 6. ACM, 2014.  
Enck, William, et al. "TaintDroid: an information-flow tracking system for realtime privacy monitoring on smartphones." ACM Transactions on Computer Systems (TOCS) 32.2 (2014): 5.  

## Symbolic execution
Cadar, Cristian, Daniel Dunbar, and Dawson R. Engler. "KLEE: Unassisted and Automatic Generation of High-Coverage Tests for Complex Systems Programs." OSDI. Vol. 8. 2008.  
Shoshitaishvili, Yan, et al. "Sok:(state of) the art of war: Offensive techniques in binary analysis." 2016 IEEE Symposium on Security and Privacy (SP). IEEE, 2016.  
Chipounov, Vitaly, Volodymyr Kuznetsov, and George Candea. "S2E: A platform for in-vivo multi-path analysis of software systems." ACM SIGARCH Computer Architecture News. Vol. 39. No. 1. ACM, 2011.  
Stephens, Nick, et al. "Driller: Augmenting Fuzzing Through Selective Symbolic Execution." NDSS. Vol. 16. No. 2016. 2016.  

## Loop Analysis
Xie, Xiaofei, et al. "Loopster: static loop termination analysis." Proceedings of the 2017 11th Joint Meeting on Foundations of Software Engineering. ACM, 2017.  
Xie, Xiaofei, et al. "Proteus: Computing disjunctive loop summary via path dependency analysis." Proceedings of the 2016 24th ACM SIGSOFT International Symposium on Foundations of Software Engineering. ACM, 2016.  
Xie, Xiaofei, et al. "S-looper: automatic summarization for multipath string loops." Proceedings of the 2015 International Symposium on Software Testing and Analysis. ACM, 2015.  

## Set constraints
Jens Palsberg. How to solve set constraints, Oct 1, 2008.  

## Flow (in)sensitive analysis, context (in)sensitive analysis, information flow analysis
John Whaley, Monica S. Lam. Cloning-based context-sensitive pointer alias analysis using binary decision diagrams. In Proceedings of PLDI'04, pages 131-144.  
Pan, Xiang, et al. "FlowCog: context-aware semantics extraction and analysis of information flow leaks in android apps." 27th {USENIX} Security Symposium ({USENIX} Security 18). 2018.  

## Use of static program analysis for optimization. Flow-directed method inlining, type-safe method inlining
Neal Glew and Jens Palsberg. Type-safe method inlining. Science of Computer Programming, 52:281-306, 2004. Preliminary version in Proceedings of ECOOP'02, European Conference on Object-Oriented Programming, pages 525-544, Springer-Verlag (LNCS 2374), Malaga, Spain, June 2002.  

## Relationships among static analysis and type systems
Nevin Heintze and David McAllester. Linear-time Subtransitive Control Flow Analysis, In Proceedings of PLDI'97, ACM SIGPLAN Conference on Programming Language Design and Implementation, pages 261-272, 1997.  
Jens Palsberg and Patrick M. O'Keefe. A type system equivalent to flow analysis. ACM Transactions on Programming Languages and Systems, 17(4):576-599, July 1995.   Preliminary version in Proceedings of POPL'95, 22nd Annual SIGPLAN-SIGACT Symposium on Principles of Programming Languages, pages 367-378, San Francisco, California, January 1995.  

## Impossibility results
Sumit Gulwani, Ashish Tiwari. Assertion Checking over Combined Abstraction of Linear Arithmetic and Uninterpreted Functions. ESOP 2006, pages 279-293.  
Thomas W. Reps. Undecidability of context-sensitive data-independence analysis. ACM Transactions on Programming Languages and Systems, 22(1): 162-186, 2000.  
G. Ramalingam. The Undecidability of Aliasing, ACM Transactions on Programming Languages and Systems, 16(5):1467-1471, September 1994.  
Krishnendu Chatterjee, Di Ma, Rupak Majumdar, Tian Zhao, Thomas A. Henzinger, and Jens Palsberg. Stack Size Analysis of Interrupt Driven Software. Information and Computation 194(2):144-174, 2004, special issue dedicated to Paris Kanellakis. Preliminary version in Proceedings of SAS'03, International Static Analysis Symposium, pages 109-126, San Diego, June 2003.  

## Soundness proofs for static analyses
Jens Palsberg. A Proof of the Schroder-Bernstein Theorem, Jul 26, 2008.  
Jens Palsberg. Closure analysis in constraint form. ACM Transactions on Programming Languages and Systems, 17(1):47-62, January 1995. Preliminary version in Proceedings of CAAP'94, Colloquium on Trees in Algebra and Programming, Springer-Verlag (LNCS 787), pages 276-290, Edinburgh, Scotland, April 1994.  
Use of static program analysis for bug finding, including synchronization optimization, deadlock detection, security vulnerability detection
Larry Koved, Marco Pistoia, Aaron Kershenbaum. Access rights analysis for Java. OOPSLA 2002, pages 359-372.  
Jonathan Aldrich, Craig Chambers, Emin Gun Sirer, and Susan J. Eggers. Static Analyses for Eliminating Unnecessary Synchronization from Java Programs. SAS 1999, pages 19-38.  
Erik Ruf. Effective synchronization removal for Java. PLDI 2000, pages 208-218.
Christian Grothoff, Jens Palsberg, and Jan Vitek. Encapsulating objects with confined types. ACM Transactions on Programming Languages and Systems, to appear. Preliminary version in Proceedings of OOPSLA'01, ACM SIGPLAN Conference on Object-Oriented Programming Systems, Languages and Applications, pages 241-253, Tampa Bay, Florida, October 2001.  