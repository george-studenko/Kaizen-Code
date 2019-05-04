# Object Calisthenics
By applying object calisthenics you can get code that is more:
* Readable  
* Reusable  
* Testeable
* Maintenable 

## Rules

### 1. Only **one** level of indentation per method.  
This will make a method more readable as you will need to extract out pieces of code for example for loops or conditionals and put a meaningful name to those methods which are going to be called in this method.  
#### Benefits  
* Single responsibility
* Better naming
* Shorter methods
* Reusable methods

### 2. Don't use the **else** keyword
Else keywords will add complexity to the code and create non linear flows (adding more use cases)

### Ways to avoid using the else keyword
* Use default values
* Early return
* Extract code
* Use polymorphism
* State pattern
* Strategy pattern

#### Benefits
* Avoid code duplication
* Lower complexity 
* Readability 

### 3. Wrap primitive types
By wrapping primitive types into classes we can encapsulate the type and have control from a single place in case we need to refactor or change the primitive type later on, it also helps to make more readable by giving a hint of what exactly a method parameter is receiving

#### Benefits
* Encapsulation
* Type hinting
* Attracts similar behavior

