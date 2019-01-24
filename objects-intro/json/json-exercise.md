# Exercise

**WDI Fundamentals Unit 10**

## ![Your Turn](../../.gitbook/assets/exercise.png) Your Turn

### JSON Exercise

#### Instructions

1. Write the code to perform the actions listed below in the **"JavaScript"** panel in the JS Bin editor. 
2. If you don't see the JS Bin below, please refresh the page.
3. Click "Run" to run the code in the "Console" panel.
4. After clicking "Run", to check variable values, type the variable name in the **"Console"** panel on the right and hit enter/return.

[JS Bin on jsbin.com](http://jsbin.com/ruqelev/embed?js,console)

#### Let's get started!

1. JSONLint is a helpful online tool for checking JSON syntax and ensuring that it is valid. Take a look at the object below. Copy the entire object. Then go to [JSONLint](http://jsonlint.com/) and paste it into the validator. Does it pass the test?

   ```javascript
    {
      "someKey": "someValue",
      "innerArray": [
        "alpha",
        "beta",
        "gamma",
        "delta"
      ]
    }
   ```

2. The following line is valid JavaScript, but the object is not written in valid JSON syntax. Use JSONLint to validate the above object; then, update the object to use the correct JSON syntax so it passes the validator.

   ```javascript
    {
        name: 'Eddie Vedder', 
        age: 49
    }
   ```

3. Take a look at the `grungeAlbums` object provided in the JS Bin editor.
   * In the "JavaScript" panel in JS Bin, use the `JSON.stringify()` method to turn the `grungeAlbums` JavaScript object into a JSON string, and store it in a variable `grungeAlbumsJSON`. 
   * Then, use the `JSON.parse()` method to convert `grungeAlbumsJSON` back into a JavaScript object and store it in the variable `grungeAlbumsObject`. 
   * Log each variable to the console to compare, and also compare to the original object. You'll need to hit the "Run" button in the "Console" panel to see the output from the `console.log()` statements.
4. Now loop through each album in `grungeAlbumsObject`, and use a `console.log()` statement to print out the album name, artist, and units sold. Each album should be formatted as follows:

   ```text
    Album: Album name
    Artist: Artist name
    Units sold: 31234
   ```

   * Hit the "Run" button in the console and you should see the information for each album displayed in the console.

     > Hint: you'll want to use a `for` loop for this step.

> _Stuck? Check out the_ [_solutions_](../../exercise-solutions.md#json) _for assistance._

Feeling confident? [Test yourself.](../objects-quiz.md)

