# Exercise

**WDI Fundamentals Unit 11**

## ![Your Turn](../../.gitbook/assets/exercise%20%281%29.png) Your Turn

### Events Exercise

#### Instructions

1. Write the code to perform the actions listed below in the **"JavaScript"** panel in the JS Bin editor. 
2. If you don't see the JS Bin below, please refresh the page.
3. Make sure that the "Auto-run JS" checkbox is checked in the "Output" panel.

[JS Bin on jsbin.com](http://jsbin.com/xozufo/embed?html,js,output)

#### Let's get started!

In this challenge, we'll utilize the `document` object and events to create a todo list. Users should be able to enter new todo items in an input and see them displayed on the page.

Before you get started, take a look at the starter code that has been provided in the "HTML" Panel in JS Bin. You'll need to reference the HTML for the steps below.

1. First create a function called `addItem`. For now it should be empty.
2. Add a `click` event handler to the button. When the button is clicked, run the `addItem` function.
3. Alright, now within the `addItem` function we need to find out what the user entered into the input field. We'll be using a new property - the `value` property - to find out what the user entered into the input. The syntax for using this property looks like this:

   ```javascript
    document.getElementsByTagName('findTheRightElement')[0].value;
   ```

   * Get the user's todo item from the `input` element and store it in a variable `newItemText`.

     > Hint: Here's how we can select the input field:
     >
     > ```javascript
     > document.getElementsByTagName('input')[0]
     > ```

4. Now we want to add the new list item to the `ul` with the id `todo-list`. Remember, in order to add a new element to the page, there are a few steps we will have to take:
   * Use the `createElement()` method to create a list item element and store it in the variable `newItem`.
   * Add content to this new list item using the `innerHTML` property.
   * Use the `appendChild()` method to append this element to the unordered list.
5. Test things out! Enter a task, click the button in the "Output" panel, and make sure that your task is getting added to the todo list.

> _Stuck? Check out the_ [_solutions_](../../exercise-solutions.md#manipulating-the-dom) _to see what you can do._

[Ready to test yourself?](../dom-quiz.md).

