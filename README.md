# JavaScript Closure Gotcha in Loops

This repository demonstrates a common error in JavaScript related to closures within loops.  The example uses `setTimeout` inside a loop, leading to unexpected results.  The solution shows how to correctly capture the loop variable's value using an immediately invoked function expression (IIFE).