# Class Notes Week X
# Java 1 review
	## Methods
		-EX:'public statc int[] reverseArray(int[] array)'
	## Instance methods
		- Accessors: Methods used to report the state of objects
		- Mutators: Methods used to change the state of objects
			- If there are no methods that change the state of an object. These are called immuatable 
			- There are many methods that change the state of an objects state. We call these mutable 
		### Special cases
			- Getters: accessor mehtods used to reports the low-level state of objects
			- Setters: Mutator methods to change low-level state of objects
		### Method overloading
			- Overloading: using the same method name, but different parameters
				- Common when we want to assume default parameters
				- or when different types convey similar types of information
	
	## Objects: One instance of a class
		- Occupies a piece of memory in the heap
		- Each instance has its own memory
		- The set of values stored in this memory block is called the state of the object
	## Memory allocation
		### The stack
			- Includes references and values
		### The heap
			- Slower to access
			- Includes names and contents of references and values
		
		
	## UML Diagram
		- UML is a spatial representaion that describes the contents of the code
		- "+" is used for public
		- "-" is used for private
		- Used for class to map out the code
		- Name at the top is the name of the Class
		- Initializations go at the top and the methods with return types go at the bottom
	## Classes: A means of creating new types
		- Group data elements that describe some abstract concept
		- Provide methods that operate on these data elements
		- These elements can be primitive data or other objects
		- Class names start with a capital letter
		- Classes include data as well as methods
		- ** This is an important way to organize your code **
		### A class is a contract
			- The set of instance methods define the legal ways an object can be accessed/mutated
			- All operations on an object: must always leave the object inn a consistent state
		### A Class as an "Ecapsulator"
			- A class hides many details from the outside world
			- The user of a class only has to worry about the class' public interface
				- Easier to understand how to use class
				- The implementaion of the class can change without the user knowing
		### Public vs Private
			- Public pros
			 	- Easy access to all data by other classes
				- Don’t have to implement getters and setters
			- Public cons
				- Can’t protect the data from other classes – easy to get into an inconsistent state
				- Therefore, the class cannot make any guarantees about how it behaves
		### Instance vs Class Data
			- Each object gets its own copy of instance data
			- All objects in a class share one copy of class data
				- In UML, class variables are underlined
				- IN the class definition, class variables are declared as static
	## Problem Solving
		- Understand the problem
		- Design a solution
		- Consider alternitives and refine
		- implemnt the solution
		- Test the solutiom
	## Difference between a char[] and a String
		- char[] is a primitive data type
		- String is a class (able to use methods that are already created)
			- toString, toLowerCase, toUperCase, startsWith
		
