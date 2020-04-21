## HTML Text, CSS Introduction, and Basic JavaScript Instructions

### Terms to know 

- structural markup - the element that you can use to describe bot headings and paragraphs
- semantic markup - provides extra info such as where emphasis is placed in a sentence, that something is a quotation, the meaning of acryonyms, etc. They are not intended to affect the structure of your webpage.

```
<h1> headings
<p> paragraphs
<b> bold
<i> italics
<sup> superscript (ex. 4th)
<sub> subscirpt (ex. H2O)
<br /> adding line breaks inside a paragraph
<hr /> horizontal rule (creates horizontal line)

Semantic Markups
<strong></strong> bold
<em></em> italics
<blockquote> used for longer quote that take up an entire paragraph. <p> element is inside
<q> used for shorter quotes
<abbr> abbreviations
<cite> used to indicatewhere the citation is from
<dfn> used to indicate defining instance of a new term
<address> to contain contact details for the author of the page
<ins> & <del> shows content that has been inserted or deleted
<s> strikethrough
```

### CSS 

Using external css
```
<link href="LOCATION OF CSS FILE" type="text/css" rel="stylesheet" />
```

- Block level elements look like they start on new line
- inline elements flow within the text

Example styles: boxes, text, specific

**Terms to know:** 
- rule set
- selector, declaration
- inside the declaration is the property, value

Ruleset:  
.banana {  
      background-color: red;  
}
 
### Box model
- content - text
- Padding - clear area around the content
- border - around the content and padding
- margin - around the border. is transparent

### CSS Selectors

`.class {}` Class Selector    
`#id {}` ID Selector    
`* {}` Universal Selector   
`h1 {}` Type Selector   
`li>a {}` Child Selector (targets any a elements that are childeren of li elements)  
`p a {}` Descendent Selector (targest any a elements inside p elements even if there are other elements nested between)  
`h1 + p {}` Adjacent Sibling Selector (targets the first p element after any h1 element but not other p elements)  
`h1~p {}` General Sibling Selector (if you had two p elements that are siblings of an h1 element, this rule would apply to both)  

![CSS Selectors](/images/cssSelector.jpg)

### How CSS Rules Cascade

- Last Rule
- Specificity
- Important: you can add !important to a property value 
- Note: CSS rules usually appear in a separate document

### JavaScript

code inside a function is encapsulation  

```
document.write('Good Afternoon');
```
`document` : object represents the entire webpage  
`.` :  member operator  
`write()` : method of the document object  that allows new content to be written into the page where the `<script>` element sits  
`Good afternoon` : parameter

Javascript will run whenever it reaches a `<script>` element


- code block - code inside of the curly braces
- statements - inside of code blocks. are individual instructions the computer should follow
- variables - stored bits of information
- variable key word - var
- variable name -  
- ` = ` assignment operator
- variable value - 
- variable types - number, string, boolean

### 6 rules for Naming Variables

1. Name must beghin with letter, dollar sign, or an underscore. Never a number
1. Names can contain letter, number, dollar sign, or underscore. Never a dash or period
1. Can't use keywords or reserved words
1. Names are case sensitive
1. Use names that describes what the variable stores
1. Use camelCase

### Arrays

- array literal - creating array writing it from left to right
- array constructor - 
```
var colors = new Array('white,
                        'black',
                        'custom');
```
- updating third item:
```
colors[2] = 'beige';
```
 
### Loops

To determine which path to take, programmers rely on the following three concepts
- Evaluations - analyze values in your scripts to determine if they match expected results
- Decisions - using result of the script, you can decide which path your script should go
- Loops - perorm the same set of steps repeatedly

2 Components to a decision
- An expression is evaluated which returns a value
- A condition statement says what to do in a given situation


### Comparison Operators

```
== : is equal to
=== : strict equal to
!= : is not equal to
!== : strict not equal to
> : greater than
>= : greater than or equal to
< : less than
<= : less than or equal to
```
- Strict equals will compare two values and data type. Equal will only compare value

### Logical Operators

- Logical operators will let you compare the results of more than one comparison operator


[Back to Table of Contents](https://davees987.github.io/reading-notes)