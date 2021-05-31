# CSS layout

*CSS page layout techniques allow us to take elements contained in a web page and control where they are positioned relative to their default position in normal layout flow, the other elements around them, their parent container, or the main viewport/window.*

*The page layout techniques are*

- Normal flow
- The display property
- Flexbox
- Grid
- Floats
- Positioning
- Table layout
- Multiple-column layout

### Normal flow:

*Normal flow is how the browser lays out HTML pages by default when you do nothing to control page layout*

### The display property

*The main methods of achieving page layout in CSS are all values of the display property. 

This property allows us to change the default way something displays. Everything in normal flow has a value of display, 

used as the default way that elements they are set on behave. 

For example, the fact that paragraphs in English display one below the other is due to the fact that they are styled with display: block.

If you create a link around some text inside a paragraph, that link remains inline with the rest of the text, and doesn’t break onto a new line. 

This is because the <a> element is display: inline by default.

### Flexbox

Flexbox is the short name for the Flexible Box Layout Module, designed to make it easy for us to lay things out in one dimension — either as a row or as a column. 
  
To use flexbox, you apply display: flex to the parent element of the elements you want to lay out; all its direct children then become flex items.

### Grid Layout

While flexbox is designed for one-dimensional layout, Grid Layout is designed for two dimensions — lining things up in rows and columns.

### Floats

Floating an element changes the behavior of that element and the block level elements that follow it in normal flow. 
  
The element is moved to the left or right and removed from normal flow, and the surrounding content floats around the floated item.

### Positioning techniques

Positioning allows you to move an element from where it would be placed when in normal flow to another location. 
  
  Positioning isn’t a method for creating your main page layouts, it is more about managing and fine-tuning the position of specific items on the page.
  
### Table layout

HTML tables are fine for displaying tabular data, but many years ago — before even basic CSS was supported reliably across browsers — web developers used to also use tables for entire web page layouts — putting their headers, footers, different columns, etc.
  
in various table rows and columns. This worked at the time, but it has many problems — table layouts are inflexible, very heavy on markup, difficult to debug, and semantically wrong (e.g., screen reader users have problems navigating table layouts).

### Multi-column layout

The multi-column layout module gives us a way to lay out content in columns, similar to how text flows in a newspaper. 

While reading up and down columns is less useful in a web context as you don’t want to force users to scroll up and down, arranging content into columns can be a useful technique.

