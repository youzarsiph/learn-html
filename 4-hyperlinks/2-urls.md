# URLs

A URL, or *Uniform Resource Locator* is a string of text that tells you where something is located on the Web.
For example, My portfolio is located at `https://github.com/youzarsiph`.
URLs use paths to find files. Paths show you where the file you're looking for is stored in the filesystem.
Let's look at an example of a directory structure:

```console
src [The root directory: contains the whole site]
 |
 +--> css [Subfolder: CSS styles]
 |     |
 |     +--> styles.css
 |     +--> defaults.css
 |
 +--> js [Subfolder: JS scripts]
 |     |
 |     +--> index.js
 |     +--> highlight.js
 |
 +--> index.html [Home page]
 +--> about.html [About page]
```

For example:

```htm
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Understanding URLs and Paths</title>

    <!--
      To include a hyperlink inside `index.html` (the top level `index.html`) pointing to `css/styles.css` 
      in the `css subdirectory`, This is done by writing the directory's name,
      then a forward slash, then the name of the file. 
    -->
    <link rel="stylesheet" href="css/styles.css">

    <!--
      To include a hyperlink inside `projects/index.html` pointing to `js/index.js`,
      you'd have to go up a directory level, then back down into the `js` directory.
      To go up a directory, use two dots `..`
     -->
    <script src="../js/index.js"></script>
  </head>

  <body>
    <h1>URLs</h1>
    <p>
      To include a hyperlink inside `index.html` (the top level `index.html`) pointing to `about.html` in the *same directory*,
      you would write the filename that you want to link to, because it's in the same directory as the current file.

      Here is a link to <a href="about.html">**about**</a> page.
    </p>
  </body>
</html>
```

This is how you can use URLs and paths in HTML using the `<link>` and `<script>` elements.
URLs and paths can help you *connect* your web pages and files. 😊
