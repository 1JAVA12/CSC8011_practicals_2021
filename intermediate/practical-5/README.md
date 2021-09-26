# practical-5


Make sure to fork this project into your portfolio space before progressing 
with the practical. if you do not do this, then your changes may not be saved

Instructions on how to do this can be found [here](https://ncl.instructure.com/courses/24644/pages/forking-or-cloning-a-project?module_item_id=1228552)

A video showing a step by step on how to do this can be found [here](https://web.microsoftstream.com/video/4ecb0839-6fd9-48bc-b563-3ab2122ef011)

## Practical-5.1

This practical extends upon practical 4. Copy and paste your `Garage` and
 `Car` implementations into the `Garage` and `Car` classes provided
 
 In the IO class, you will see the following code
 
 ```java
public class IO {

    public static void main(String[] args) {
        new IO().run();
    }

    public void run() {
        Controller c = new Controller();
    }
}
```
This IO class will act as the main class that handles the input and output to
 this system.
 
In the Controller class you will see the following code

```java
import java.util.ArrayList;

public class Controller {
    public ArrayList<Garage> garages = new ArrayList<>();
    public ArrayList<Car> cars = new ArrayList<>();
    
}
```

The controller class will handle the objects of garages and cars using the
 ArrayLists provided.
 
In the Controller class, add the following methods:
    - a method to add a garage object to the ArrayList
    - a method to add a car object to the ArrayList
    
## Practical 5.2

In the IO class, create a basic command line menu to add the ability to do
 the following:
    - create a car object from information from the command line, using a
     scanner, and use the Controller method created in 5.1 to add the car to
      the system
    - create a garage object from information from the command line, using a
         scanner, and use the Controller method created in 5.1 to add the car to
          the system

## Practical 5.3

In the Controller class, provide a methods that do the following:
- filter all cars with a given age
- filter all cars with a given make
- filter all cars that are younger than a given age

## Practical 5.4

In the IO class, extend the command line menu so that you can invoke the
 filters in the Controller class
 
## Practical 5.5

**Observation Task**
Have a look at the solution for this practical and see if you can see any
 comparisons with what is being asked in the assessment.

          
      
