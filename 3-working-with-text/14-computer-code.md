# Representing Computer Code

When you write a web page, you might want to show some **computer code** to your visitors.
Maybe you want to teach them how to code, or share some cool tricks with them.
How do you make your code look **nice** and **easy** to read on your web page?

You can use some special elements to **mark up** your computer code using HTML.
HTML is the language we use to create web pages. These elements are:

- `<code>`: For making any piece of computer code look **different** from the normal text.
- `<pre>`: For keeping the **spaces** and **indents** in your code.
  Sometimes, you need to use spaces and indents to make your code look **neat** and **organized**.
  But the browser will **ignore** them and make your code look **messy**.
  If you use `<pre></pre>` tags around your code,
  the browser will **respect** your spaces and indents and show them exactly as you wrote them.
- `<var>`: For highlighting the **names** of the things you use in your code.
  These are called **variables**. Variables are like **containers** that store different values.
  For example, you can have a variable called `name` that stores your name as a value.
- `<kbd>`: For showing the **keys** or **buttons** that you press on your computer.
  For example, you can use `<kbd>Ctrl</kbd>` + `<kbd>C</kbd>` to copy something, or `<kbd>Enter</kbd>` to submit something.
- `<samp>`: For showing the **result** of running your code.
  This is what the computer will **say** or **do** after it executes your code.
  For example, it might say "Hello, world!" or open a new window.

Here is an example of how to use these elements to mark up some computer code:

```htm
<pre>
  <code>
    <!-- This is a comment. It explains what the code does. -->
    <!-- First, we create a variable called btn and assign it to a button element on the web page. -->
    <var>const</var> btn = document.querySelector('button');
    <!-- Then, we add an event listener to the button. This means that when we click the button, something will happen. -->
    btn.onclick = () => {
      <!-- In this case, what will happen is that the computer will show an alert message that says "You clicked the button!" -->
      alert('You clicked the button!')
    }
  </code>
</pre>
```
