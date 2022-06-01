# 1 June 2022

## Writing Specs
We should write the specs in a simple english model and do not write any logics in the specs because if our logic is wrong, the spec will fail even the spec was actually correct. Whole spec became wrong because of that incorrect logic. 

Example :

If we specify the perimeter of a rectangle should be `4 times the length`. Here we know the logic our spec may pass but in real we can't specify. So, we should avoid writing any logic in spec and ensure the spec has a behaviour.

## Cyclometric Complexity
Cyclomatic complexity of a code section is the quantitative measure of the number of linearly independent paths in it. It is a software metric used to indicate the complexity of a program.

For example, if source code contains no control flow statement then its cyclomatic complexity will be 1 and source code contains a single path in it. Similarly, if the source code contains one if condition then cyclomatic complexity will be 2 because there will be two paths one for true and the other for false. 

But if we go implementing many control flow statement our code not look good, In that cases we can use terinary operator to make our code look good.


## YMMV

(abbrevation) `your mileage may vary`

### Concrete class

A concrete class is a class that we can create an instance of, using the new keyword.

In other words, it's a full implementation of its blueprint. A concrete class is complete.

Imagine, for example, a Car class:

```
public class Car {
    public String honk() {
        return "beep!";
    }

    public String drive() {
        return "vroom";
    }
}
```

Because all of its methods are implemented, we call it a concrete class, and we can instantiate it:

```
Car car = new Car();
```

## Delegation and Inheritence
Delegation is a way to make composition as powerful for reuse as inheritance . In delegation, two objects are involved in handling a request: a receiving object delegates operations to its delegate. This is analogous to subclasses deferring requests to parent classes. But with inheritance, an inherited operation can always refer to the receiving object through the this member variable in C++ and self in Smalltalk. To achieve the same effect with delegation, the receiver passes itself to the delegate to let the delegated operation refer to the receiver.

We should prefer Immutability over mutability.

## Liskov Substitution principle (LSP)
The Liskov Substitution principle was introduced by Barbara Liskov in her conference keynote “Data abstraction” in 1987. A few years later, she published a paper with Jeanette Wing in which they defined the principle as:

```
Let Φ(x) be a property provable about objects x of type T. Then Φ(y) should be true for objects y of type S where S is a subtype of T.
```

`Reference : ` https://stackify.com/solid-design-liskov-substitution-principle/

## Factory Pattern
Factory pattern is one of the most used design patterns in Java. This type of design pattern comes under creational pattern as this pattern provides one of the best ways to create an object.

In Factory pattern, we create object without exposing the creation logic to the client and refer to newly created object using a common interface.

`Reference : ` https://www.tutorialspoint.com/design_pattern/factory_pattern.htm