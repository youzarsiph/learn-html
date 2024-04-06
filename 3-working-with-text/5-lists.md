# Lists

Lists are *everywhere* in life—from your grocery list to the list of steps you follow to get to your home every day.
Lists are *everywhere* on the web, too, and we have three different types to learn about.

## Unordered

Unordered lists are used to mark up lists of items for which the order of the items *doesn't matter*.

```htm
<h1>Unordered Lists</h1>

<ul>
  <li>List Item 1</li>
  <li>List Item 2</li>
  <li>List Item 3</li>
</ul>
```

## Ordered

Ordered lists are lists in which the order of the items *does matter*.
The markup structure is the same as for unordered lists, except that you
have to put the list items in an `<ol>` element, instead of `<ul>`

```htm
<h1>Ordered Lists</h1>

<ol>
  <li>List Item 1</li>
  <li>List Item 2</li>
  <li>List Item 3</li>
</ol>
```

## Description Lists

Description lists *group* terms and descriptions.
Common uses for this element are making a dictionary or showing metadata.
Description lists use a different wrapper than the other list types — `<dl>`;
also each term is wrapped in a `<dt>` (description term) element,
and each description is wrapped in a `<dd>` (description definition) element.
The browser default styles will show description lists with the descriptions *indented* a bit from the terms.

```htm
<h1>Description Lists</h1>

<dl>
  <dt>Data Term 1</dt>
  <dd>Data Term 1 Description</dd>
  <!-- Note that it is allowed to have a single term with multiple descriptions -->
  <dt>Data Term 2</dt>
  <dd>Data Term 2 Description 1</dd>
  <dd>Data Term 2 Description 2</dd>
</dl>
```

This is how you can use lists in HTML using the `<ul>`, `<ol>`, and `<dl>` elements.
Lists can make your content more *organized* and *clear*. 😊
