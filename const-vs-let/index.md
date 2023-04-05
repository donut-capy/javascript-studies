# Const vs let #

> `const` vs `let` vs `var` you definetly want to use `const`, and **never** **never** **never** use `var`

This is a very controversial topic, with sparkling conversations. It seems that the majority view is that one should use `const` as much as possible, only falling back to `let` where necessary.  

## `const` ##

we use `const` to declare variables, and it's value cannot be changed once it's defined

## `let` ##

we use `let` as a block-scoped local variable, optionally initializing it to a value that can be changed later

### Why `const`? ###

* **You choose it:** in reality
* **Just one thing:** if you're thinking about using `const` or `let` everytime you use it, you're wasting your time
* **Reassinign may cause bugs:** In a longer function, it can be easy to miss when a variable is reassigned. This may cause bugs
* **Performance benefits:** JavaScript engines could make code using `const` run faster due to the knowledge the variable won’t be reassigned