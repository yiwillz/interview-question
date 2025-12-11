## OOP 
 OOP（object-oriented program）： organized software design around data and object rather than functions and logic.

>benfit: compare to proceduaral programming; modularity and reusability(模块化和可复用性); maintainability（可维护性）; scalability（可扩展性）

> language: Java, Python, C++, C#, Rudy, JavaScript, Swift
### class and object
#### class (类)

a template or a recipe - to defines what an object will contain(its data) and what it will be able to do(its behavior) 

>attribute(图上)， methods（图下）
![alt text](image.png)
#### object(对象)
the instance of a class, a food(创建出的实体)
* 有独立的数据，独立于其他对象

### enum(枚举)
define constant, type safe
* 枚举后的对象可以包含额外的数据和行为

### interface(接口)
what and how a component should do 
* extensible, testable, loosely coupled (可扩建，可测试，松耦合性【模块化】)

### 四大特性
* encapsulation (封装)
>Encapsulation = Data hiding + Controlled access

将数据和方法分组到一个类，并限制细节访问，通常使用private【getter,setter】, protected, public
* abstraction (抽象)
>Abstraction = Hiding Complexity + Showing Essentials

只展现高级功能，隐藏细节，通常将“是什么”和“如何做” 分开，通过抽象类（子类如何做）；接口，公共API 实现

* inheritance (继承)
> subclass = parent class(properties + behaviors)

复用性，一般只在"是一个"的情况下使用，而不是"拥有一个"或“使用一个”(用composition)

* polymorphism (多态)
> different object call same method in different way

1. compile-time(static binding)/method overloading 静态 - 运行前
2. runtime (dynamic binding)/method overriding 动态 - 运行时

