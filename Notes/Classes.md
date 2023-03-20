# Classes
* A class is the definition of a single type of object.
* A class defines a concept (such as a Person) and an object is a single thing based on class(Such as Roodson, Teddy).
## Example
```rb
class Person
  attr_accessor name:, age:, sexe:
end
```
This line of code : ```code attr_accessor name:, age:, sexe: ``` means : Create these 3 attributes and make them accessible 
to be set and changed at will. This means, every time you deal with a Person object in your code, you can change these attributes.

## Instantiation
The process to create an object called : instantiation. Create a new instance (object) of the class.
```rb
# Create a new object
person_instance = Person.new
# Set name attribute 
personn_instance.name = 'Naha Thalie'
```
# Inheritance : <
Inheritance allows different classes to relate to one anotherand group concepts by their similarities.

## Example
```rb
class Pet
  attr_accessor :name, :age, :gender, :color
end

class Snake < Pet
  attr_accessor :length
end

```
# Methods
Methods enable you to tell objects to perform actions.