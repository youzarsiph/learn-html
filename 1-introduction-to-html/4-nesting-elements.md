# Nesting Elements

Nesting elements means putting one element inside another element, like a *Russian doll*. 🎎
You have to be *attentive* and follow the rules of nesting, otherwise your web page will not look the way you want it to. 😊
The rules of nesting are:

- Opening tag: This is like a *badge* that tells the Web browser what kind of element it is.
  It has the element name inside angle brackets, like this: `<element>`.
  This opening tag marks the *start* of the element, or when it begins to work.
- Content: This is what the element *contains*, such as text, images, or other elements.
- Closing tag: This is like another *badge* that tells the Web browser that the element is *finished*.
  It has the same element name inside angle brackets, but with a slash before it, like this: `</element>`.
  This closing tag marks the *end* of the element, or when it stops working.

Let's take a look at an example of nesting elements:

```htm
<p>
  HTML is <strong>easy</strong> to learn.
</p>
```

This is right, because the `<strong>` element is *totally* inside the `<p>` element.
The `<strong>` element makes the text inside it **bold**, so the word "easy" will appear in **bold** on the web page. 💪

But this is wrong:

```htm
<p>
  HTML is <strong>easy to learn.
</p>
</strong>
```

This is wrong, because the closing tag of the `<strong>` element is *outside* the closing tag of the `<p>` element.
This will *confuse* the Web browser and cause errors in showing the content. ❌

Nesting elements is a common and helpful technique in HTML,
as it lets you create *fancy* and *rich* web pages with different styles and features.
But you have to be careful and follow the rules.
