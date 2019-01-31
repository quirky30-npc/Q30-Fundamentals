# Column Layout

## Column Layout

{% embed url="http://fast.wistia.net/embed/iframe/fk9027biok?seo=false&videoFoam=true" %}

### Reminder: Use IDs Sparingly in CSS

You are technically allowed to use CSS IDs, but these are almost never used by professional developers because of their specificity. CSS classes give you the ability to reuse styles, whereas any style specified with an ID can only be used once. Also, IDs can override classes, making a code base more difficult to maintain as it gets larger.

Overall, using classes in your CSS will help with the scalability of your design and your ability to write cleaner code.

Only use IDs in your CSS if you're 100% positive that the styles are for one unique element and you will not need to reuse the styles at any point.

### Reminder: Using IDs in JavaScript

When writing JavaScript, IDs are useful for accessing and altering different elements on your page. This process is called DOM manipulation. You'll learn more about manipulating the DOM once we dive deeper into JavaScript. For now, remember to style and select using classes when writing your CSS!

#### Checkpoint

* What does the `<aside>` tag do?
* How would you go about creating three columns on your web page?

[Let's practice building columns!](column-layout-exercise.md)

