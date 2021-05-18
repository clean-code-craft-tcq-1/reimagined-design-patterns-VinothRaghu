# reimagined-design-patterns

Give a summary description of Four design patterns that you choose from the following design patterns: **Adapter,  Builder, Composite, Decorator, Observer, Interpreter, State, Mediator, Memento, Prototype, Proxy**. In your summaries say:

- what kind of problem(s) you can solve with that pattern and when you use it, maybe with a short example
- how the pattern works, what the basic idea of the pattern is
- what the main advantage and what the the main disadvantage is of using this pattern
- Write a short summary for each of the four patterns, about half a page for each pattern (rather less than more). 

> Do not add diagrams, and do not try to give a complete description of the patterns as found in the books. Rather think of how you would explain the essential ideas of these patterns in a few sentences to a colleague while drinking coffee.



# Adapter Design Pattern

An adapter design pattern is an structural design pattern
It is used to convert one type of data into another type for compatability
It works as an interface between the two objects

**Advantage:**
- Reusability

**Disadvantage:**
- More no of coding lines makes design complex

**Example:**

Adapter pattern can be effectively used when we are trying to interface one type of communication with another

Here, we are taking the webcam as an example:
The operation of webcam is to capture the real world and display it in the application.
For performing image processing algorithms, we should use webcam to capture the images, store it and processing it.
For automatic vehicle detection, we are using camera as an interface to capture the number plate of the vehicle and 
performing OCR technique to convert that image into string and validating it.

>In python, we are using image processing module named as OpenCV to capture the webcam, store in the local disk 
>and processing to get desired output


# Decorator Design Pattern
An Decorator design pattern is an structural design pattern.
It is used to add additional features or behaviors to a particular instance of a class, without modifying the other instances of same class
Difference between adapter and decorator pattern is adapter pattern is used to convert the interface of object, where
decorator object is to extend the functionality of same object

**Advantage:**
- Flexible Design without breaking existing code

**Disadvantage:**
- Difficult to understand the existing functionality, if we extend the same

**Example:**

For Battery Monitoring System, the alerts and triggers functionalities are present.
to extend these functionalities, we will add the web UI interface for the same functionalities.
for alerts, the web UI interface will be developed to display the customer, how many alerts popped up at given period of time in the browser(PC/Mobile)
>A Clean and neat Web UI interface functionality can de developed on top of the existing functionality without modifying any lines in the code and providing customer a valuable >content to view everything in their hands itself
