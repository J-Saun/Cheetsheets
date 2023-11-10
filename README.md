# Cheetsheets {#home}

[Codeblock](#codeblock)
[Lists](#lists)
[Definitions](#definitions)
[Task Lists](#task-lists)
[Horizontal Rule](#hr)
[HTML](#html)

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

### Emphasis

Using two asterisks **this text is bold**.
Two underscores **works as well**.
Lets make it _Italic_.
You guessed it, _one underscore is also enough_.
Can we combine _*both of them?*_ Absolutely.
Subscript? H-2-0.
Superscript? x \* x^2.
We can also ==highlight something?

> This is a block quote.
> Next line with space in between.
>
> > And nested.
> >
> > > You can **style** your text _as you want_.

### Codeblock {#codeblock}

I created `.env` file at the root.

```
{
    learning: "Markdown",
    showing: "block code snippet"
}

```

```js
const x = "Block code snippet in JS";
console.log(x);
```

### Lists {#lists}

- Node.js
- Express
- Next.js
- Learning backend

1. Learn Basics
   1. HTML
   2. CSS
   3. Javascript
2. Learn one framework
   - React
     - Router
     - Redux
   - Vue
   - Svelte
     [Index](#home)

### Definitions {#definitions}

React.js
: Javascript library for building interfaces

Next.js
: The React framework

| Left Align (default) | Center Align | Right Align |
| :------------------- | :----------: | ----------: |
| React.js             |   Node.js    |       MySQL |
| Next.js              |   Express    |     MongoDB |
| Vue.js               |   Next.js    |             |

[Index](#home)

### Task Lists {#task-lists}

- [x] Learn Markdown
- [ ] Learn Frontend Dev
- [ ] Learn Full Stack Dec

Footnote not working

#### I am working on a project. [^1]

[1]: Stack is: React, typescript, Tailwind CSS

Project is about movies and music

Link to headers

[Jump to header below](#some-id)

...

### Heading with id {#some-id}

[Index](#home)

### Horizontal Rule {#hr}

First Horizontal rule

---

Second HR

---

### HTML {#html}

<h1>This is a heading</h1>

<p>Paragraph...</p>

<a href="#">Link</a>

<br>
<br>

<p>Small sentence <strong><em>demonstrating</em></strong> HTML tags</p>

<details>
<summary>One more demonstration</summary>

- Easy
- Simple
</details>