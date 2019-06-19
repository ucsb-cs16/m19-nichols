---
num: "lect11"
desc: "The good, bad and ugly about pointers, C++ Memory Model, Dynamic memory allocation (Heap), Heap vs Stack"
ready: true
pdfurl: /lectures/CS16_Lecture11.pdf
annotatedpdfurl: /lectures/CS16_Lecture11_ann.pdf
annotatedready: true
lecture_date:  2019-05-09
---

## Code from lecture

<https://github.com/ucsb-cs16-s19-nichols/code-from-class/tree/master/05-09>

## Stuff I wrote on the "whiteboard"

Go here and click on the appropriate date:
<https://1drv.ms/o/s!AlgIeD1urAgmgQHsG_JzMJgKHx9V>

## Kevin's Notes

[Follow this link to access the notes](/lectures/CS16_Lecture11_Notes.docx){:data-ajax="false"}

# Topics

The good:

* Pointers allow arrays to be passed to functions efficiently
* Pointers allow arrays of large structs to be traversed effiently

The bad:

* Pointers can only point to one type of data (not generic)
* They don't automatically point - need to do some work

The ugly

* Bugs in code that involves pointers can cause your program to irrecoverably crash (Segmentation fault)
* Examples: dereferencing a null pointer, out of bound array access, dereferncing a pointer that has junk value.

## C++ Memory model
* Barebones model of memory: value vs address
* Scope: local vs. global
* Layout of compiled C++ program in memory: text, global data , heap and stack


* A first look at dynamic memory allocation
* The hows and whys of creating data on the stack vs. heap

