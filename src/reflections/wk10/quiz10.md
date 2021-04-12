# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
Namespaces are used to organize code into logical groups and to prevent name collisions that can occur especially when your code base includes multiple libraries
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
class combines the fields and methods(member function which defines actions) into a single unit

structure is a collection of variables of different data types under a single unit
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
void
```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
public
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
that the return object will be a string
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
creating a car object
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
overriding the method Start as a virtual or global method?
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public
private
protected
internal
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
can be accessed only by code in the same class or struct
```