# Read 06 Notes

**JS Book**  
Ch 3: Object Literals(p100-105)  
Ch 5: Document Object Model (p183-242)  

## Problem Domain

The hardest part of programming is the problem domain. You can make programming easier if you make the problem domain easier or get better at understanding the problem domain. 


## Document Object Model

People will also call DOM an Application Programming Interface (API)  
DOM tree will consist of 4 main types of Nodes  
- Document Node
- Element Node
- Attribute Node
- Text Node

## Accessing and updating the Dom tree involves two steps:

1. Access the Elements:

  - Select individual element node  
    - getElementById('id') -
    - querySelector('css selector') - returns first element match. ex 'li.hot'  

  - Select multiple elements (nodelists)  
    - getElementsByClassName('class')   
    - getElementsbyTagName('tagName')  ex. h1, li
    - querySelectorAll() - ex li[id]  

  - Traversing   
    - parentNode  
    - previousSibling   
    - nextSibling  
    - firstChild   
    - lastChild  

2. Work with those Elements:

  - Access / update text nodes    
    - nodeValue - lets you access or update contents of text node  

  - Work with HTML Content    
    - textContent - will collect text and ignore any markup (use this one)
    - innerText - should generally avoid because firefox doesnt   support it, it will not show any content hidden by CSS, can be slower
    - innerHTML - better suited to updating entire fragments  
      - Adding Content   
        1. store new content as string in variable
        2. select element whose content you want to replace
        3. set elements innerHTML property to new string
    - DOM Manipulation:   
      - createElement()  
      - createTextNode()  
      - appendChild()
      - removeChild()  

![Dom-manipulation](/images/DOM-manipulation.png)      

  - Access or Update Attribute Values
    - className / id
    - hasAttribute()
    - getAttribute()
    - setAttribute()
    - removeAttribute()



- DOM Queries - methods that find elements in the DOM tree
- Storing elements in a variable really means storing the location of the element(s) within the DOM tree. The properties and methods of that element node work on the variable. It saves the browser from searching the element multiple times. Known as caching
- if a method can return more than one node, it will always return a nodelist
- NodeList - collection of nodes. looks like array and are numbered like arrays. They are type of object called a collection
  - A few notable properties and methods
    - length property 
    - item() method returns a specific node
- Two ways to select element from a node list
  - item() method
  - array syntax (preferred, faster)

Three Techniques for adding HTML and when you should use each one
- document.write() - quick and easy but is rarely advised. used by beginners
- element.innerHTML - is faster when adding things, or removing things, but should not be used to add content that came from a user. this is a security risk
- DOM manipulation - 


Cross-Site Scripting(XSS) Attacks

Defending against cross site scripting  
- validation - only let visitors input the kind of characters they need to when supplying information
- double-check validation
- database may safely contain markup and script from trusted sources
- as data leaves the database, all potentially dangerous characters should be replaced
- only insert content generated by users into certain parts of template file
- dont create dom fragments containing html from untrusted sources


[Back to Table of Contents](https://davees987.github.io/reading-notes)