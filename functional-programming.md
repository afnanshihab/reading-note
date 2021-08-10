# FUNCTIONAL PROGRAMMING

* ***What is functional programming?***

Its a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data

* ***What is a pure function and how do we know if something is a pure function?*** 

It returns the same result if given the same arguments (it is also referred as deterministic)  ...It does not cause any observable side effects

* ***What are the benefits of a pure function?***


The code’s definitely easier to test. We don’t need to mock anything. So we can unit test pure functions with different contexts:

*parameter A : the function returns value B*



* ***What is immutability?***

When data is immutable, its state cannot change after it’s created. If you want to change an immutable object, you can’t. Instead, you create a new object with the new value.


* ***What is Referential transparency?***

Basically, if a function consistently yields the same result for the same input, it is referentially transparent.

*pure functions + immutable data = referential transparency*


-----------
* ***What is a module?***

Module is just essentially another JavaScript file

* ***What does the word ‘require’ do?***

That is in the global object in node js and we can use it any where

* ***How do we bring another module into the file that we are working in?***


Export it from the module file and then require it at our file


* ***What do we have to do to make a module available?***

Store the required as a variable and export it


#### Things I want to know more about
Learning more about import and export modules.

To learne  more watch and read  :
[Node JS Tutorial for Beginners #6 - Modules and require()](https://www.youtube.com/watch?v=xHLd36QoS4k)

[Concepts of Functional Programming in Javascript](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)