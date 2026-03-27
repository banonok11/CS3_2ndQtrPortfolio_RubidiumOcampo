## Step 1: 
**Guided Question: What changed compared to the default static positioning? Try to give different values to top and left or you can change it to bottom, right.**


## Step 2:
**Guided Question: What happens when you scroll the page? Why does the footer behave differently from position relative?**

## Step 3:
**Guided Question: What is the effect of position: absolute on an element? How is it different from fixed?**

## Step 4:
**Guided Question: Why does the notice appear on top of the content? What happens if you swap the z‑index values?**

# Reflection
a. Could you summarize the differences between the CSS position values (static, relative, absolute, fixed)?
- Static - This is the default position of the element, meaning it is positioned according to the normal document flow, meaning the default way elements are displayed on an HTML page.
- Relative - When using this css position value, the element will be displayed RELATIVE to its normal position meaning you can shift it left, right, top and bottom.
- Absolute - This may seem similar to relative, but it is different. It is removed from the normal document flow and positioned relative to its nearest ancestor, and it no longer affects its parents' height.
- Fixed - This one is simple, the element will now be positioned relative to the viewport.

b. How does absolute positioning depend on its parent element?
- Absolute positioning uses its ancestor as its reference point, and that is why the absolute positioning depends on the parent element.

c. How do you differentiate sticky from fixed (you can research on sticky)?
- Sticky uses scroll position while fixed does not. This means that when you use sticky on an element, that element will behave like a relative element until it reaches a specific scroll position. The css sticky position value only sticks within its entire parent container, not the entire viewport.

d. If you were designing a webpage for a school event, how might you use positioning to highlight important information? Please give concrete examples
