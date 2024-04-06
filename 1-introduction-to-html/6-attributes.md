# Attributes

Attributes are like **spices** that you can sprinkle on your elements.
They are **invisible** to the viewers, but they can **enhance** the appearance or behavior of the content.

An attribute should follow these rules:

- It should be **separated** from the element name by a space.
  (If you want to add more than one attribute for an element, you should also leave spaces between them.)
- It should have a **name**, followed by an equal sign.
- It should have a **value**, wrapped with opening and closing quote marks.

In this example, the class attribute is a **label** that you can use to apply different styles to the element.

```htm
Attribute--+
           |
   +---------------+
<p class="paragraph">HTML is easy to learn.</p>
   +---+ +---------+
     |        |
     |        +--> Value
     +--> Name
```

## Boolean attributes

Some attributes don't need values. They are like **switches** that you can turn on or off. This is okay.
These are called Boolean attributes.
Boolean attributes can only have one value, which is usually the same as the attribute name.

```htm
Boolean attribute <---+
                      |
                   +------+
<input type="text" disabled />
```

This is an example of a Boolean attribute.
It has the name `disabled` inside the tag, and no value.
The `disabled` attribute makes the input element **unusable**. 🚫
