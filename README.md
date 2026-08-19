## Awesome LLVM [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 497,666 | 🐛 102 | 📅 2026-08-18

This repo includes LLVM-related projects, websites, docs, and other resources. Only well-maintained resources are included; PRs are welcome.
This README.md itself mostly records **LLVM backend** (as well as mixed) resources; for **Clang**-specific ones, please check **[Clang.md](./Clang.md)** in this repo.

## Starchart

![Star History Chart](https://api.star-history.com/svg?repos=learn-llvm/awesome-llvm\&type=Date)

# Awesome Websites(references) with stars

* 🐉 <http://llvm.org/>, and [its doxygen docs](https://llvm.org/doxygen/index.html)
* 🐉 <https://llvm.org/devmtg/> - LLVM Developers' Meeting and other events
  * 📹 [2023](https://www.youtube.com/playlist?list=PL_R5A0lGi1AD9nPVlv7mG8_2mMSiL_0Ik)
* 🐉 <http://blog.llvm.org/> - official blog
* 🐉 [discourse forum](https://discourse.llvm.org/)
* 🐉 [llvm-commits archives](https://lists.llvm.org/pipermail/llvm-commits/)
* 🐉 [llvm-bugs archives](https://lists.llvm.org/pipermail/llvm-bugs/)
* 🐉 [LLVMProj @ YouTube](https://www.youtube.com/@LLVMPROJ/videos?view=0\&sort=dd\&shelf_id=0) - official account, including [LLVM devmeeting](http://llvm.org/devmtg/), EuroLLVM, etc
* 🐉 [Open Projects](https://llvm.org/OpenProjects.html)
* 🐉 [LLVM Community events calendar](https://calendar.google.com/calendar/u/0/embed?src=calendar@llvm.org)
* [llvm-weekly](http://llvmweekly.org/) and its [Mastodon page](https://fosstodon.org/@llvmweekly) by [Alex Bradbury](https://fosstodon.org/@asb)
* [The Architecture of Open Source Applications - LLVM](http://www.aosabook.org/en/llvm.html)
* [Eli Bendersky's website](http://eli.thegreenplace.net/)
* [ChenWj's LLVM Wiki](http://people.cs.nctu.edu.tw/~chenwj/dokuwiki/doku.php?id=llvm)(Traditional Chinese)
* [An Unofficial LLVM Website](http://llvm.lyngvig.org/Articles/)
* [LLVM @ StackOverflow](http://stackoverflow.com/questions/tagged/llvm)
* [LLVM @ reddit](https://www.reddit.com/r/LLVM/)
* [GitHub LLVM topic](https://github.com/topics/llvm)
* [LLVM documentation in hdoc](https://docs.hdoc.io/hdoc/llvm-project/functions.html)
* ~~[ELLCC](http://ellcc.org/demo/index.cgi) - Online LLVM Demo Page~~

# Tutorials/Documentation ([reference](http://llvm.org/docs/index.html))

* 🐉 [Tools for Learning LLVM TableGen](https://blog.llvm.org/posts/2023-12-07-tools-for-learning-llvm-tablegen/) - tutorial by David Spickett about LLVM's [TableGen](https://github.com/llvm/llvm-project/tree/main/llvm/utils/TableGen) ⭐ 39,827 | 🐛 38,343 | 🌐 LLVM | 📅 2026-08-19
* :octocat: [LLVM-Tutor](https://github.com/banach-space/llvm-tutor) ⭐ 3,420 | 🐛 14 | 🌐 C++ | 📅 2026-05-17 - A collection of out-of-tree LLVM passes for teaching and learning
* :octocat: [llvm-ir-tutorial](https://github.com/Evian-Zhang/llvm-ir-tutorial) ⭐ 1,516 | 🐛 1 | 🌐 LLVM | 📅 2026-01-04 (in Chinese)
* :octocat: [wuzhanglin/llvm-IR-examples](https://github.com/wuzhanglin/llvm-IR-examples) ⭐ 44 | 🐛 0 | 🌐 C++ | 📅 2022-08-23 - Some examples for using LLVM to generate IR
* :octocat: [srg-llvm-pass-tutorial](https://github.com/delcypher/srg-llvm-pass-tutorial) ⭐ 19 | 🐛 0 | 🌐 C++ | 📅 2015-04-26 - A tutorial about llvm passes from [Software reliability group](http://srg.doc.ic.ac.uk/)
* :octocat: [learning-llvm](https://github.com/danbev/learning-llvm) ⭐ 18 | 🐛 0 | 🌐 C | 📅 2022-09-13 - a project for learning about llvm
* :octocat: [LLVM-Pass-Analysis-Collection](https://github.com/JohannesLiu/LLVM-Pass-Analysis-Collection) ⭐ 4 | 🐛 0 | 🌐 C++ | 📅 2023-12-03 - A Collection of LLVM Pass for Program Analysis
* :octocat: [lahiri-phdworks/LLVM-Examples](https://github.com/lahiri-phdworks/LLVM-Examples) ⭐ 3 | 🐛 0 | 🌐 LLVM | 📅 2024-05-20 - LLVM Repository and Code samples. LLVM Passes and quick bytes.
* 🐉 [LLVM Tutorials](http://llvm.org/docs/tutorial/index.html) - a list of tutorials
  * :octocat: [Python Version of the LLVM Tutorial](https://github.com/eliben/pykaleidoscope) ⭐ 343 | 🐛 1 | 🌐 Python | 📅 2026-07-01
* 🐉 [LLVM Language Reference Manual](http://llvm.org/docs/LangRef.html) - detailed docs for LLVM IR/Bitcode
  * :octocat: [PSA: Instruction-constructors changing to iterator-only insertion](https://github.com/sunxfancy/vscode-llvm) ⭐ 237 | 🐛 1 | 🌐 TypeScript | 📅 2024-05-30 - VSCode LLVM Compiler Explorer
  * 🐉 [LLVM Bitcode File Format](http://llvm.org/docs/BitCodeFormat.html)
  * 🐉 [The Often Misunderstood GEP Instruction](http://llvm.org/docs/GetElementPtr.html)
  * 🐉 [Opaque Pointers](https://llvm.org/docs/OpaquePointers.html) - Opaque pointer that was introduced in LLVM14 and fully deprecates typed pointers in LLVM17
  * [A Gentle Introduction to LLVM IR](https://mcyoung.xyz/2023/08/01/llvm-ir/), with a [Chinese translation version](TODO)
* 🐉 [LLVM Programmer’s Manual](http://llvm.org/docs/ProgrammersManual.html) - how to develop using LLVM infrastructure
  * 🐉 [LLVM Coding Standards](http://llvm.org/docs/CodingStandards.html)
  * 🐉 [LLVM Developer Policy](http://llvm.org/docs/DeveloperPolicy.html)
  * 🐉 [LLVM Style RTTI](http://llvm.org/docs/HowToSetUpLLVMStyleRTTI.html)
  * 🐉 [Source Level Debugging](http://llvm.org/docs/SourceLevelDebugging.html)
  * 🐉 [Create A Project](http://llvm.org/docs/Projects.html)
  * 🐉 [Exception Handling in LLVM](http://llvm.org/docs/ExceptionHandling.html)
  * 🐉 [](https://discourse.llvm.org/t/psa-instruction-constructors-changing-to-iterator-only-insertion/77845)
  * 📹 [A Tour of ADT - the LLVM Developer's Toolbox](https://www.youtube.com/watch?v=owQlnNYek2o\&list=PL_R5A0lGi1AD9nPVlv7mG8_2mMSiL_0Ik\&index=26)
* 🐉 [CommandLine 2.0 Library Manual](http://llvm.org/docs/CommandLine.html) - LLVM's CLI option parser library, used by all LLVM CLI tools etc
* 🐉 [Getting Started with the LLVM System](http://llvm.org/docs/GettingStarted.html) - LLVM project's build, configurations, directory layouts etc
* 🐉 [LLVM’s Analysis and Transform Passes](http://llvm.org/docs/Passes.html)
  * 🐉 [Using the New Pass Manager](https://llvm.org/docs/NewPassManager.html) - LLVM's new pass manager for optimization (both CLI and API changed)
  * 🐉 [Writing an LLVM Pass](http://llvm.org/docs/WritingAnLLVMPass.html)
  * 🐉 [LLVM Alias Analysis Infrastructure](http://llvm.org/docs/AliasAnalysis.html)
  * [Tracing Memory Access With an LLVM Pass](https://www.bitsand.cloud/posts/llvm-pass/) - a blog post details how to implement an LLVM Pass that allows for tracing memory access
* 🐉 [LLVM Testing Infrastructure Guide](http://llvm.org/docs/TestingGuide.html)
* 🐉 [Writing an LLVM Backend](http://llvm.org/docs/WritingAnLLVMBackend.html)
* 🐉 [LLVM Remarks](https://llvm.org/docs/Remarks.html) - emit diagnostics describing whether an optimization is performed/missed
* 🐉 [LLVM FAQ](http://llvm.org/docs/FAQ.html) - Frequently Asked Questions
* :octocat: [Sanitizers](docs/sanitizers) - AddressSanitizer, MemorySanitizer, ThreadSanitizer, UndefinedBehaviorSanitizer, LeakSanitizer, etc
* :octocat: [Tutorial: Creating an LLVM Backend for the Cpu0 Architecture](http://jonathan2251.github.io/lbd/index.html)
* 📃 [Get Started with the LLVM C API](https://pauladamsmith.com/blog/2015/01/how-to-get-started-with-llvm-c-api.html)
* 📹 [LLVM Tutorial Walkthrough](https://www.youtube.com/watch?v=09EAVa7BAp4\&list=PLSq9OFrD2Q3ChEc_ejnBcO5u9JeT0ufkg) -- Toby Ho's tutorial
* 📹 [Introduction to the Low-Level Virtual Machine (LLVM)](https://www.youtube.com/playlist?list=PLDSTpI7ZVmVnvqtebWnnI8YeB8bJoGOyv) - UFMG's Compilers Lab's tutorial
* 📹 [Understanding Compiler Optimization](https://www.youtube.com/watch?v=FnGCDLhaxKU\&t=59s) - Chandler Carruth's Opening Keynote Meeting C++ 2015

# Publications

* <http://llvm.org/pubs/>
* [LLVM @ Google Scholar](https://scholar.google.com/scholar?hl=en\&q=llvm)
* [LLVM @ ACM-DL](https://dl.acm.org/action/doSearch?fillQuickSearch=false\&target=advanced\&expand=dl\&field1=AllField\&text1=llvm)
* [LLVM @ IEEEXplore](http://ieeexplore.ieee.org/search/searchresult.jsp?newsearch=true\&queryText=llvm)
* [LLVM @ DBLP](http://dblp.org/search/#query=llvm)
* 📖 [Learn LLVM 12](https://www.amazon.com/Learn-LLVM-12-beginners-libraries/dp/1839213507/ref=sr_1_1) - good to start with
* 📖 [Learn LLVM 17](https://www.packtpub.com/product/learn-llvm-17-second-edition/9781837631346) Second Edition
* 📖 [Getting Started with LLVM Core Libraries](https://www.amazon.com/Getting-Started-LLVM-Core-Libraries/dp/1782166920), also available on [ACM library](https://dl.acm.org/citation.cfm?id=2692607)
* 📖 [LLVM Cookbook](https://www.amazon.com/LLVM-Cookbook-Mayur-Pandey/dp/178528598X)
* 📖 [LLVM Essentials](https://www.amazon.com/LLVM-Essentials-Suyog-Sarda/dp/1785280805/)
* 📖 [LLVM Techniques, Tips, and Best Practices Clang and Middle-End Libraries](https://www.amazon.com/Techniques-Practices-Clang-Middle-End-Libraries/dp/1838824952)
* 📖 [Engineering LLVM Backend](https://www.amazon.com/Engineering-LLVM-Backend-next-generation-accelerator-ebook/dp/B0BBRF69XL/ref=sr_1_15)

# Official Tools/Libraries ([reference](http://llvm.org/docs/CommandGuide/index.html))

* [BOLT](https://github.com/llvm/llvm-project/blob/main/bolt/README.md) ⭐ 39,827 | 🐛 38,343 | 🌐 LLVM | 📅 2026-08-19 - a post-link optimizer developed to speed up large applications
* Core Utilities
  * [opt](http://llvm.org/docs/CommandGuide/opt.html) - LLVM optimizer, for LLVM analysis and transformation passes, works on `.ll` or `.bc` files
    * 📹 [Core C++ 2021 :: opt-viewer: Inspecting compiler optimizations in high-level code](https://www.youtube.com/watch?v=BJ_yxTmZQbc)
    * 📹 [LLVM Optimization Remarks - Ofek Shilon - CppCon 2022](https://www.youtube.com/watch?v=qmEsx4MbKoc)
  * [lli](https://llvm.org/docs/CommandGuide/lli.html) - Directly execute/intepreter programs from LLVM bitcode, running on `.ll` or `.bc` files
  * [llvm-dis](http://llvm.org/docs/CommandGuide/llvm-dis.html) - LLVM disassembler, from `.bc` to `.ll`
  * [llvm-as](http://llvm.org/docs/CommandGuide/llvm-as.html) - LLVM assembler, from `.ll` to `.bc`
  * [llvm-link](http://llvm.org/docs/CommandGuide/llvm-link.html) - LLVM bitcode linker, merge multiple `.bc`s/`.ll`s into one
  * [llvm-dwarfdump](http://llvm.org/docs/CommandGuide/llvm-dwarfdump.html) - Print contents of DWARF sections, `llvm-dwarfdump -a main.o`
  * [llvm-config](http://llvm.org/docs/CommandGuide/llvm-config.html) - Print LLVM compilation options, e.g., `llvm-config --includedir`
  * [llvm-extract](http://llvm.org/docs/CommandGuide/llvm-extract.html) - Extract functions from an LLVM module
  * [llvm-bcanalyzer](http://llvm.org/docs/CommandGuide/llvm-bcanalyzer.html) - LLVM bitcode analyzer, `llvm-bcanalyzer main.bc`
  * [llvm-objdump](http://llvm.org/docs/CommandGuide/llvm-objdump.html) - LLVM's [objdump](https://en.wikipedia.org/wiki/Objdump), `llvm-objdump -a main.o`
  * [llvm-nm](http://llvm.org/docs/CommandGuide/llvm-nm.html) - LLVM's nm
  * [llvm-readelf](https://llvm.org/docs/CommandGuide/llvm-readelf.html) - LLVM's [readelf](https://en.wikipedia.org/wiki/Readelf), `llvm-readelf -a main.o`
  * [llvm-readobj](http://llvm.org/docs/CommandGuide/llvm-readobj.html) - LLVM object reader, `llvm-readobj --all main.o`
  * [llvm-diff](http://llvm.org/docs/CommandGuide/llvm-diff.html) - LLVM structural "diff"
  * [llc](http://llvm.org/docs/CommandGuide/llc.html) -  LLVM static compiler, compile LLVM IR to native assembly,  `llc main.ll -o main.s`
  * [llvm-ar](http://llvm.org/docs/CommandGuide/llvm-ar.html)(llvm-ranlib) - LLVM archiver
  * [llvm-mca](https://llvm.org/docs/CommandGuide/llvm-mca.html) - LLVM Machine Code Analyzer
  * [lit](http://llvm.org/docs/CommandGuide/lit.html) - LLVM Integrated Tester, for testing purpose during development
* [libc++](https://libcxx.llvm.org/) - LLVM's implementation of C++ standard library
* [libc++abi](https://libcxxabi.llvm.org/) - LLVM's C++ ABI library that provides an implementation of the library portion of the Itanium C++ ABI
* [Compiler-RT](https://compiler-rt.llvm.org/) - runtime libraries, including sanitizers, profiling utilities, etc
* [MLIR](https://mlir.llvm.org/) - Multi-Level Intermediate Representation
  * :octocat: [llvm/Torch-LLVM](https://github.com/llvm/torch-mlir) ⭐ 1,888 | 🐛 578 | 🌐 C++ | 📅 2026-08-18 - first class support from the PyTorch ecosystem to the MLIR ecosystem
  * :octocat: [j2kun/mlir-tutorial](https://github.com/j2kun/mlir-tutorial) ⭐ 1,346 | 🐛 8 | 🌐 C++ | 📅 2025-07-18 - a series of articles on the MLIR framework for building compilers
  * :octocat: [llvm/Polygeist](https://github.com/llvm/Polygeist) ⭐ 623 | 🐛 90 | 🌐 C++ | 📅 2025-06-19 - C/C++ frontend for MLIR
  * :octocat: [intel/mlir-extensions](https://github.com/intel/mlir-extensions/tree/main) ⭐ 156 | 🐛 83 | 🌐 MLIR | 📅 2026-08-18 - Intel® Extension for MLIR
  * :octocat: [Lewuathe/mlir-hello](https://github.com/Lewuathe/mlir-hello) ⭐ 138 | 🐛 1 | 🌐 C++ | 📅 2025-12-23 - minimal Hello-World example of MLIR
  * out-of-tree MLIR project templates: [zincnode/mlir-he](https://github.com/zincnode/mlir-he) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2025-02-16, [jmgorius/mlir-standalone-template](https://github.com/jmgorius/mlir-standalone-template) ⭐ 120 | 🐛 3 | 🌐 CMake | 📅 2026-03-26, [Lewuathe/mlir-hello](https://github.com/Lewuathe/mlir-hello) ⭐ 138 | 🐛 1 | 🌐 C++ | 📅 2025-12-23
  * :octocat: [melior](https://github.com/edg-l/melior) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2026-08-18 - The rustic MLIR bindings in Rust; see also [introduction blog post](https://edgarluque.com/blog/mlir-with-rust/)
  * 🐉 [MLIR News](https://discourse.llvm.org/c/mlir/mlir-news-mlir-newsletter/) - MLIR News issue on discourse
  * 🐉 [](https://discourse.llvm.org/t/rfc-a-new-tutorial-mlir-for-beginners/78273)
  * :octocat: [Sparsifier](https://developers.google.com/mlir-sparsifier) - Google MLIR sparsifier
  * [MLIR Workshop @ EuroLLVM 2024](https://discourse.llvm.org/t/cfp-mlir-workshop-at-the-eurollvm-developer-meeting-apr-9-2024/76987) -- topics with slides available, also [notes about MLIR at round table](https://discourse.llvm.org/t/notes-from-the-mlir-upstream-round-table-eurollvm-2024/78374)
  * 📹 [MLIR Is Not an ML Compiler, and Other Common Misconceptions](https://www.youtube.com/watch?v=lXAp6ZAWyBY\&list=PL_R5A0lGi1AD9nPVlv7mG8_2mMSiL_0Ik\&index=25)
  * [Working with MLIR](https://makslevental.github.io/working-with-mlir/)
* [libfuzzer](https://llvm.org/docs/LibFuzzer.html) - a library for coverage-guided fuzz testing
* [LLD](https://lld.llvm.org/) - LLVM's integrated linker, similar to [GNU ld](https://linux.die.net/man/1/ld) and [gold linker](https://en.wikipedia.org/wiki/Gold_\(linker\))
  * relevant: [LLVM Gold Linker plugin](https://llvm.org/docs/GoldPlugin.html)
* [LLDB](http://lldb.llvm.org/) - LLVM's LLDB Debugger
  * 🐉 [GDB to LLDB command map](https://lldb.llvm.org/use/map.html)
* [LLVM's libunwind](https://bcain-llvm.readthedocs.io/projects/libunwind/en/latest/) - an implementation of the interface defined by the HP libunwind project
* [Polly](http://polly.llvm.org/) - LLVM Framework for High-Level Loop and Data-Locality Optimizations
* [OpenMP in LLVM](https://openmp.llvm.org/)
  * 🐉 [LLVM OpenMP @ discourse](https://discourse.llvm.org/c/runtimes/openmp/35)
* [OpenCL C in LLVM](https://libclc.llvm.org/) - open source, BSD/MIT dual licensed implementation of the library requirements of the OpenCL C programming language

# Unofficial Tools/Libraries ([reference](http://llvm.org/ProjectsWithLLVM/))

* [Emscripten](https://github.com/kripken/emscripten) ⭐ 27,571 | 🐛 2,471 | 🌐 C++ | 📅 2026-08-19 - An LLVM-to-JavaScript Compiler
* [Infer](https://github.com/facebook/infer) ⭐ 15,679 | 🐛 297 | 🌐 OCaml | 📅 2026-08-19 - Facebook's static analysis framework; C/C++/objc is based on LLVM/Clang
* [RetDec](https://github.com/avast/retdec) ⭐ 8,606 | 🐛 458 | 🌐 C++ | 📅 2026-05-26 - a retargetable machine-code decompiler based on LLVM
* [ollvm](https://github.com/obfuscator-llvm/obfuscator/wiki) ⭐ 4,385 | 🐛 97 | 📅 2023-10-20 - code obfuscation based on LLVM4.0
* [cling](https://github.com/root-project/cling) ⭐ 4,177 | 🐛 137 | 🌐 C++ | 📅 2026-08-06 - The cling C++ interpreter ([1.0](https://github.com/vgvassilev/cling/releases/tag/v1.0) ⭐ 1,808 | 🐛 67 | 🌐 C++ | 📅 2026-07-30 has been released)
* [IKOS](https://github.com/nasa-sw-vnv/ikos) ⭐ 3,161 | 🐛 50 | 🌐 C++ | 📅 2026-05-31 - Static analyzer for C/C++ based on the theory of Abstract Interpretation.
* [klee](https://github.com/klee/klee) ⭐ 2,971 | 🐛 86 | 🌐 C++ | 📅 2026-07-06 - Symbolic Virtual Machine
* [mstorsjo/llvm-mingw](https://github.com/mstorsjo/llvm-mingw) ⭐ 2,928 | 🐛 128 | 🌐 C | 📅 2026-08-19 - An LLVM/Clang/LLD based mingw-w64 toolchain
* [mcsema](https://github.com/trailofbits/mcsema) ⚠️ Archived - An x86 to LLVM IR decompiler
* [google/souper](https://github.com/google/souper) ⚠️ Archived - A superoptimizer for LLVM IR
* [circt](https://github.com/llvm/circt) ⭐ 2,221 | 🐛 1,140 | 🌐 C++ | 📅 2026-08-19 - Circuit IR Compilers and Tools
* [QBDI](https://github.com/QBDI/QBDI) ⭐ 1,810 | 🐛 19 | 🌐 C++ | 📅 2026-07-24 - A Dynamic Binary Instrumentation framework based on LLVM
* [remill](https://github.com/lifting-bits/remill) ⭐ 1,799 | 🐛 73 | 🌐 C++ | 📅 2026-07-01 - Library for lifting machine code to LLVM bitcode
* [SVF-tools](https://github.com/SVF-tools/SVF) ⭐ 1,701 | 🐛 208 | 🌐 C++ | 📅 2026-07-30 - Pointer Analysis and Program Dependence Analysis for C and C++ Programs
* [Phasar](https://github.com/secure-software-engineering/phasar) ⭐ 1,053 | 🐛 38 | 🌐 C++ | 📅 2026-08-18 - A LLVM-based static analysis framework
* [microsoft/llvm-mctoll](https://github.com/microsoft/llvm-mctoll) ⭐ 877 | 🐛 45 | 🌐 C++ | 📅 2024-06-22 - statically (AOT) translates (or raises) binaries to LLVM IR
* [whole-program-llvm](https://github.com/travitch/whole-program-llvm) ⭐ 734 | 🐛 8 | 🌐 Python | 📅 2025-12-30 - A wrapper script to build whole-program LLVM bitcode files; its go port [gllvm](https://github.com/SRI-CSL/gllvm) ⭐ 342 | 🐛 13 | 🌐 Go | 📅 2024-04-28
* [llvm-pass-skeleton](https://github.com/sampsyo/llvm-pass-skeleton) ⭐ 613 | 🐛 8 | 🌐 C++ | 📅 2025-03-06 - example LLVM pass
* [DG](https://github.com/mchalupa/dg) ⭐ 525 | 🐛 93 | 🌐 C++ | 📅 2025-05-21 -  Various program analyses, construction of dependence graphs and program slicing of LLVM bitcode
  * dg can integrate SVF, see [here](https://github.com/mchalupa/dg/blob/master/doc/SVF.md) ⭐ 525 | 🐛 93 | 🌐 C++ | 📅 2025-05-21 for details
* [smack](https://github.com/smackers/smack) ⭐ 448 | 🐛 94 | 🌐 C | 📅 2026-08-19 - SMACK Software Verifier and Verification Toolchain
* [dr checker](https://github.com/ucsb-seclab/dr_checker) ⭐ 339 | 🐛 12 | 🌐 C++ | 📅 2022-04-30 - A Soundy Vulnerability Detection Tool for Linux Kernel Drivers
* [seahorn/clam](https://github.com/seahorn/clam) ⭐ 286 | 🐛 4 | 🌐 C | 📅 2026-08-08 - a static analyzer (CLI) based on [seahorn/crab](https://github.com/seahorn/crab) ⭐ 253 | 🐛 2 | 🌐 C++ | 📅 2026-08-16, the latter of which is abstract Interpretation-based library
* [llvm2cpg](https://github.com/ShiftLeftSecurity/llvm2cpg) ⭐ 95 | 🐛 3 | 🌐 C++ | 📅 2021-02-27 - LLVM meets Code Property Graphs
* [llvm2c](https://github.com/staticafi/llvm2c) ⭐ 93 | 🐛 13 | 🌐 C++ | 📅 2025-12-04 - Decompiler of LLVM bitcode to C
* [GaloisInc/yapall](https://github.com/GaloisInc/yapall) ⭐ 68 | 🐛 20 | 🌐 C | 📅 2025-03-01 - A precise and scalable pointer analysis for LLVM, written in Ascent
* [diffkemp](https://github.com/viktormalik/diffkemp) ⭐ 43 | 🐛 56 | 🌐 C++ | 📅 2026-07-31 - Static analysis of semantic differences in kernel versionsa
* [llvm-crash-analyzer](https://github.com/cisco-open/llvm-crash-analyzer) ⭐ 43 | 🐛 19 | 🌐 C++ | 📅 2024-06-26 -- crash analysis against coredump files based on LLVM Machine-IR, together with LLDB
* [S2E](https://github.com/s2e) - Selective Symbolic Execution (use KLEE as symbolic executor)
* [capstone](http://www.capstone-engine.org/beyond_llvm.html) - Disassembler based on the MC component of the LLVM compiler infrastructure
* [DWGrep](http://pmachata.github.io/dwgrep/) - A tool for querying Dwarf (debuginfo) graphs
* [American fuzzy lop (AFL)](http://lcamtuf.coredump.cx/afl/) - LLVM mode for instrumentation

# Bindings

* [llvmlite](https://github.com/numba/llvmlite) ⭐ 2,283 | 🐛 171 | 🌐 Python | 📅 2026-08-18 - A lightweight LLVM **python** binding for writing JIT compilers
* [go-llvm](https://github.com/tinygo-org/go-llvm) ⭐ 290 | 🐛 6 | 🌐 Go | 📅 2026-07-21 - **Go** binding
* [LLVM Rust crates](https://crates.io/search?q=llvm) - **Rust** bindings

# LLVM-backed Languages

* [codon](https://github.com/exaloop/codon) ⭐ 16,830 | 🐛 119 | 🌐 Python | 📅 2026-08-18
* [numba](https://github.com/numba/numba) ⭐ 11,124 | 🐛 1,799 | 🌐 Python | 📅 2026-08-19
* [scala-native](https://github.com/scala-native/scala-native) ⭐ 4,684 | 🐛 420 | 🌐 Scala | 📅 2026-08-17
* [solang](https://github.com/hyperledger/solang) ⭐ 1,382 | 🐛 280 | 🌐 Rust | 📅 2026-08-15
* [ldc](https://github.com/ldc-developers/ldc) ⭐ 1,363 | 🐛 581 | 🌐 D | 📅 2026-08-19
* ~~[go-llvm](https://github.com/go-llvm/llgo) ⚠️ Archived~~
* [Ola](https://github.com/mateeeeeee/Ola) ⚠️ Archived - a toy language, for learning LLVM-backend codegen
* C/C++/ObjC/ObjC++
* [Swift](https://developer.apple.com/swift/)
* [GHC Haskell](https://www.haskell.org/ghc/)
* [Rust](https://www.rust-lang.org)
* [Julia](https://julialang.org/)
* [Crystal](https://crystal-lang.org/)
* [mojo](https://docs.modular.com/)

# Setup

* ⚙️ [LLVM Debian/Ubuntu nightly packages](http://apt.llvm.org/) - Debian APT sources
* ⚙️ [Mac OS Homebrew Formula](\[https://github.com/Homebrew/homebrew-core/blob/master/Formula/llvm.rb]\(https://github.com/Homebrew/homebrew-core/blob/master/Formula/l/llvm.rb\)) - HomeBrew's LLVM formula

# Other relevant resources:

* :octocat: [static-analysis](https://github.com/analysis-tools-dev/static-analysis) ⭐ 14,737 | 🐛 28 | 🌐 Rust | 📅 2026-06-10 - A curated list of static analysis tools and linters for all programming languages, config files, build tools, and more
* :octocat: [dynamic-analysis](https://github.com/analysis-tools-dev/dynamic-analysis) ⭐ 1,101 | 🐛 5 | 🌐 Markdown | 📅 2026-07-20 - A curated list of dynamic analysis tools and linters for all programming languages, binaries, and more
* :octocat: [awesome-llvm-security](https://github.com/gmh5225/awesome-llvm-security) ⭐ 872 | 🐛 0 | 📅 2026-08-14 - awesome llvm security projects
* :octocat: [LLVM-Guide](https://github.com/mikeroyal/LLVM-Guide) ⭐ 202 | 🐛 0 | 🌐 C++ | 📅 2024-01-04
* :octocat: [program analysis topics on GitHub](https://github.com/topics/program-analysis)
* :octocat: other [awesome lists on GitHub](https://github.com/topics/awesome)
* [List of tools for static code analysis (on Wikipedia)](https://en.wikipedia.org/wiki/List_of_tools_for_static_code_analysis)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-19._
