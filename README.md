# Python practice questions 
- Declare a function called username that takes one argument as a string and returns the name
```python
def username(string):
    return string

print(username("Hello"))
```
- 2. Create AND - &&  & ==  Which one returns a bool value?
```python
Name = "Ron"
if Name == "Ron":
```
- 3. Declare a list with numbers 1 to 5 and iterate through the list and display list
```python
list = [1.,2,3,4,5]
for num in list:
    print(num)
``` 

- 4. What is the difference between a list and a tuple?
```python
A list is mutable, is defined with []
A tuple is immutable, defined with ()
```

5. Can we add an element to a list? - yes

Can we add an element to a tuple? - no

Can the elements of a tuple contain different types? - yes


- 6. Create a dictionary with key values firstname and lastname
```python 
dict = {"firstname":"John", "lastname":"Doe"}
```   
- 7. Add course to the dictionary
```python
dict = {"firstname":"John", "lastname":"Doe"}
dict['course'] = 'DevOps'
print(dict)
```

- 8. Create a class named student, initialise class and create an object of the class
```python
class Person:
  def __init__(self, name):
    self.name = name
student = Person("abc")
print(student.name)
```