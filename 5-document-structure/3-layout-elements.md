# HTML Layout Elements

It's good to *know* the overall meaning of all the HTML sectioning elements in detail
— this is something you'll *learn* gradually as you start to get more experience with web development.
For now, these are the main definitions that you should *remember*:

- `<main>` is for content *special* to this page.
  Use `<main>` only once per page, and put it directly inside `<body>`.
  Ideally this shouldn't be nested within other elements.
- `<article>` wraps a block of related content that *stands* on its own without the rest of the page.
- `<section>` is similar to `<article>`, but it is more for *grouping* together a single
  part of the page that has one single piece of functionality.
  It's a good idea to start each section with a heading.
- `<aside>` contains content that is not *closely* related to the main content but can
  give more information *loosely* related to it.
- `<header>` shows a group of *introductory* content.
  If it is a child of `<body>` it defines the *global* header of a webpage,
  but if it's a child of an `<article>` or `<section>` it defines a *specific* header for that section
- `<nav>` contains the main *navigation* functionality for the page.
  *Other* links, etc., would not go in the navigation.
- `<footer>` shows a group of *final* content for a page.

This is how you can use HTML layout elements using the `<main>`, `<article>`, `<section>`, `<aside>`, `<header>`, `<nav>`, and `<footer>` elements.
HTML layout elements can make your web page more *organized* and *clear*. 😊
