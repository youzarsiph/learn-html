# Figures and Caption 🖼️

Captions are great for explaining what your images are about. They can make your web pages more informative and interesting.
But how do you add captions to your images? 🤔

One way is to do something like this:

```htm
<div class="figure">
  <img
    width="400"
    height="300" 
    src="images/sky.jpg"
    alt="A blue sky with white clouds and a rainbow"
  />

  <p>A beautiful sky after a rain shower.</p>
</div>
```

This works, but it has a problem. There is nothing that connects the image and the caption in a meaningful way.
This can confuse screen readers that help people who can't see the images.
For example, if you have 50 images and captions on your page, how do you know which caption belongs to which image? 😕

A better way is to use the HTML `<figure>` and `<figcaption>` elements.
These elements are made for this purpose: to group the image and the caption together,
and to tell the browsers and screen readers that they are related. You can rewrite the above example like this:

```htm
<figure>
  <img
    width="400"
    height="300" 
    src="images/sky.jpg"
    alt="A blue sky with white clouds and a rainbow"
  />

  <figcaption>
    A beautiful sky after a rain shower.
  </figcaption>
</figure>
```

The `<figcaption>` element shows that the caption describes the content of the `<figure>` element.

Note: Captions and alt text are different things. Captions help everyone understand the image, while alt text replaces the image when it is not available. So, captions and alt text should not say the same thing, because they both show up when the image is gone. Try turning off images in your browser and see how it looks. 👀

A figure can be more than an image. It can be anything that:

- Shows your message in a clear and concise way.
- Can fit in different places on your page.
- Gives important information that supports your main text.

A figure can be multiple images, a code snippet, audio, video, equations, a table, or something else. 🙌
