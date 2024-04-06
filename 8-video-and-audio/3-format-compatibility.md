# Use Multiple Source Formats To Improve Compatibility 🎥

You might have a problem with the previous example. The video might not play for you,
because different browsers like different video (and audio) formats.
😕 But don't worry, there are ways to fix this problem. 🙌
Mobile browsers may play some formats that desktop browsers don't, and vice versa.
Also, both desktop and mobile browsers may use other software to play some media types that they can't handle by themselves.
This means media support depends partly on what software the user has installed.

```htm
<video controls>
  <source src="sky.mp4" type="video/mp4" />
  <source src="sky.webm" type="video/webm" />
  <p>
    Your browser doesn't support this video. No worries, here is a
    <a href="sky.mp4">link to the video</a> that you can watch. 😊
  </p>
</video>
```

Here we've removed the src attribute from the `<video>` tag, and instead added separate `<source>` elements
that point to different sources. In this case the browser will check the `<source>` elements and play the
first one that it can support. Having WebM and MP4 sources should cover most platforms and browsers these days.

Each `<source>` element also has a type attribute. This is optional, but it is recommended that you include it.
The type attribute tells the browser the MIME type of the file in the `<source>`, and browsers can use the type to
skip videos they don't know how to play. If type isn't included, browsers will load and try to play each file until
they find one that works, which obviously takes time and is a waste of resources.
