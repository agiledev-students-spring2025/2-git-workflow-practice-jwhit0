# Git Practice

## [Goodbye, Object-Oriented Programming](https://cscalfani.medium.com/goodbye-object-oriented-programming-a59cda4c0e53)


What I found interesting about this article is how it discusses the conflicts that can arise with OOP when working with more complex systems. OOP can result in rigid, extensive, or cyclical class hierachies, making software harder to grow. The author also discusses how slight changes in a base class can lead to unintentional and adverse changes in the logical behavior of derived classes. Another interesting issue the author mentions is that of encapsulation, and how when a piece of code passes a reference of an object to a constructor without copying, changes made to the object can result in broken encapsulation. The solution would be to copy, but it can be an issue when there are deep class hierachies involved.


### [brian105's](https://github.com/brian105) thoughts on this article


I liked how the author poked holes into the normally sturdy paradigms of OOP languages. Its rigidity can be its downfall, as things that seem logical to people wouldn't work properly, like when fiddling with inheritance (especially of built-in methods.) That being said, there are enough pros to OOP that it still remains the most popular programming model.
