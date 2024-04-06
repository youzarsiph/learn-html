# Applying CSS and Javascript to HTML

Most websites you'll see today will use CSS to make them look *awesome*,
and JavaScript to add *cool* features, such as video players, maps, games, and more.
These are usually added to a web page using the `<link>` element and the `<script>` element, respectively.

The `<link>` element should always be inside the head of your document.
This needs two attributes, `rel="stylesheet"`, which tells the browser that it is the document's *style guide*, and `href`, which has the location of the *style file*.

The `<script>` element should also be in the head, and should have a `src` attribute with the location of the *JavaScript* you want to use, and `defer`, which basically tells the browser to load the JavaScript *later*.
after the page has finished reading the HTML.

```htm
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Applying CSS and Javascript to HTML</title>
    <!-- Link CSS -->
    <link rel="stylesheet" href="my-css-file.css" />
    <!-- Link Javascript -->
    <script src="my-js-file.js" defer></script>
  </head>
</html>
```

This is how you can apply CSS and Javascript to your HTML document using the `<link>` and `<script>` elements.
CSS and Javascript can make your web page more *pretty* and *fun*. 😎
