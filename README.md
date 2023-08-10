# CPP_session
C++ session 

1. Encapsulation
2. Abstraction
3. Inheritance
4. Polymorphism
5. Classes
6. Objects

Classes and Objects:

![image](https://github.com/chaitanyaGa/CPP_session/assets/7933528/e2f91eab-b4e7-486c-9989-b94a1c20b2bd)

**1. Encapsulation**

Encapsulation is the wrapping of important information inside an object. In other words, the variables and methods are stored inside the object upon its creation.

Encapsulation prevents unwanted access outside of the class. This concept is beneficial in guarding the usage of your program. You probably don’t want your clients to make some catastrophic changes to your software.

To realize this restriction, we need something that lets us specify the ‘security level.’ And this is where access modifiers kick in.

Access modifiers

Access modifiers are public and private as you see in the example above. (There is another called protected , more about this later)

We can specify the class members as public or private. By default, all members of a class are private, unless they are specifically labeled as public.

Public members can be accessed directly by any object user, but private members can only be accessed by the object itself.

Taking the example above, we declared price as a private member because we don’t want users to access it directly. We defined the methodsetPriceas a public member to allow other users to set the price only by calling the method explicitly.

Example:

```C++
int main(){
   Fruit banana(1.25, "yellow");
   
   // error   
   std::cout << banana.color << std::endl;
   }
```
The object banana cannot directly access the class variable color in main() .

The access modifiers help restrict the usage of certain class members. You may refer to [this complete guide](https://www.programiz.com/cpp-programming/access-modifiers) to learn more about access modifiers.

**2. Abstraction**

Data abstraction in OOP means showing only the essential information while hiding the details from the end-user. This concept is an extension of encapsulation.

In class, abstraction refers to separating a class’s interface from the implementation details.

If you still can’t get it, you may understand as — “You only see what I choose to show you”

what part is exposed while how part is hidden from external user of class.

Abstraction allows us to use straightforward classes to express complex details.


Further study:
Design Patterns
Open source contribution
Compilation processs of languages.

