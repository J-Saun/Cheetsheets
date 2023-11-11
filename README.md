### Markdown Cheetsheet {#home}

<hr>

- [Codeblock](#codeblock)
- [Lists](#lists)
- [Definitions](#definitions)
- [Task Lists](#task-lists)
- [Emphasis](#emphasis)
- [Horizontal Rule](#hr)
- [HTML](#html)<br>
- [Combinations](#combinations)
- [create an anchor](#anchors-in-markdown)

<br>

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

<br>

### Emphasis

<a id="enphasis" href="#home">Index</a>

Using two asterisks **this text is bold**.<br>
Two underscores **works as well**.<br>
Lets make it _Italic_.<br>
You guessed it, _one underscore is also enough_.<br>
Can we combine _*both of them?*_ Absolutely.<br>
Subscript? H-2-0.<br>
Superscript? x \* x^2.<br>
We can also ==highlight something?<br>

<br>

### Block quotes {#block-quotes}

> This is a block quote.
> Next line with space in between.
>
> > And nested.
> >
> > > You can **style** your text _as you want_.

<br>

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

<br>

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

<br>

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

<br>

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

<br>

### Horizontal Rule {#hr}

First Horizontal rule

---

Second HR

---

<br>

### HTML {#html}

<h1>This is a heading</h1>

<p>Paragraph...</p>

<a href="#">Html Link</a>

<br>
<br>

<p>Small sentence <strong><em>demonstrating</em></strong> HTML tags</p>

<details>
<summary>One more demonstration</summary>

- Easy
- Simple
</details>

<br>

### Combinations {#combinations}

---

#### Block quotes, Tables, & checklist

> ##### Add a checklists to the first layer of a blockquote
>
> - [x] Learn Markdown
> - [ ] Learn Frontend Dev
> - [ ] Learn Full Stack Dec
>
> Next line with space in between.
>
> > And nested inside is a table.
> >
> > > You can **style** your section _as you want_.
> >
> > | TH       |   TH    |      TH |
> > | :------- | :-----: | ------: |
> > | React.js | Node.js |   MySQL |
> > | Next.js  | Express | MongoDB |
> > | Vue.js   | Next.js |         |
> >
> > > Add a horizontal rule
> >
> > ## and keep nesting
> >
> > End of Example

[Index](#home)
