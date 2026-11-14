### What did you predict for Warmup.java, and what did it actually print? Explain the lines that surprised you.

##### 7 5.0 -126
##### Two
##### Three

I predicted almost same output before the code got executed. The part that suprised me was (byte)130 is giving -126.



### What is the difference between the static variable totalProducts and the instance variable name?

totalProducts is a static variable and is shared across all the objects. Any object can update totalProducts and any other object can consume the value of totalProducts as well.
name is an Instance variable, every object has its own copy of instance variable, so every object have its own value for the variable name. Changing the value of variable name in a object will not affect the value of name in another object.

### What does the copy constructor do, and why does changing p2.name not change p1.name?

Copy constructor is a constructor used to initilize another object using an existing object. p2, p1 are different objects of the same class, and every object has its own copy of the instance variables of the class, updating an instance variable of one object (p1) will not affect the same instance variable that belongs to another object (p2).

### Why does Java force you to write (int) average when converting a double to an int, and what happens to the decimal part?

While converting from double to int, Java demands explicit typecasting by providing the datatype to which the data needs to be typecasted within paranthesis. This is done to prevent information loss and the decimal part gets truncated.