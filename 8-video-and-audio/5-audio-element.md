# The `<audio>` Element 🎵

Do you want to make your webpages more lively and engaging with audio?
😍 You can do that easily with the `<audio>` element. Here is a simple example of how it works:

```htm
<audio controls>
  <source src="rain.mp3" type="audio/mp3" />
  <source src="rain.ogg" type="audio/ogg" />
  <p>
    Your browser doesn't support this audio file. No worries, here is a
    <a href="rain.mp3">link to the audio</a> that you can listen to. 😊
  </p>
</audio>
```

This takes up less space than a video player, because there is no picture — you just need to show buttons to play the audio.
Other differences from HTML video are these:

- The `<audio>` element doesn't need the width/height attributes
  — because there is no picture, so there is nothing to change the size of.
- It also doesn't need the poster attribute — again, no picture.
- Other than this, `<audio>` has all the same features as `<video>`. 🙌
