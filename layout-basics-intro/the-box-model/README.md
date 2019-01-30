---
description: WDI Fundamentals Unit 5
---

# The Box Model

## The Box Model

Now that we understand how to differentiate between `inline` and `block` elements, it's time to take a look at the CSS Box Model. Every HTML element on a webpage is in a box, therefore, every element has:

* The **content** within the box
* The **padding**, or the area outside of the content
* The **border**, or the line between `padding` and `margin`
* The **margin**, or the area outside the `border` that separates the element from other elements on the page

### More on the Box Model

In the video above, we mainly discussed how to set shorthand properties for padding values that are the same. However, there will be many cases where you'll want to set properties that have different values. Here's how your syntax would look like for different padding values for each side of an HTML element.

```markup
div {
    background: #c0dec5;
    padding: 30px 20px 0 15px;
}
```

This means that the top `padding` will be `30px`, the right `padding` is `20px`, the bottom `padding` is `0`, and the left `padding` is `15px`. This diagram will help you visualize how this works:

![](../../.gitbook/assets/trouble%20%281%29.png).

There will also be instances when you want to have the same `padding` or `margin` value for your left and right margins, and another value for your top and bottom margins. For example, to set your _top and bottom_ `padding` to `0` and your _left and right_ `padding` to `20px`, you would set it up like so:

```markup
div {
    padding: 0 20px;
}
```

### Checkpoint

* How would you set a solid `border` that is red and has a width of `4px` for a `p` element?
* How would you center a wrapper for your website?

### Further Reading

* Learn more about CSS shorthand on the [Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/Web/CSS/Shorthand_properties)

[Ready to try coding it yourself?](the-box-model-exercise.md)

