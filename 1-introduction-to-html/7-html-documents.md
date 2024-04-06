# Anatomy of an HTML document

You can't make a web page with just one element.
You need to put many elements together to create a whole HTML document.

```htm
               --+
<!DOCTYPE html>  +--> Doc Type: HTML version
               --+
<html>                                              --+
  <head>                  --+                         |
    <meta charset="UTF-8">  |                         |
                            |                         |
    <title>                 +--> Head: Meta data      |
      My Page Title         |                         |
    </title>                |                         |
  </head>                 --+                         +--> Root Element 
                                                      |
  <body>                  --+                         |
    <p>                     |                         |
      My page               +--> Body: Page content   |
    </p>                    |                         |
  </body>                 --+                         |
</html>                                             --+
```

Here we have:

1. `<!DOCTYPE html>`: the doctype is a special code that tells the Web browser
  what version of HTML you are using. It has to be the first thing in your document.
2. `<html></html>`: The `<html>` element. This element wraps all the content on the page.
  It is the main or root element of your document.
3. `<head></head>`: The `<head>` element. This element holds everything you want to add to the HTML page,
  **that isn't the content** the page will show to viewers. This includes things like keywords and a page
  summary for search engines, CSS to make your content look nice, character set declarations to avoid strange symbols, and more.
4. `<body></body>`: The `<body>` element. This contains all the content that appears on the page,
  such as text, images, videos, games, music, or anything else.
