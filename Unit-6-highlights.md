# Unit 6 : Constructors and Destructors

## **Constructors** : 

* A special member function provided by C++ which enables an object to initialize itself when it is created.


* A constructor that accepts no parameters is called a *default constructor* , the default constructor for class `class_name` is `class_name::class_name()`.
    > If no such constructor is defined then the compiler supplies a default constructor.
* The constructor should be declared in public section 

* They DO NOT have return types 

* They CANNOT be inherited 
    > A derived class can call the base class constructor 

* Constructors CANNOT be *virtual*

* That can have default arguments 

* We cannot refer to the address of a constructor 

* They make "Implicit calls" to the operators **new** and **delete** when memory allocation is required 

### **Parameterized Constructors** :

* The constructors which can take arguments are called Parameterized Constructors

* **Calling the Constructor :**
>```cpp
>// explicit call syntax => <class> <object-name> = <class-name>>(<Parameters>) ;
>// For example :
>integer int1 = integer(0,100) ;
>-----------------------------------------------------------------------------------
>// implicit call syntax => <class-name> <object-name>(<Parameters>) ;
>// For example :
>integer int1(0,100) ;
>```







## **Destructors** : 
* A special member function provided by C++ which destroys the objects when they are no longer needed 

