# Day-1
__2/22/2021__

## What does Inheritance accomplish for us in C#?

Inheritence allows us to reuse code by allowing a child class to inherit from it's parent class. This means that the child will have the same properties as the parent, but could also add on to those.

## How does Member inheritance work in C#? Does a class inherit all members of the base class?

There are two members that are not inherited from their parent. Constructors and finalizers. Everything else is inherited.

## How does accessibility affect inheritance?

Even though members of a parent class are inherited by the child classes, not all of them are visible. Private members aren't visible from child classes unless the child class is nested in the parent class. Protected members are only visible in child classes and internal members are visible in a child class located within the same scope as a parent.

### Afternoon Challenge

https://github.com/JasonSpjute/travel