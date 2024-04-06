# Add text tracks to your videos 🎥

WebVTT is a format for writing text files with multiple lines of text and some extra
information like the time in the video when each line should show up, and some basic styling/positioning options.
These lines of text are called cues, and there are different types of cues for different purposes.

The most common cues are:

- `subtitles`
  Translations of foreign words, for people who don't speak the language of the audio.

- `captions`
  Synchronized words or descriptions of important sounds, to let people who can't hear the audio know what is happening.

- `timed descriptions`
  Text that should be spoken by the media player to describe important images to blind or visually impaired users.

```console
WEBVTT

1
00:00:22.230 --> 00:00:24.606
This is the first subtitle.

2
00:00:30.739 --> 00:00:34.074
This is the second.

...
```

To show this along with the HTML video, you need to:

- Save it as a .vtt file in a good place.
- Link to the .vtt file with the `<track>` element.
  `<track>` should go inside `<audio>` or `<video>`, but after all `<source>` elements.
  Use the kind attribute to tell the browser if the cues are subtitles, captions, or descriptions.
  Also, use `srclang` to tell the browser what language you have written the subtitles in.
  And, add label to help readers find the language they want.

```htm
<video controls>
  <source src="sky.mp4" type="video/mp4" />
  <source src="sky.webm" type="video/webm" />
  <track kind="subtitles" src="subtitles_ar.vtt" srclang="ar" label="Arabic" />
</video>
```
