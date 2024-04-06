# Adding custom icons

You can *jazz up* your site by adding custom icons to your metadata.
These icons will *appear* in different spots depending on the browser.
The most common one of these is the favicon
(a *quick* way of saying "favorites icon", because it shows up in the "favorites" or "bookmarks" lists in browsers). You might see (depending on the browser) favicons in the browser tab of each open page,
and next to bookmarked pages in the bookmarks panel.

You can add a favicon to your page by:

- Saving it in the same folder as the site's main page, saved in .ico format
  (most browsers also like favicons in other formats like .gif or .png)
- Adding this line to your HTML's `<head>` section to link to it

```htm
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Adding custom icons to your site.</title>
    <!-- Link to the icon -->
    <link rel="icon" href="favicon.ico" type="image/x-icon" />
  </head>
</html>
```

This is how you can *slip* custom icons into your HTML document using the `<link>` element.
Custom icons can make your site more *fun* and *catchy*. 😎
