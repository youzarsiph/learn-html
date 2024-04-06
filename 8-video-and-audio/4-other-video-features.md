# Other Video Features 🎥

You can do more than just showing a video on your webpages.
You can also use some HTML features to customize your video.
😍 Here are some of the features you can use:

- `width` and `height`
  You can change the video size with these attributes or with CSS.
  In both cases, videos keep their original width-height ratio — this is called the aspect ratio.
  If you change the aspect ratio, the video will stretch to fill the space horizontally,
  and the empty space will have a solid background color by default.

- `autoplay`
  Makes the video (or audio) start playing as soon as the page loads.
  You should avoid using this feature on your sites, because users can find it very annoying. 😠

- `loop`
  Makes the video (or audio) play again and again when it ends.
  This can also be annoying, so use it only if you really need to.

- `muted`
  Makes the video (or audio) play without any sound by default. 🔇

- `poster`
  The URL of an image that will show before the video plays.
  You can use this for a splash screen or an advertising screen. 🖼️

- `preload`
  Used for loading large files faster; it can have one of three values:
  - `"none"` does not load the file
  - `"auto"` loads the media file
  - `"metadata`" loads only the information about the file

```htm
<video
  controls
  width="400"
  height="400"
  autoplay
  loop
  muted
  preload="auto"
  poster="poster.png">
  <source src="sky.mp4" type="video/mp4" />
  <source src="sky.webm" type="video/webm" />
  <p>
    Your browser doesn't support this video. No worries, here is a
    <a href="sky.mp4">link to the video</a> that you can watch. 😊
  </p>
</video>
```
