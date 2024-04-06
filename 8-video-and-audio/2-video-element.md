# The `<video>` Element 🎥

Do you want to make your webpages more lively and engaging with video?
😍 You can do that easily with the `<video>` element. Here is a simple example of how it works:

```htm
<video src="sky.webm" controls>
  <p>
    Your browser doesn't support HTML video. No worries, here is a
    <a href="sky.webm">link to the video</a> that you can watch. 😊
  </p>
</video>
```

Let's look at the features of this code:

- `src`
  Just like the `<img>` element, the src (source) attribute tells the browser where to find the video you want to show.
  It's as simple as that. 🙌

- `controls`
  Users need to be able to control the video and audio playback (it's very important for people who have epilepsy.)
  You can use the `controls` attribute to show the browser's own control buttons, or you can make your own buttons with JavaScript API.
  At least, you need to have buttons to play and pause the media, and to change the volume. 🔊

The paragraph inside the `<video>` tags is called fallback content — this is what the browser will show if it doesn't
support the `<video>` element. This way, you can provide a backup option for older browsers.
You can put anything you want here; in this case, we've given a direct link to the video file,
so the user can still watch it somehow. 👍
