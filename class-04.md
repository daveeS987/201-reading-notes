# Read 04 Notes

**HTML Book**
- Chapter 4: Links (pg74-93)
- Chapter 15: Layout (pg358-404)

**JS Book**
- Chapter 3: Functions, Methods, Objects (pg86-99)
- Article: 6 Reasons for Pair Programming


## Links

To other sites, use absolute url
```
<a href="https://www.github.com">GitHub</a>
```

To other pages on same site, use relative url
```
<a href="index.html">Home</a>
```

![Relative Links](/images/relativeLinks.png)

Email Links
```
<a href="mailto:davee@example.org">Email Davee</a>
```

Opening Links in a new Window, use target=_blank
```
<a href="http://www.example.com" target="_blank">Example</a>
```

Linking to Parts of the same page: use ID attributes with #  
```
<a href="#id attribute">Specific Part of Webpage</a>
```

Link to specific part of page of another website
```
<a href="http://www.example.com/#SpecificID">Link</a>
```

## Layout

**Terms to know**

- block-level elements - start on a new line
- inline elements - flow in between surrounding texts
- containing elements - aka parent element, when block level elements sit inside another block-level element, the outside element is refered as containing
- positing schemes
  - normal flow - default behavior, elements appear one after another below each other
  - relative positioning - shifts an element. does not affect position of surrounding elements
  - absolute positioning - position element in relationship to containing element. taken out of normal flow, does not affect position of surrounding elements, it will move as user scroll up and down the page
  - fixed positioning - positions the element in relation to the browser window. Does not move when user scrolls up or down
  - floating elements - element that is out of normal flow and can be positined far right or left. Floated elements become a block-level element around which other content can flow
- box offset- tells browsers how far from top, bottom, left, or right to position the box
- z-index - property that allows you to control which box appears on top
- fixed width layout - does not change when user changes size of browser window
- liquid layout - will change size depending on size of browser window
- 960 pixel grid - widely used by web designers
- 960.gs css framework

**Properties to be familiar with**

- position: static;
- position: relative;
- position: absolute;
- position: fixed;
- z-index: (higher the number, the closer it is to the front);
- float: 
- clear: (allows you to say no element should touch the left or right hand side of a box);
- width:
- overflow: auto;

Notes

- Web Designers often try to create pages of around 960-1000px wide
- The top 570-600px of the site is commonly used for the most relavent or most important info to the user


### Functions

- function - series of statements that have been grouped together to perform a specific task
- expressions - produce a value
- anonymous function - function with no names
- function expression - uses anonymous function or no name
- function declaration - also known as named functions
- immediately invoked function expressions(IIFE) - are executed once the interpretor comes accros them. Used when code only needs to be run once. can prevent conflicts between two scripts that might use same variable name
- local variables - function level variable with local scope or function level scope. variables inside a function
- global variables - variable outside a function. has global scope. can be used anywhere in a script


### 6 Reasons for Pair Programming

- Greater Efficiency
- Engaged collaboration
- Learning from fellow Students
- Social Skills
- Job Interview Readiness
- Work Environment Readiness

Fundamental skills that help anyone learn a new language
- listening - hearing and interpreting vocabulary, listen to guidance of other coders
- speaking - using correct words to communicate an idea, coders explain out loud what code should do
- reading - understand written language, for coders that means reading other people code
- writing - actually write code


[Back to Table of Contents](https://davees987.github.io/reading-notes)
