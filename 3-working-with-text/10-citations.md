# Citations

When you write a web page, you might want to show some words or sentences that someone else said or wrote.
You do this to give credit to the original source, or to support your own ideas.
In HTML, which is the language we use to create web pages, we can use the `<cite>` element to show the
title of the resource that we are quoting from.
We should also show the link to the source in the text, so that people can check it out if they want.

```htm
<p>
  This is based on the
  <a href="/en-US/docs/Web/HTML/Element/blockquote">
    <cite>MDN blockquote page</cite></a>:
</p>

<blockquote
  cite="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/blockquote">
  <p>
    The <strong>HTML <code>&lt;blockquote&gt;</code> Element</strong> (or
    <em>HTML Block Quotation Element</em>) shows that the enclosed text is
    a long quotation.
  </p>
</blockquote>

<p>
  The quote element — <code>&lt;q&gt;</code> — is
  <q cite="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/q">
    for short quotations that don't need paragraph breaks.
  </q>
  — from the <a href="/en-US/docs/Web/HTML/Element/q"><cite>MDN q page</cite></a>.
</p>
```

By default, the browser will show the citations in italic font, to show that they are titles.
