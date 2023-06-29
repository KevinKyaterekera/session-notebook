# CSS (Cascading Style Sheets)

## Applying CSS to HTML

There are three methods of applying to a html document.<br>

1. Internal (written in the '<head>'-property)
2. Inline (written right after the property, thats supposed to be styled.)
3. External (written in an external document that is linked to the html document).<br>

## Important css concepts:

1. **Inheritance:**

   Elements are inheritate from parents to child elemens. Or some of descendes. Anything that is related to fonts (yout typography, font sizes, text-alignment, line hight or colors and so one) are inherited. So it makes sense to define all of this in the body element, because it will be inherited anyways. And after that you can overwrite these things with more specific selectors.

2. **The Cascade:**

   It means that the browser is reading the css code from top to bottom and applys these styles in that order (without talking about specifity). Even a different command that belongs to the same class would be overwritten by the browser, because of the cascading reading behavior that css has. <br> For example:<br> **\_`.dark-background { `<br>` background-color: black;`<br>`}`** <br>
   would be overwritten by a second command thats targeting the .dark-background-class. Only because it was written below it in the css file.<br> This is very helpful to know when it comes to finding problems and why some styles are not working.

3. **The Box-Model:**

   The default behavior is "content-box". That means that the browser will add padding and margin to your element/box/div. so if you only want your written element to appear in its given size, you have to use this concepts, to make sure, that it wil appear like this.

4. **Specifity:**

   Basically its a little bit involed with the cascade and the "order" of things. But its [how specific](https://www.youtube.com/watch?v=c0kfcP_nD9E&list=PL4-IK0AVhVjP27yZLwW-gkPggRps0CCnP) selectors are in our css.

5. **Creating Layouts**

   Try to avoid Positioning while starting. Better and way more useful are:<br>

   - [Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
   - [Flex-Box](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

   Create a class for the layout and an extra class for the content or typography and so on to avoid conflicts. There are several methodologies. The one that is quit common for beginers is the [BEM-methodologie](https://getbem.com/introduction/). Basically it means to seperate the block from the element and the modifiers. The syntax is like: **"block\_\_element--modifier"**. So if you have like a grid-parent that contains three blocks. <br> You could use:

   - one class for the container
   - one class for the blocks layout and how the layouts working.
   - one class for the individuall styling. if nessassary.

### **Videos**

Have a closer look on [this](https://www.youtube.com/watch?v=JnTPd9G6hoY.)

## Selectors:
