# Languages

You can (and really should) *select* the language of your page.
This can be done by adding the lang attribute to the *first* HTML tag.

```htm
<!DOCTYPE html>
<html lang="en">
  ...
</html>
```

This is *handy* in many ways. Your HTML document will be *favored* by search engines if its language is selected
(making it *appear* right in language-specific results, for example),
and it is *helpful* to people with visual disabilities using screen readers.

You can also make parts of your document use different languages.

```htm
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Languages</title>
  </head>

  <body>
    <h1>Subsection language</h1>
    <p lang="ar">مرحبا</p>
  </body>
</html>
```

This is how you can *pick* languages in HTML using the lang attribute. Languages can make your page more *welcoming* and *diverse*. 😎
