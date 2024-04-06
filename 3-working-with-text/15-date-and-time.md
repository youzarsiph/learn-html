# Marking up Date and Time

When you write a web page, you might want to show some **times and dates** to your visitors.
Maybe you want to tell them when an event is happening, when a blog post was published, or when a photo was taken.
How do you make your times and dates look **nice** and **consistent** on your web page?

You can use a special element called `<time>` to **mark up** your times and dates using HTML.
HTML is the language we use to create web pages.
The `<time>` element lets you write your times and dates in a **standard** format that the computer can **understand**.
This way, the computer can **display** your times and dates in different ways, such as a calendar, a clock, or a reminder.

Here is an example of how to use the `<time>` element:

```htm
<!-- Standard simple date -->
<time datetime="2024-02-01">1 February 2024</time>

<!-- Just year and month -->
<time datetime="2024-01">January 2024</time>

<!-- Just month and day -->
<time datetime="01-20">20 January</time>

<!-- Just time, hours and minutes -->
<time datetime="19:30">19:30</time>

<!-- You can do seconds and milliseconds too! -->
<time datetime="19:30:01.856">19:30:01.856</time>

<!-- Date and time -->
<time datetime="2024-01-20T19:30">7.30pm, 20 January 2024</time>

<!-- Date and time with timezone offset -->
<time datetime="2024-01-20T19:30+01:00">
  7.30pm, 20 January 2024 is 8.30pm in France
</time>

<!-- Calling out a specific week number -->
<time datetime="2024-W04">The fourth week of 2016</time>
```

As you can see, there are many different ways that humans write down dates. But the `<time>` element makes sure that the computer knows what they mean. 😊
