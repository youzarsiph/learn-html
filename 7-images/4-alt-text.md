# Describe your images with alt text 🗣️

The alt attribute lets you write a text that describes your image,
so that people who can't see it can still understand it. For example:

```htm

<img src="images/sky.jpg" alt="A blue sky with white clouds and a rainbow" />
```

The alt text tells us that the image is a sky with a rainbow. 🌈

You need alt text for your images because:

- Some people use screen readers to listen to the web page. Alt text helps them to know what the images are. 👂
- Sometimes the browser can't load the image. Alt text helps the user to know what they are missing. 🕵️‍♂️
- Some people use browsers that only show text. Alt text helps them to know what the images are. 📜
- You want to make your web page more searchable. Search engines can use alt text to match your images with keywords. 🔎
- Some people turn off images to save data or avoid distractions. Alt text helps them to know what the images are. 📱

What you write in your alt attribute depends on why you have the image on your web page.
Think about what the user would lose if they can't see the image:

- If your image is just for decoration, you should write alt="". This tells the screen reader to skip the image. 🎨
- If your image has important information, you should write a brief alt text that explains it.
  Or write the same information in the main text. Don't write the same thing twice. 📝
- If your image is a link, you should write a clear alt text that tells the user where the link goes.
  You can write it inside the `<a>` element or inside the alt attribute. 🔗
- If your image is text, you should write the same text in the alt attribute.
  But you should use CSS instead of images for text. 🆎

The main idea is to make your web page usable even when the images can't be seen.
This makes your web page more accessible and user-friendly. 😊
