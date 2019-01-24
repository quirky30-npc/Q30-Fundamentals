# Exercise

**WDI Fundamentals Unit 10**

## ![Your Turn](../../.gitbook/assets/exercise.png) Your Turn

### Creating Objects Exercise

#### Instructions

1. Write the code to perform the actions listed below in the **"JavaScript"** panel in the JS Bin editor. 
2. If you don't see the JS Bin below, please refresh the page.
3. Click "Run" to run the code in the "Console" panel.
4. After clicking "Run", to check variable values, type the variable name in the **"Console"** panel on the right and hit enter/return.

[JS Bin on jsbin.com](http://jsbin.com/lufunit/1/embed?js,console)

#### Let's get started!

Our goal for this exercise is to create a contact book that allows us to store contact info \(including first name, last name, phone, and email address\) and list our contacts.

1. Create an array called `contacts`. The `contacts` array should contain three objects, one for each contact stored in our book. Here's the contact information for each person:

| `firstName` | `lastName` | `phone` | `email` |
| :--- | :---: | :--- | :---: |
| `"John"` | `"Doe"` | `"(512) 355-0453"` | `"johndoe@email.com"` |
| `"Jane"` | `"Doe"` | `"(312) 641-2203"` | `"janedoe@email.com"` |
| `"Suzie"` | `"Smith"` | `"(415) 604-4219"` | `"suziesmith@email.com"` |

> Hint: Here's the syntax for creating an array that contains objects:
>
> ```javascript
> var garden = [
>    {
>        color: 'red',
>        flower: 'rose',
>        petals: 20
>    },
>    {
>        color: 'blue',
>        flower: 'violet',
>        petals: 6
>    }
> ];
> ```

2. Now let's create a `listContacts` function to list our contacts. This function should loop through the `contacts` array and log the first and last name for each contact to the console, e.g. `"John Doe"`. Then call the `listContacts` function.

> Hint \#1: The syntax for a loop looks like this:
>
> ```javascript
> for (var i = 0; i < arrayName.length; i++) {
>    // code to execute 
> }
> ```
>
> Hint \#2: From within the loop, we can use `i` as an index to find the current item we are on. If we wanted to log a contact's email from within the loop, it would look like this:
>
> ```javascript
> for (var i = 0; i < arrayName.length; i++) {
>    console.log(contacts[i].email); 
> }
> ```
>
> _Stuck? Check out the_ [_solutions_](../../exercise-solutions.md#creating-objects) _for assistance._

[Ready to move on? Here's the next lesson.](../methods/)

