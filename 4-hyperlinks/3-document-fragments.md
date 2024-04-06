# Document Fragments

You can link to a *particular* part of an HTML document,
called a document fragment, instead of just to the top of the document.
To do this you first have to give an id attribute to the element you want to link to.
It usually makes sense to link to a *certain* heading

```htm
<h1>Document Fragments</h1>
<p>
  Learn how to link a *particular* part of an HTML document.
  To link to that *specific* `id`,
  you'd add it at the end of the URL, followed by a hash/pound symbol (`#`).
  
  Here is a link to a <a href="index.html#target">**document fragment**</a>.
</p>

<h2 id="target">Target Element</h2>
```

This is how you can use document fragments in HTML using the id attribute and the hash symbol.
Document fragments can help you *navigate* your web page better. 😊
