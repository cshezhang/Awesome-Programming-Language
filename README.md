# Introduction
A curated list of Software Engineering, System Security, Computer System and Program Language research resources(Papers, Books, Courses, Tools).

## Register Allocation and SSA Form

Sreedhar, Vugranam C., et al. "Translating out of static single assignment form." International Static Analysis Symposium. Springer, Berlin, Heidelberg, 1999.  

Fernando Magno Quintao Pereira and Jens Palsberg. Register allocation via coloring of chordal graphs. In Proceedings of APLAS'05, Asian Symposium on Programming Languages and Systems, pages 315-329, Tsukuba, Japan, November 2005.  

Sebastian Hack and Gerhard Goos. Optimal register allocation for SSA-form programs in polynomial time. In Information Processeing Letters 98(4): 150-155, 2006.  

Fernando Magno Quintao Pereira and Jens Palsberg. Register allocation after classical SSA elimination is NP-complete. In Proceedings of FOSSACS'06, Foundations of Software Science and Computation Structures. Springer-Verlag (LNCS), Vienna, Austria, March 2006.  

Vijay S. Menon, Neal Glew, Brian R. Murphy, Andrew McCreight, Tatiana Shpeisman, Ali-Reza Adl-Tabatabai, Leaf Petersen. A verifiable SSA program representation for aggressive compiler optimization. In Proceedings of POPL'06, pages 397-408.  

Braun, Matthias, et al. "Simple and efficient construction of static single assignment form." International Conference on Compiler Construction. Springer, Berlin, Heidelberg, 2013.  

## Call Graph Construction

Jeffrey Dean, David Grove, Craig Chambers. Optimization of Object-Oriented Programs Using Static Class Hierarchy Analysis. In Proceedings of ECOOP'95, pages 77-101.  

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

Hua Yan, Yulei Sui, Shiping Chen, and Jingling Xue. 2018. Spatio-temporal context reduction: a pointer-analysis-based static approach for detecting use-after-free vulnerabilities. In Proceedings of the 40th International Conference on Software Engineering (ICSE ’18). Association for Computing Machinery, New York, NY, USA, 327–337.  

Yue Li, Tian Tan, Anders Møller, and Yannis Smaragdakis. 2018. Precision-guided context sensitivity for pointer analysis. Proc. ACM Program. Lang. 2, OOPSLA, Article 141 (October 2018), 29 pages.  

Tan, Tian, Yue Li, and Jingling Xue. "Efficient and precise points-to analysis: modeling the heap by merging equivalent automata." Proceedings of the 38th ACM SIGPLAN Conference on Programming Language Design and Implementation. 2017.  

## Taint Analysis

Arzt, Steven, et al. "Flowdroid: Precise context, flow, field, object-sensitive and lifecycle-aware taint analysis for android apps." Acm Sigplan Notices. Vol. 49. No. 6. ACM, 2014.  

Enck, William, et al. "TaintDroid: an information-flow tracking system for realtime privacy monitoring on smartphones." ACM Transactions on Computer Systems (TOCS) 32.2 (2014): 5.  

Wei, Fengguo, et al. "Jn-saf: Precise and efficient ndk/jni-aware inter-language static analysis framework for security vetting of android applications with native code." Proceedings of the 2018 ACM SIGSAC Conference on Computer and Communications Security. 2018.  

Qi, Zhenxiao, et al. "SpecTaint: Speculative Taint Analysis for Discovering Spectre Gadgets" Network and Distributed Systems Security (NDSS) Symposium 2021  

## Symbolic Execution
David Trabish and Noam Rinetzky. 2020. Relocatable addressing model for symbolic execution. In Proceedings of the 29th ACM SIGSOFT International Symposium on Software Testing and Analysis (ISSTA 2020). Association for Computing Machinery, New York, NY, USA, 51–62.  

Frank Busse, Martin Nowack, and Cristian Cadar. 2020. Running symbolic execution forever. In Proceedings of the 29th ACM SIGSOFT International Symposium on Software Testing and Analysis (ISSTA 2020). Association for Computing Machinery, New York, NY, USA, 63–74.  

Godefroid, Patrice, Michael Y. Levin, and David Molnar. "SAGE: whitebox fuzzing for security testing." Communications of the ACM 55.3 (2012): 40-44.  

Cadar, Cristian, and Koushik Sen. "Symbolic execution for software testing: three decades later." Commun. ACM 56.2 (2013): 82-90.  

Cadar, Cristian, Daniel Dunbar, and Dawson R. Engler. "KLEE: Unassisted and Automatic Generation of High-Coverage Tests for Complex Systems Programs." OSDI. Vol. 8. 2008.  

Shoshitaishvili, Yan, et al. "Sok:(state of) the art of war: Offensive techniques in binary analysis." 2016 IEEE Symposium on Security and Privacy (SP). IEEE, 2016.  

Chipounov, Vitaly, Volodymyr Kuznetsov, and George Candea. "S2E: A platform for in-vivo multi-path analysis of software systems." ACM SIGARCH Computer Architecture News. Vol. 39. No. 1. ACM, 2011.  

Stephens, Nick, et al. "Driller: Augmenting Fuzzing Through Selective Symbolic Execution." NDSS. Vol. 16. No. 2016. 2016.  

Chipounov, Vitaly, et al. "Selective symbolic execution." Proceedings of the 5th Workshop on Hot Topics in System Dependability (HotDep). No. CONF. 2009.  

## Software Testing

Y. Jia and M. Harman, "An Analysis and Survey of the Development of Mutation Testing," in IEEE Transactions on Software Engineering, vol. 37, no. 5, pp. 649-678, Sept.-Oct. 2011.  

## Program Repair

Raja Ben Abdessalem, Annibale Panichella, Shiva Nejati, Lionel C. Briand, and Thomas Stifter. 2020. Automated repair of feature interaction failures in automated driving systems. In Proceedings of the 29th ACM SIGSOFT International Symposium on Software Testing and Analysis (ISSTA 2020). Association for Computing Machinery, New York, NY, USA, 88–100.

Yiling Lou, Ali Ghanbari, Xia Li, Lingming Zhang, Haotian Zhang, Dan Hao, and Lu Zhang. 2020. Can automated program repair refine fault localization? a unified debugging approach. In Proceedings of the 29th ACM SIGSOFT International Symposium on Software Testing and Analysis (ISSTA 2020). Association for Computing Machinery, New York, NY, USA, 75–87.   

Ghanbari, Ali, and Lingming Zhang. "PraPR: Practical Program Repair via Bytecode Mutation." 2019 34th IEEE/ACM International Conference on Automated Software Engineering (ASE). IEEE, 2019.  

X. Xu, Y. Sui, H. Yan and J. Xue, "VFix: Value-Flow-Guided Precise Program Repair for Null Pointer Dereferences," 2019 IEEE/ACM 41st International Conference on Software Engineering (ICSE), Montreal, QC, Canada, 2019, pp. 512-523, doi: 10.1109/ICSE.2019.00063.  

Ming Wen, Junjie Chen, Rongxin Wu, Dan Hao, and Shing-Chi Cheung. 2018. Context-aware patch generation for better automated program repair. In ICSE (ICSE’18). ACM, 1-11.  

## Loop Analysis

Xie, Xiaofei, et al. "Loopster: static loop termination analysis." Proceedings of the 2017 11th Joint Meeting on Foundations of Software Engineering. ACM, 2017.  

Xie, Xiaofei, et al. "Proteus: Computing disjunctive loop summary via path dependency analysis." Proceedings of the 2016 24th ACM SIGSOFT International Symposium on Foundations of Software Engineering. ACM, 2016.  

Xie, Xiaofei, et al. "S-looper: automatic summarization for multipath string loops." Proceedings of the 2015 International Symposium on Software Testing and Analysis. ACM, 2015.  

## Reflection Analysis

Li, Li, et al. "Reflection-aware static analysis of android apps." Proceedings of the 31st IEEE/ACM International Conference on Automated Software Engineering. 2016.  

J. Liu, Y. Li, T. Tan and J. Xue, "Reflection Analysis for Java: Uncovering More Reflective Targets Precisely," 2017 IEEE 28th International Symposium on Software Reliability Engineering (ISSRE), Toulouse, 2017, pp. 12-23.  

## Set Constraints

Jens Palsberg. How to solve set constraints, Oct 1, 2008.  

## Flow (in)Sensitive Analysis, Context (in)Sensitive Analysis, Information Flow Analysis

John Whaley, Monica S. Lam. Cloning-based context-sensitive pointer alias analysis using binary decision diagrams. In Proceedings of PLDI'04, pages 131-144.  

Pan, Xiang, et al. "FlowCog: context-aware semantics extraction and analysis of information flow leaks in android apps." 27th {USENIX} Security Symposium ({USENIX} Security 18). 2018.  

## Use of Static Program Analysis for Optimization. Flow-directed Method Inlining, Type-safe Method Inlining
Neal Glew and Jens Palsberg. Type-safe method inlining. Science of Computer Programming, 52:281-306, 2004. Preliminary version in Proceedings of ECOOP'02, European Conference on Object-Oriented Programming, pages 525-544, Springer-Verlag (LNCS 2374), Malaga, Spain, June 2002.  

## Relationships among Static Analysis and Type System

Nevin Heintze and David McAllester. Linear-time Subtransitive Control Flow Analysis, In Proceedings of PLDI'97, ACM SIGPLAN Conference on Programming Language Design and Implementation, pages 261-272, 1997.  

Jens Palsberg and Patrick M. O'Keefe. A type system equivalent to flow analysis. ACM Transactions on Programming Languages and Systems, 17(4):576-599, July 1995.   Preliminary version in Proceedings of POPL'95, 22nd Annual SIGPLAN-SIGACT Symposium on Principles of Programming Languages, pages 367-378, San Francisco, California, January 1995.  

L. Peter Deutsch and Allan M. Schiffman. Efficient Implementation of the Smalltalk-80 System. In Proceedings of POPL'84, pages 297-302. 

Jens Palsberg and Michael I. Schwartzbach. Object-oriented type inference. In Proceedings of OOPSLA'91, ACM SIGPLAN Sixth Annual Conference on Object-Oriented Programming Systems, Languages and Applications, pages 146-161, Phoenix, Arizona, October 1991. 

## Mining Big Code
Raychev, Veselin, Martin Vechev, and Andreas Krause. "Predicting program properties from" big code"." ACM SIGPLAN Notices 50.1 (2015): 111-124.  

Bichsel, Benjamin, et al. "Statistical deobfuscation of android applications." Proceedings of the 2016 ACM SIGSAC Conference on Computer and Communications Security. 2016.  

Jingxuan He, Pesho Ivanov, Petar Tsankov, Veselin Raychev, and Martin Vechev. 2018. Debin: Predicting Debug Information in Stripped Binaries. In Proceedings of the 2018 ACM SIGSAC Conference on Computer and Communications Security (CCS ’18). Association for Computing Machinery, New York, NY, USA, 1667–1680.  

Victor Chibotaru, Benjamin Bichsel, Veselin Raychev, and Martin Vechev. 2019. Scalable taint specification inference with big code. In Proceedings of the 40th ACM SIGPLAN Conference on Programming Language Design and Implementation (PLDI 2019). Association for Computing Machinery, New York, NY, USA, 760–774.  

## Crash Consisitency
Y Jiang, H Chen, F Qin, C Xu, X Ma, J Lu. Crash consistency validation made easy. In Proceedings of the Symposium on the Foundations of Software Engineering (FSE), 133--143, 2016.  

M Zheng, J Tucek, F Qin, M Lillibridge. Understanding the robustness of SSDS under power fault. In Proceedings of the USENIX Conference on File and Storage Technologies (FAST), 271--284, 2013.  

M Zheng, J Tucek, D Huang, F Qin, M Lillibridge, E S Yang, B W Zhao, S Singh. Torturing databases for fun and profit. In Proceedings of the Conference on Operating Systems Design and Implementation (OSDI), 449--464, 2014.  

T S Pillai, V Chidambaram, R Alagappan, S Al-Kiswany, A C Arpaci-Dusseau, R H Arpaci-Dusseau. All file systems are not created equal: On the complexity of crafting crash-consistent applications. In Proceedings of the Conference on Operating Systems Design and Implementation (OSDI), 433--448, 2014.  

J Yang, C Sar, D Engler. EXPLODE: A lightweight, general system for finding serious storage system errors. In Proceedings of the Conference on Operating Systems Design and Implementation (OSDI), 131--146, 2006.  

Dongjie Chen,Yanyan Jiang, Chang Xu, Xiaoxing Ma, and Jian Lu.2020. Testing File System Implementations on Layered Models.In 42nd International Conference on Software Engineering (ICSE ’20), May 23–29, 2020, Seoul, Republic of Korea.

## Code Difference, Code Embeeding(Representation)
Thong Hoang, Hong Jin Kang, David Lo, and Julia Lawall. 2020. CC2Vec: distributed representations of code changes. In Proceedings of the ACM/IEEE 42nd International Conference on Software Engineering (ICSE '20). Association for Computing Machinery, New York, NY, USA, 518–529.  

Ke Wang and Zhendong Su. 2020. Blended, precise semantic program embeddings. In Proceedings of the 41st ACM SIGPLAN Conference on Programming Language Design and Implementation(PLDI 2020). Association for Computing Machinery, New York, NY, USA, 121–134. 

Yue Duan, Xuezixiang Li, Jinghan Wang, and Heng Yin, "DeepBinDiff: Learning Program-Wide Code Representations for Binary Diffing", NDSS'2020

Ding, Steven HH, Benjamin CM Fung, and Philippe Charland. "Asm2vec: Boosting static representation robustness for binary clone search against code obfuscation and compiler optimization." 2019 IEEE Symposium on Security and Privacy (SP). IEEE, 2019.

Jean-Rémy Falleri, Floréal Morandat, Xavier Blanc, Matias Martinez, and Martin Monperrus. 2014. Fine-grained and accurate source code differencing. In Proceedings of the 29th ACM/IEEE international conference on Automated software engineering(ASE 2014). Association for Computing Machinery, New York, NY, USA, 313–324.  

Rumen Paletov, Petar Tsankov, Veselin Raychev, and Martin Vechev. 2018. Inferring crypto API rules from code changes. In Proceedings of the 39th ACM SIGPLAN Conference on Programming Language Design and Implementation (PLDI 2018). Association for Computing Machinery, New York, NY, USA, 450–464.  

## Impossibility Results
Sumit Gulwani, Ashish Tiwari. Assertion Checking over Combined Abstraction of Linear Arithmetic and Uninterpreted Functions. ESOP 2006, pages 279-293.  

Thomas W. Reps. Undecidability of context-sensitive data-independence analysis. ACM Transactions on Programming Languages and Systems, 22(1): 162-186, 2000.  

G. Ramalingam. The Undecidability of Aliasing, ACM Transactions on Programming Languages and Systems, 16(5):1467-1471, September 1994.  

Krishnendu Chatterjee, Di Ma, Rupak Majumdar, Tian Zhao, Thomas A. Henzinger, and Jens Palsberg. Stack Size Analysis of Interrupt Driven Software. Information and Computation 194(2):144-174, 2004, special issue dedicated to Paris Kanellakis.  

## Improvements for Static Analyses
Rijnard van Tonder and Claire Le Goues. 2020. Tailoring programs for static analysis via program transformation. In Proceedings of the ACM/IEEE 42nd International Conference on Software Engineering (ICSE '20). Association for Computing Machinery, New York, NY, USA, 824–834.  

### Soundness for static analysis
Jens Palsberg. A Proof of the Schroder-Bernstein Theorem, Jul 26, 2008.  
Jens Palsberg. Closure analysis in constraint form. ACM Transactions on Programming Languages and Systems, 17(1):47-62, January 1995. 

Use of static program analysis for bug finding, including synchronization optimization, deadlock detection, security vulnerability detection  

Larry Koved, Marco Pistoia, Aaron Kershenbaum. Access rights analysis for Java. OOPSLA 2002, pages 359-372.  

Jonathan Aldrich, Craig Chambers, Emin Gun Sirer, and Susan J. Eggers. Static Analyses for Eliminating Unnecessary Synchronization from Java Programs. SAS 1999, pages 19-38.  

Erik Ruf. Effective synchronization removal for Java. PLDI 2000, pages 208-218.  

Christian Grothoff, Jens Palsberg, and Jan Vitek. Encapsulating objects with confined types. ACM Transactions on Programming Languages and Systems, to appear.