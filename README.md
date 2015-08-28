# BenderOS
Rust Unix-like OS Implementation

-- Some thoughts about maybe building a language that can be compiled to. Rust's MIR RFC could be a potential target, which is able to encapsulate the desired performance I'm after, and allowing me to design the syntax however I want, in say LISP. I could use this to build a scripting language that I want! (maybe in a shell too!).

This comment on SO has some interesting ideas:
http://programmers.stackexchange.com/questions/139134/do-all-functional-languages-use-garbage-collection

Here's an idea to allow efficient functional languages at the hardware level:
http://stackoverflow.com/questions/791437/why-dont-purely-functional-languages-use-reference-counting

* This SO question has some good links to get started:
* http://stackoverflow.com/questions/12924319/writing-an-os-with-uefi

EXPLICIT GOALS:
All the code required to boot a custom OS, using UEFI.
