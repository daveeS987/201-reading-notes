# Read 07 Notes

Article: Domain Modeling
HTML Book: Chapter 6: "Tables" (p126-145)
JS Book: Chapter 3: "Functions, Method, and Objects" (p106-144)

## Object Oriented programming in Javascript Fundamental

1. `new` Keyword instantiates(create) an object
1. Constructor function initializes properties inside the object with `this` variable
1. The object is stored in a variable for later use  

## Tips to follow when building domain models.

1. When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
1. Model its attributes with a constructor function that defines and initializes properties.
1. Model its behaviors with small methods that focus on doing one job well.
1. Create instances using the new keyword followed by a call to a constructor function.
1. Store the newly created object in a variable so you can access its properties and methods from outside.
1. Use the this variable within methods so you can access the object's properties and methods from inside.

## Tables

Elements to be familiar with

```
<table>
<tr> table row
<td> table data
<th> table heading
colspan attribute (left to right)
rowspan attribute (up and down)
<thead>
<tbody>
<tfoot>
``` 

## Functions, Methods, Objects

