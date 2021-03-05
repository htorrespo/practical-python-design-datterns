<!--
https://link-springer-com.ezproxy.unal.edu.co/chapter/10.1007/978-1-4842-2680-3_2
-->

## The Problem

One of the first debugging techniques you learn is simply printing the values of certain variables to the console. This helps you see what is going on inside your program. When the programs you write become more complex, you reach a point where you cannot run the whole program in your mind effectively. This is when you need to print out the values of certain variables at specific times, especially when the program does not act as you expect it to. Looking at the output of your program at different points in its execution helps you locate and fix bugs swiftly.

Your code quickly becomes littered with print statements, and that’s fine, until one fine day when you deploy your code. Running your code on a server, as a scheduled job on your own machine, or as a standalone piece of software on a client’s computer means that you can no longer rely on the console for feedback when something goes wrong. You have no way of knowing what went wrong or how to replicate the issue. This takes debugging from the realm of science straight into gambling.

The simplest solution is to replace print statements with a command to write the output to a file instead of to the console, like this:
