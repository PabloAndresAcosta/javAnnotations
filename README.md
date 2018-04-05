# javAnnotations
Practices on java anotations

form "https://dzone.com/articles/creating-custom-annotations-in-java"
How are Annotations Processed?
Processing annotations is accomplished through the Java Reflection Application Programming Interface (API). Sidelining the technical nature of the reflection API for a moment, the reflection API allows us to write code that will inspect the class, methods, fields, etc. of an object. For example, if we create a method that accepts a Car object, we can inspect the class of this object (namely, Car) and discover that this class has three fields: (1) make, (2) model, and (3) year. Furthermore, we can inspect these fields to discover if each is annotated with a specific annotation.
