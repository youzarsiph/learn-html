# Quotations

When you write a web page, you might want to show some words or sentences that someone else said or wrote.
You do this to give credit to the original source, or to support your own ideas. In HTML, which is the language we
use to create web pages, we can use different elements to mark up quotations, depending on how long or short they are.

## Blockquote

If you want to quote a large chunk of text (like a paragraph, multiple paragraphs, a list, etc.) from somewhere else,
you can use the `<blockquote>` element to show this. You should also include a URL that points to the source of the
quote inside a cite attribute, so that people can check where you got it from.

```htm
<p>Here is a blockquote:</p>

<blockquote 
  cite="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/blockquote">
  <p>
    The <strong>HTML <code>&lt;blockquote&gt;</code> Element</strong> (or
    <em>HTML Block Quotation Element</em>) shows that the enclosed text is
    a long quotation.
  </p>
</blockquote>

```

By default, the browser will show this as a paragraph that is moved a bit to the right, to show that it is a quote.

## Inline quotations

If you want to quote a small piece of text (like a word, a phrase, or a sentence) from somewhere else,
you can use the `<q>` element to show this. You should also include a URL that points to the source of the
quote inside a cite attribute, so that people can check where you got it from.

```htm
<p>
  The quote element — <code>&lt;q&gt;</code> — is
  <q cite="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/q">
    for short quotations that don't need paragraph breaks.
  </q>
</p>
```

By default, the browser will show this as normal text with quotation marks around it, to show that it is a quote.

This is how you can use quotations in HTML using the `<blockquote>` and `<q>` elements.
Quotations can make your content more credible and clear. 😊
