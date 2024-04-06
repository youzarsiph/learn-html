# Image Titles

You know how you can add title attributes to links, to show more details when you hover over them? You can do the same thing with images, like this:

```htm
<img 
  src="images/sky.jpg"
  width="300" height="200"
  title="This is a beautiful sky"
  alt="A blue sky with white clouds and a rainbow"
/>
```

This will show a tooltip with the title text when you move your mouse over the image, just like with links. 🖱️

But this is not a good idea — title attributes have some problems with accessibility,
which means that they are not friendly to all users. For example, screen readers may not read them,
and most browsers won't show them if you are using a keyboard or a touch screen. 😢

It is better to write the extra info in the main text of your article, where everyone can see it.
Don't hide it in the image. 🙈
