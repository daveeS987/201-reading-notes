# Read 08 Notes

**HTML Book**
- Chapter 15: Layout (pg358-404)

## Layout

**Terms to know**

- block-level elements - start on a new line
- inline elements - flow in between surrounding texts
- containing elements - aka parent element, when block level elements sit inside another block-level element, the outside element is refered as containing
- positing schemes
  - normal flow - default behavior, elements appear one after another below each other
  - relative positioning - offsets an element. does not affect position of surrounding elements
  - absolute positioning - position element in relationship to containing element. taken out of normal flow, does not affect position of surrounding elements, it will move as user scroll up and down the page
  - fixed positioning - positions the element in relation to the browser window. Does not move when user scrolls up or down
  - floating elements - element that is out of normal flow and can be positined far right or left. Floated elements become a block-level element around which other content can flow
- Parents of floated elements problem/solution: if containing elements only have floated elements, the browser will treat it as if its 0 pixels tall. solution: 
  ```
  overflow: auto;
  width: 100%;
  ```
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

