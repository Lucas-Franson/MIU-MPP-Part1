# MIU-MPP-Part1
Maharishi International University 
Modern Programming Practices

## Relationship (UML)
### Associations
![Image representing the association relationship between two classes](Association.png)
- A has a B
- Permanent relationship
- A keeps a reference to B 

### Dependency 
![Image representing the dependency relationship between two classes](Dependency.png)
- Temporary relationship
- Dependency does not keep reference between classes

### Inheritance
![Image representing the inheritance relationship between two classes](Inheritance.png)
- A obtain properties and behaviors of B
- A is a type of B

## Relationship Names
Giving a specific user requirement text, the nouns will become the classes and the verbs will become the names, then we can create an association matrix, example:

|           | Student | Professor     |
|----------:|---------|---------------|
| Student   |         | is teached by |
| Professor | teaches |               |
