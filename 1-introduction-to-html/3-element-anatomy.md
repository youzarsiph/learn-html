# Element Anatomy

An element is made up of three parts:

- Opening tag: This is like a *name tag* that tells the Web browser what kind of element it is.
  It has the element name inside angle brackets, like this: `<element>`.
  This opening tag marks the *start* of the element, or when it begins to work.
- Content: This is what the element *contains*, such as text, images, or other elements.
- Closing tag: This is like another *name tag* that tells the Web browser that the element is *finished*.
  It has the same element name inside angle brackets, but with a slash before it, like this: `</element>`.
  This closing tag marks the *end* of the element, or when it stops working.

Let's take a look at the paragraph element:

```htm
Element <--+
           |
+----------------------+
<p> Element content </p>
+-+ +-------------+ +--+
 |         |         |
 |         |         +--> Closing tag
 |         +--> Content
 +--> Opening tag
```

The paragraph element is used to make *chunks* of text on a web page. It has the name `p` inside the tags, and the content is the text you want to show. 📝
