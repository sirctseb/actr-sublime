ACT-R Sublime
============
A Sublime Text 2 Package for ACT-R development
---
Snippets
---
Productions
```lisp
(P name
==>
)
```
Productions with a goal test
```lisp
(P name
  =goal>
    ISA
==>
)
```
Productions with a goal state transition
```lisp
(P name
  =goal>
    ISA
    state   name
==>
  =goal>
    state
)
```
