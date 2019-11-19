# vr.pyv

vr.pyv is a specification of [Viewstamped Replication][vrr] in [mypyvy][mypyvy].

## State Machine Diagrams

There are a number of useful state machine diagrams for Viewstamped Replication described in
[_the morning paper_][tmp] by Adrian Colyer. They are replicated here below.

### Normal Operation

![state diagram for normal operation](https://adriancolyer.files.wordpress.com/2015/03/vr-normal.jpg?w=1280&h=566)

### View Change

![state diagram for view change](https://adriancolyer.files.wordpress.com/2015/03/vr-view-change.jpg?w=1280&h=1184)

[vrr]: http://www.pmg.csail.mit.edu/papers/vr-revisited.pdf 
[mypyvy]: https://github.com/wilcoxjay/mypyvy
[tmp]: https://blog.acolyer.org/2015/03/06/viewstamped-replication-revisited/
