# TractableCSPm
## Matt Luckcuck 2018
### m.luckcuck@gmail.com
A Work in Progress library of CSPm modules that provide tractable data structures

This is a side-project of mine, based on trying to solve some problems I ran into during my PhD. A presentation outlining (model-checking,) the problems I encountered, and how they were initially solved can be found [here](https://mluckcuck.github.io/files/presentations/efficientModelChecking.pdf). These initial solutinos were constructed with the help of Tom Gibson-Robinson.

Here, I intend to construct CPSm modules that each encapsulates one data structure, built in a way that FDR 'likes', thereby making analysis using them tractable. Standard approaches lead to state explosion, which this library intends to side-step.
