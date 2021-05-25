[<<<Back](03-basic.md) | [Next>>>](05-p_and_h.md)

# Tags and Elements

Tags and elements are the structuring components of html webpages.

**Elements** identify the different parts of a page, such as paragraphs, headings, titles, body text, images and more. Elements are demarcated by tags which enclose the content of an element (ex. `<head>` and `</head>` are tags that denote the head element of your page).

**Tags** demarcate elements in one of two ways. As with the paragraph element below, an element can have an opening and a closing tag, with content in between.

```html
<p>This is a paragraph.</p>

<p>
    This is also a paragraph.
</p>
```

Elements which have an opening and closing tag can have other elements inside them. Inside the paragraph element below is a strong element, which emphasizes the included text by making it bold.

```html
<p>
    When I came home from school, I saw he had <strong>stolen</strong> my chocolate pudding.
</p>
```

Some elements, such as the image element, have self-closing tags or **void tags**: these do not contain displayed text or other nested elements.

```html
<img src="image.jpeg" />
```

These elements don't require a separate closing tag. Closing tags aren't needed because you wouldn't add content inside these elements. For example, it doesn't make sense to add any additional content inside an image.

In addition to the 'src' attribute, which tells the browser where to find the image file to display, `<img>` elements should also have an 'alt' attribute with a brief description of the image (alternative text).

```html
<img alt="This is an image" src="image.jpeg" />
```

Alternative text is crucial to make your website accessible: it provides a description of the image for users who are using alternative browser technology (such as audio-based screen readers).  

If you look back at the basic template in your `index.html` file, you'll see that the main sections of your file have opening and closing tags. Each of these main elements will eventually enclose several nested elements to structure the content of our website.

[<<<Back](03-basic.md) | [Next>>>](05-p_and_h.md)
