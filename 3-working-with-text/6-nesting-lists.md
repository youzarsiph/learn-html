# Nesting Lists

When you write a web page, you might want to show some **items** that have other items inside them.
For example, you might want to show the categories of animals, and then the names of the animals in each category.
How do you make your items look like **lists** that have other lists inside them?

You can use HTML, which is the language we use to create web pages, to make your items look like **nested lists**.
HTML has different **elements** that you can use to mark up your lists, like `<ul>` for unordered lists, `<ol>` for ordered lists, and `<li>` for list items.
You have to put your items **inside** these elements, so the browser knows how to **show** them.
To make a nested list, you have to put another list element **inside** a list item element.

```htm
<h1>Nested Lists</h1>

<ol>
  <li>List Item</li>
  <li>
    List Item with more information
    <ul>
      <li>Nested List Item</li>
    </ul>
  </li>
</ol>
```

This is how you can use nested lists in HTML using the `<ol>` and `<ul>` elements. Nested lists can make your content more detailed and clear. 😊
