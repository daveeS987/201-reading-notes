# Read 06 Notes

JS Book  
Ch 3: Object Literals(p100-105)
Ch 5: Document Object Model (p183-242)

Problem Domain

The hardest part of programming is the problem domain. You can make programming easier if you make the problem domain easier or get better at understanding the problem domain. 


## Object Literals

<br>
<br>


## Document Object Model

People will also call DOM an Application Programming Interface (API)  
DOM tree will consist of 4 main types of Nodes  
- Document Node
- Element Node
- Attribute Node
- Text Node

Accessing and updating the Dom tree involves two steps:
1. Access the Elements
  - Select individual element node
    - getElementById()
    - querySelector()
  - Select multiple elements (nodelists)
    - getElementsByClassName()
    - getElementsbyTagName()
    - querySelectorAll()
  - Traversing 
    - parentNode
    - previousSibling / nextSibling
    - firstChild / lastChild

    <br>
2. Work with those Elements
  - Access / update text nodes
    - nodeValue - lets you access or update contents of text node
  - Work with HTML Content
    - innerHTML - allow access to child elements and text content
    - textContent
    - DOM Manipulation -
      - createElement()
      - createTextNode()
      - appendChild() / removeChild()
  - Access or Update Attribute Values
    - className / id
    - hasAttribute()
    - getAttribute()
    - setAttribute()
    - removeAttribute()

- DOM Queries - methods that find elements in the DOM tree
- Storing elements in a variable really means storing the location of the element(s) within the DOM tree. The properties and methods of that element node work on the variable. It saves the browser from searching the element multiple times. Known as caching

    




