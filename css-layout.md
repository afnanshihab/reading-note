
***FIRST OF ALL :***

This article show cases what CSS is and how it is integrated with HTML for design purposes.

## Layout

Containing Elements If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element. 



* Elements behave differently though, block elements always start on a new line even if the content is just a dot, while inline elements flow between surrounding text, or in other words, everything that flows like a text will surround that element.

## Positions

**There are five different position values:**

![position](https://cdn.educba.com/academy/wp-content/uploads/2019/12/CSS-Position.jpg)

1. static

2. relative

3. fixed

4. absolute

5. sticky


* If the Elements they do not get positioned using CSS... they will flow normally in the same order they were marked up, however you can always alter that. There are other two known ways or modes of positioning which are relative and absolute positioning. **Absolutely positioned** elements get removed from the normal flow entirely, and get positioned relative to the relatively positioned parent, on the other hand, **relatively positioned** elements get positioned relative to their original position in the normal flow and other elements stay in their places. For the absolutely positioned elements, there is a property called the z-index and it is used to alter the stacking of elements when they overlap.

* You can also make the element fixed, so even if you scroll, the element will stay in its place, another one is the sticky position, which is somehow similar to fixed positioning, but the difference is that the element moves or scrolls relative to its container.

* You can also position elements by making them float, either to the right or the left, and once you float an elements, text will wrap around it just like water, but be careful, since if you float all child elements in a container, the container will close up to height zero and will cause the elements to overflow or hang in there in the middle of nowhere.

***All of these methods for positioning allow you to create layouts of various types and shapes, and among the most popular ones are fixed width layouts, liquid layouts and layouts that are based on grids.***

![](https://cdn.educba.com/academy/wp-content/uploads/2019/12/CSS-Position-eg5.png)

### ***SO,,,***
CSS page layout techniques allow us to take elements contained in a web page and control where they are positioned relative to their default position in normal layout flow, the other elements around them, their parent container, or the main viewport/window. The page layout techniques we’ll be covering in more detail in this module are

1. Normal flow
2. The display property
3. flexbox
4. Grid
5. Floats
6. Positioning
7. Table layout
8. Multiple-column layout



![](https://res.cloudinary.com/practicaldev/image/fetch/s--A-2MK0bn--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://ishadeed.com/assets/grid-flex/grid-vs-flexbox-1.png)
--------------------------


## Secreen & Pages
**Screen Sizes**    : Different visitors to your site will have different sized screens that show different amounts of information, so your design needs to be able to work on a range of different sized screens.

**Screen Resolution**   :  Resolution refers to the number of dots a screen shows per inch. Some devices have a higher resolution than desktop computers and most operating systems allow users to adjust the resolution of their screens.

**Page Sizes **   :Because screen sizes and display resolutions vary so much, web designers often try to create pages of around 960-1000 pixels wide.

**Fixed Width**   : Layouts Fixed width layout designs do not change size as the user increases or decreases the size of their browser window. Measurements tend to be given in pixels.

**Liquid Layouts**   : Liquid layout designs stretch and contract as the user increases or decreases the size of their browser window. They tend to use percentages.