# Java Infinite Loop Bug

This repository contains a simple Java program that demonstrates an infinite loop due to improper variable incrementation within the loop condition. The bug is explained, and a corrected version is provided. 

## Bug Description

The program intends to print numbers from 0 to 4. However, the `x++` within the `println` method and the separate `x = x + 1;` statement outside create a situation where x never reaches 10 causing an infinite loop. 

## Solution

The corrected version ensures that the loop counter is incremented correctly. The unnecessary second increment is removed, resolving the infinite loop issue.

## Usage

1. Clone the repository.
2. Compile and run the Java files: `javac BuggyLoop.java` and `java BuggyLoop`. 
3. Compare the outputs of the buggy and corrected versions.