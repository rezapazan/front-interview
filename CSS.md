# CSS Interview Questions

**1. What is the Box model in CSS? Which CSS properties are a part of it?**

A rectangle box is wrapped around every HTML element. The box model is used to determine the height and width of the rectangular box. The CSS Box consists of Width and height (or in the absence of that, default values and the content inside), padding, borders, margin.

- content
- padding
- border
- margin

**2. Difference between CSS grid vs flexbox?**
CSS Grid Layout is a two-dimensional system, meaning it can handle both columns and rows. Grid layout is intended for larger-scale layouts which aren’t linear in design.
Flexbox is largely a one-dimensional system (either in a column or a row). Flexbox layout is most appropriate to the components of an application.

**3. Explain CSS position property?**

- **Absolute**: To place an element exactly where you want to place it. absolute position is actually set relative to the element's parent. if no parent is available then the relative place to the page itself (it will default all the way back up to the element).
- **Relative**: "Relative to itself". Setting position: relative; on an element and no other positioning attributes, it will no effect on its positioning. It allows the use of z-index on the element and it limits the scope of absolutely positioned child elements. Any child element will be absolutely positioned within that block.
- **Fixed**: The element is positioned relative to the viewport or the browser window itself. viewport doesn't change if you scroll and hence the fixed element will stay right in the same position.
- **Static**: Static default for every single page element. The only reason you would ever set an element to position: static is to forcefully remove some positioning that got applied to an element outside of your control.
- **Sticky**: Sticky positioning is a hybrid of relative and fixed positioning. The element is treated as relative positioned until it crosses a specified threshold, at which point it is treated as fixed positioned.

**4. What is a z-index, how does it function?**
z-index is used for specifying the vertical stacking of the overlapping elements that occur at the time of its positioning. It specifies the vertical stack order of the elements positioned that helps to define how the display of elements should happen in cases of overlapping.
The default value of this property is 0 and can be either positive or negative.

**5. Hamburger Menu Scenario**
Consider you are tasked with creating a hamburger menu using just pure CSS. What is your approach?

**6. What is a CSS Preprocessor? What are Sass, Less, and Stylus? Why do people use them?**
A CSS Preprocessor is a tool used to extend the basic functionality of default vanilla CSS through its own scripting language. It helps us to use complex logical syntax like – variables, functions, mixins, code nesting, and inheritance to name a few, supercharging your vanilla CSS.

**7. What UI Libraries / CSS frameworks are you familiar with?**

- Material UI
- Shadcn
- Next UI
- Headless UI
- Tailwind CSS
- etc.
