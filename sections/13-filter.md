[<<<Back](12-rules.md) | [Next>>>](14-classes.md)

# Filtering

## Why 'Cascading?'

Cascading refers to the order in which the rule sets apply:

- More specific rules override less specific rules
- Later rules override earlier rules (left to right, top to bottom)
- The `!important` keyword will override other rules
- Non-specified properties may be inherited from the parent element

So if your stylesheet contained the following rule sets:

```css
p {
    color: green;
}

p strong {
    color: red;
}
```

...then the text of your paragraph would be green, but where the strong tag is found in the paragraph, the text would be bold and red. In other words, the more specific styling for the `<strong>` text in your paragraph will override the less specific styling of the paragraph in general. This would occur **regardless of the order these rule sets appear in the stylesheet.**

This rule also applies to how you integrate CSS into your HTML to style your content. For example, if you link to an external stylesheet, and you add inline or internal CSS into your HTML, the inline or internal CSS will override the rules set in the external stylesheet. Similarly, the inline CSS will override the internal CSS.

[<<<Back](12-rules.md) | [Next>>>](14-classes.md)
