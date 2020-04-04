# Read 05 Notes

**HTML Book**
- Chapter 5: Images (p94-125)
- Chapter 11: Color (p246-263)
- Chapter 12: Text (p264-299)

### Images

- three rules for creating images
  - save images in right format
  - save images at the right size
  - measure images in pixels
- use JPEG when you have different colors in a picture
- use GIF or PNG when using images with few colors or large areas of same color

Properties to be familiar with
```
<img>
<figure>
<figcaption>
```

### Color

Can specify color in 3 ways: rgb, hex codes, color names

**Terms to know**

- hue - near to the colloquial idea of color
- saturation - refers to the amount of gray in a color. max saturation means no gray, min saturation means it would be mostly gray
- brightness - or "value", refers to how much black is in a color. max brightness means no black in color. min brightness means color would be very dark

![Hue, Saturation, Brightness](/images/hue-saturation-brightness.png)

- opacity - value is number between 0.0 and 1.0, ex. 0.5 = 50%, in CSS this is the 4th property in rgba, known as the alpha value
- lightness - also referred to as luminosity. amount of white or black in a color. 0% = black, 100% = white, 50% = normal

![HSL](/images/HSL.png)

- HSLA 
  - hue expressed as angle from 0-360
  - saturation expressed as percentage
  - lightness expressed as percentage
  - alpha expressed as number between 0.0 and 1.0


### Text

Terms to know

- serif - has extra details on the main strokes of letters. in print its considered easier to read
- sans-serif - has straight ends to letters, more modern, cleaner design, can be easier to read on screen if letters are smaller
- monospace - widths of letters have same lengths, used in code
- cursive - can have joining strokes or handwriting type styles
- fantasy - decorative fonts often used for titles but not long bodies of text
- weight - light, medium, bold, black
- style - normal, italic, oblique
- stretch - condensed, regular, extended
- pseudo-elements - acts like an extra element is in the code
- pseudo-class - 

Properties to be familiar with

- font-family - can specify a list of fonts separated by commas so the browser has options if the user does not have a specified font installed
- font-size
- @font-face - allows a user to download a copy of a font they don't have. make sure licensing is permitted
- font-weight
- font-style
- text-transform - uppercase, lowercase, capitalize
- text-decoration - none, underline, overline, line-through, blink
- line-height - controls the leading
- letter-spacing - controls the kerning
- word-spacing - 
- text-align -
- vertical-align
- text-indent
- text-shadow
- first-letter - known as pseudo-elements
- first-line - known as pseudo-elements
- :link -
- :visited
- :hover
- :active
- :focus

Attribute Selectors

![Attribute Selectors](/images/Attribute-selector.png)

