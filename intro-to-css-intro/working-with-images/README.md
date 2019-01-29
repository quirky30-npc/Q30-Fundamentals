---
description: WDI Fundamentals Unit 4
---

# Working with Images

## Working With Images

Adding images to your website can help it come to life. To add images to your site, use the `img` tag with the **src** attribute. `src` stands for "Source" and tells the `img` tag where to find the image you want to include on your page.

### Breaking Down the Image Tag

The `img` tag alone doesn't do much. It's like putting an `a` element in your code without an `href` attribute. The most important thing to do is to tell the browser what image to show using the `src` attribute.

The `src` attribute for an `img` tag works just like the `href` attribute for a link: It tells a browser where to look for an image.

```markup
<img src="images/cat.jpg">
```

The **image alternate attribute**, or `alt` attribute, is a text description of the image. This text will be displayed if the image doesn't load and is read aloud to users with visual impairments. This description is especially important to include when there's text in an image.

```markup
<img src="http://i.imgur.com/z9gGd0t.jpg" alt="Grumpy cat">
```

The **title attribute** tells search engines what the image is depicting, which helps the page appear in Google Image Search.

```markup
<img src="http://i.imgur.com/z9gGd0t.jpg" alt="grumpy cat" title="grumpy cat">
```

[Let's add an image to a page!](working-with-images-exercise.md)

