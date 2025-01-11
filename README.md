#Demonstration of the CSS selectors' specificity calculation

Specificity is the algorithm used by browsers to determine the CSS declaration that is the most relevant to an element, which in turn, determines the property value to apply to the element. 
The specificity algorithm calculates the weight of a CSS selector to determine which rule from competing CSS declarations gets applied to an element.

##weight of ID elements

Adds 1 point to the first, most significant place
`#id_of_element {}`
**1-0-0**

##Weight of class

Add 1 point to the second place
`.myclass {}`
**0-1-0**

##Weight of type

Adds 1 point to the least significant place
`p {}`
**0-0-1**
