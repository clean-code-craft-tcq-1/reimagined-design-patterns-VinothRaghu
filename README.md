# reimagined-design-patterns

Give a summary description of Four design patterns that you choose from the following design patterns: **Adapter,  Builder, Composite, Decorator, Observer, Interpreter, State, Mediator, Memento, Prototype, Proxy**. In your summaries say:

- what kind of problem(s) you can solve with that pattern and when you use it, maybe with a short example
- how the pattern works, what the basic idea of the pattern is
- what the main advantage and what the the main disadvantage is of using this pattern
- Write a short summary for each of the four patterns, about half a page for each pattern (rather less than more). 

> Do not add diagrams, and do not try to give a complete description of the patterns as found in the books. Rather think of how you would explain the essential ideas of these patterns in a few sentences to a colleague while drinking coffee.




# Observer Design Pattern

**Example:**
Normal Modern Cars cosist of 40 to 80 ECU's(Electronic Control Unit) .They will interact through vehicle networs. For example if vehicle camera node detects object in front of vehicle then it will notify all other ECU about the collision condition.which means all ECU will get notify from Camera ECU when value changes from normal to collosion condition and only relevent ECU like Brake ECU will act and Stop the Vehcile to avoid collision .
This is the Typical Example for Observer Pattern

**Definition:**
1)Observer is a behavioral design pattern. 
2)It specifies communication between objects: observable and observers.
3)An observable is an object which notifies observers about the changes in its state
4)if change in one object states then all its dependents are notified and updated automatically

**Advantage:**
1)closely monitored by other components
2)Allows you to send data to many other objects in a very efficient mannor
3)In terms of the programming language used, there are no specific restrictions in principle for the observer design pattern
4)No modification is need to be done to the subject to add new observers.
5)You can add and remove observers at anytime

**Disadvantage:**
1)If not used carefully the observer pattern can add unecessary complexity
2)The order of Observer notifications is undependable
3)Heavily depend on other node



# Adapter Design Pattern

**Example:**
Adapter pattern can be effectively used when we are trying to interface one type of communication with another.(Converter)
Here, we are taking the webcam as an example:
The operation of webcam is to capture the real world and display it image format.
For performing image processing algorithms data shoud be in strings.so for automatic vehicle detection, we are using camera as an interface to capture the number plate of the vehicle and performing OCR technique to convert that image into string and validating it.
This images into string or array of binaries is one type convesation .
This is typical Example for Adapter pattern.

**Definition:**
An adapter design pattern is an structural design pattern
It is used to convert one type of data into another type for compatability
It works as an interface between the two objects

**Advantage:**
- Reusability

**Disadvantage:**
- More no of coding lines makes design complex



# Decorator Design Pattern

**Example:**
For Battery Monitoring System, the alerts and triggers functionalities are present.
to extend these functionalities, we will add the web UI interface for the same functionalities.
for alerts, the web UI interface will be developed to display , how many alerts popped up at given period of time in the browser(PC/Mobile)
>A Clean and neat Web UI interface functionality can de developed on top of the existing functionality without modifying any lines in the code and providing customer a valuable >content to view everything in their hands itself

**Definition:**
An Decorator design pattern is an structural design pattern.
It is used to add additional features or behaviors to a particular instance of a class, without modifying the other instances of same class
Difference between adapter and decorator pattern is adapter pattern is used to convert the interface of object, where
decorator object is to extend the functionality of same object

**Advantage:**
- Flexible Design without breaking existing code

**Disadvantage:**
- Difficult to understand the existing functionality, if we extend the same


