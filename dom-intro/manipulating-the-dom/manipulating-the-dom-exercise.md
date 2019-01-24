# Exercise

**WDI Fundamentals Unit 11**

## ![Your Turn](../../.gitbook/assets/exercise%20%284%29.png) Your Turn

### Manipulating the DOM Exercise

#### Instructions

Make sure that you read the instructions carefully, as the instructions are a little different from past exercises.

1. Write the code to perform the actions listed below in the **"JavaScript"** panel in the JS Bin editor. 
2. If you don't see the JS Bin below, please refresh the page.
3. Make sure that the "Auto-run JS" checkbox is checked in the "Output" panel.

[Abstract Art on jsbin.com](http://jsbin.com/novoki/embed?html,css,js,output)

#### Let's get started!

In this challenge, we'll be using the `document` object to create some abstract art. We'll be creating three elements of different dimensions and colors and then adding them to the DOM.

Are you ready?

1. Create a for loop. For the `for` loop, `i` should have an initial value of `1` and the loop should run _three_ times. Each time the loop runs, create a div element using the `createElement();` method and store it in a variable `boxElement`.
2. Alright! Next let's add some styles for each `div`. In the CSS tab we've defined some styles for you to use. Each time the `for` loop runs, we want to add a class to the current `boxElement` using the `className` property. This will apply the styles in our CSS that are associated with that class.
   * The class name for the first box should be `box-1`.
   * The class name for the second box should be `box-2`.
   * The class name for the third box should be `box-3`.

     > Hint: For the class name, we can use string concatenation to add the number to 'box-'. This will look like the following:
     >
     > `'box-' + i;`
3. Also within the `for` loop, use the `appendChild()` method to append each `boxElement` to the body.

After the third step, you should see the abstract art displayed in the "Output" panel. If you don't see anything, make sure the "Auto-run JS" checkbox is checked.

> _Stuck? Check out the_ [_solutions_](../../exercise-solutions.md#manipulating-the-dom) _to see what you can do._

[Next let's dive into events.](../events/).

