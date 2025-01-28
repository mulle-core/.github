# mulle-core

In terms of scope the github orgnaization *mulle-core* provides 

* platform specific functionality that is outside of the C standard libraries offers (e.g. mulle-mmap)
* code that is a fusion of *mulle-c* and *mulle-concurrent*, but topically outside of the scope of *mulle-concurrent*, (e.g. mulle-fprintf)

The library [**mulle-core**](https://github.com/mulle-core/mulle-core) is an amalgamation of the following libraries:

| Constituent                                  | Description
|----------------------------------------------|-----------------------
| [mulle-allocator](https://github.com/mulle-c/mulle-allocator) | 🔄 Flexible C memory allocation scheme
| [mulle-buffer](https://github.com/mulle-c/mulle-buffer) | ↗️ A growable C char array and also a stream
| [mulle-c11](https://github.com/mulle-c/mulle-c11) | 🔀 Cross-platform C compiler glue (and some cpp conveniences)
| [mulle-container-debug](https://github.com/mulle-c/mulle-container-debug) | 🛄 Debugging support for mulle-container
| [mulle-container](https://github.com/mulle-c/mulle-container) | 🛄 Arrays, hashtables and a queue
| [mulle-data](https://github.com/mulle-c/mulle-data) | #️⃣ A collection of hash functions
| [mulle-http](https://github.com/mulle-c/mulle-http) | 🈚 http URL parser
| [mulle-rbtree](https://github.com/mulle-c/mulle-rbtree) | 🍫 mulle-rbtree organizes data in a red/black tree
| [mulle-regex](https://github.com/mulle-c/mulle-regex) | 📣 Unicode regex library
| [mulle-slug](https://github.com/mulle-c/mulle-slug) | 🐌 Creates URL slugs
| [mulle-storage](https://github.com/mulle-c/mulle-storage) | 🛅 Memory management for tree nodes
| [mulle-unicode](https://github.com/mulle-c/mulle-unicode) | 🈚 Unicode ctype like library
| [mulle-url](https://github.com/mulle-c/mulle-url) | 🈷️ Support for URL parsing
| [mulle-utf](https://github.com/mulle-c/mulle-utf) | 🔤 UTF8-16-32 analysis and manipulation library
| [mulle-vararg](https://github.com/mulle-c/mulle-vararg) | ⏪ Access variable arguments in struct layout fashion in C
| [mintomic](https://github.com/mulle-concurrent/mintomic) | For more information, see [the documentation](http://mintomic.github.io/) or the accompanying blog post, [Introducing Mintomic](http://preshing.com/20130505/introducing-mintomic-a-small-portable-lock-free-api).
| [mulle-aba](https://github.com/mulle-concurrent/mulle-aba) | 🚮 A lock-free, cross-platform solution to the ABA problem
| [mulle-concurrent](https://github.com/mulle-concurrent/mulle-concurrent) | 📶 A lock- and wait-free hashtable (and an array too), written in C
| [mulle-fifo](https://github.com/mulle-concurrent/mulle-fifo) | 🐍 mulle-fifo fixed sized producer/consumer FIFOs holding `void *`
| [mulle-linkedlist](https://github.com/mulle-concurrent/mulle-linkedlist) | 🔂 mulle-linkedlist a wait and lock-free linked list
| [mulle-multififo](https://github.com/mulle-concurrent/mulle-multififo) | 🐛 mulle-multififo multi-producer/multi-consumer FIFO holding `void *`
| [mulle-thread](https://github.com/mulle-concurrent/mulle-thread) | 🔠 Cross-platform thread/mutex/tss/atomic operations in C
| [dlfcn-win32](https://github.com/mulle-core/dlfcn-win32) | ===========
| [mulle-dlfcn](https://github.com/mulle-core/mulle-dlfcn) | ♿️ Shared library helper
| [mulle-fprintf](https://github.com/mulle-core/mulle-fprintf) | 🔢 mulle-fprintf marries mulle-sprintf to stdio.h
| [mulle-mmap](https://github.com/mulle-core/mulle-mmap) | 🇧🇿 Memory mapped file access
| [mulle-sprintf](https://github.com/mulle-core/mulle-sprintf) | 🔢 An extensible sprintf function supporting stdarg and mulle-vararg
| [mulle-stacktrace](https://github.com/mulle-core/mulle-stacktrace) | 👣 Stracktrace support for various OS
| [mulle-time](https://github.com/mulle-core/mulle-time) | 🕕 Simple time types with arithmetic on timespec and timeval


*mulle-core* is based on [mulle-concurrent](//github.com/mulle-concurrent) and 
[mulle-c](//github.com/mulle-c). 

The [MulleFoundation](https://MulleFoundation.github.io) is based on mulle-core.
