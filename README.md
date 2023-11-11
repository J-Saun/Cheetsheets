# Markdown Cheetsheet

<a id="TOP" />

<a href="cheatsheet.md">← Back to ReadMe</a>

### Index

<a id="index" />

[Headings](#headers)

[Emphasis](#emphasis)

[Blockquote](#blockquote)

[Code block](#codeblock)

[Lists](#lists)

[Task Lists](#task-lists)

[Definitions](#definitions)

[Tables](#tables)

[Annotations](#annotations)

[Foldable text](#fold-text)

[Tables](#tables)

[Combinations](#combinations)

[create an anchor](#anchors-in-markdown)

<br>

### References

<a id="references"></a>

[Unicode]("https://www.compart.com/en/unicode/")

<br>
<a href="#index">ꜛ Index</a>
<br><br>

<a id="headers" />

# Heading 1

```
  # Heading 1
```

## Heading 2

```
  ## Heading 2
```

### Heading 3

```
  ### Heading 3
```

#### Heading 4

```
  #### Heading 4
```

##### Heading 5

```
  ##### Heading 5
```

<br>
<a href="#index">ꜛ Index</a>
<br><br>

### Emphasis

<a id="emphasis" />

Using two asterisks **this text is bold**.

```
  **Text Here**
```

<br>

Lets make it _Italic_.

```
__Text Here__
```

or

```
_Text Here_
```

<br>

Combine _*both of them*_.

```
_*Text Here*_
```

##### Subscript/superscript

Subscript? H-2-0.<br>
Superscript? x \* x^2.<br>
We can also ==highlight something?<br>

<br>
<a href="#index">ꜛ Index</a>
<br><br>

### Blockquote

<a id="blockquote" />

> This is a block quote.
> Next line with space in between.
>
> > And nested.
> >
> > > You can **style** your text _as you want_.

<br>

```
> This is a block quote.
> Next line with space in between.
>
> > And nested.
> >
> > > You can **style** your text _as you want_.
```

<br>
<a href="#index">ꜛ Index</a>
<br><br>

### Codeblock

<a id="codeblock" />

I created `.env` file at the root.

```
{
    learning: "Markdown",
    showing: "block code snippet"
}

```

Add the language next to the backticks ```js

```js
const x = "Block code snippet in JS";
console.log(x);
```

<br>
<a href="#index">ꜛ Index</a>
<br><br>

### Lists

<a id="lists" />

- Node.js
- Express
- Next.js
- Learning backend

```
- Node.js
- Express
- Next.js
- Learning backend
```

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

```
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
```

Checklist

- [ ] An uncompleted task
- [x] A completed task

```
  - [ ] An uncompleted task
  - [x] A completed task
```

<br>
<a href="#index">ꜛ Index</a>
<br><br>

### Definitions

<a id="definitions" />

React.js
: Javascript library for building interfaces

Next.js
: The React framework

<br>
<a href="#index">ꜛ Index</a>
<br><br>

### Tables

<a id="tables" />

| First Header | Second Header |
| ------------ | ------------- |
| Content Cell | Content Cell  |
| Content Cell | Content Cell  |

Small Table -

```
| First Header | Second Header |
| ------------ | ------------- |
| Content Cell | Content Cell  |
| Content Cell | Content Cell  |
```

| First Header | Second Header | Third Header | Fourth Header |
| :----------: | :-----------: | :----------: | :-----------: |
| Content Cell | Content Cell  | Content Cell | Content Cell  |
| Content Cell | Content Cell  | Content Cell | Content Cell  |
| Content Cell | Content Cell  | Content Cell | Content Cell  |
| Content Cell | Content Cell  | Content Cell | Content Cell  |

Large Table -

```
|First Header  | Second Header | Third Header | Fourth Header |
| :----------: | :-----------: | :----------: | :-----------: |
| Content Cell | Content Cell  | Content Cell | Content Cell  |
| Content Cell | Content Cell  | Content Cell | Content Cell  |
| Content Cell | Content Cell  | Content Cell | Content Cell  |
| Content Cell | Content Cell  | Content Cell | Content Cell  |
```

Adding a pipe `|` in a cell :

| First Header | Second Header |
| ------------ | ------------- |
| Content Cell | Content Cell  |
| Content Cell | \|            |

```
First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  |  \|
```

Left, right and center aligned table

| Left aligned Header | Right aligned Header | Center aligned Header |
| :------------------ | -------------------: | :-------------------: |
| Content Cell        |         Content Cell |     Content Cell      |
| Content Cell        |         Content Cell |     Content Cell      |

```
Left aligned Header | Right aligned Header | Center aligned Header
| :--- | ---: | :---:
Content Cell  | Content Cell | Content Cell
Content Cell  | Content Cell | Content Cell
```

<br>
<a href="#index">ꜛ Index</a>
<br><br>

### Annotation

<a id="annotation" />

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

### Images

<a name="images" />

_Image with alt :_

![picture alt](http://via.placeholder.com/200x150 "Title is optional")

     ![picture alt](http://via.placeholder.com/200x150 "Title is optional")

<br>
<a href="#index">ꜛ Index</a>
<br><br>

### Foldable text

<a id="fold-text" />

<details>
  <summary>Title 1</summary>
  <p>Content 1 Content 1 Content 1 Content 1 Content 1</p>
</details>
<details>
  <summary>Title 2</summary>
  <p>Content 2 Content 2 Content 2 Content 2 Content 2</p>
</details>

    Markup : <details>
               <summary>Title 1</summary>
               <p>Content 1 Content 1 Content 1 Content 1 Content 1</p>
             </details>

```html
<h3>HTML</h3>
<p>Some HTML code here</p>
```

Link to a specific part of the page:

[ꜛ Go To TOP](#TOP)

    [text goes here](#section_name)
    section_title<a name="section_name"></a>

Hotkey:

<kbd>⌘F</kbd>

<kbd>⇧⌘F</kbd>

    <kbd>⌘F</kbd>

Hotkey list:

| Key       | Symbol |
| --------- | ------ |
| Option    | ⌥      |
| Control   | ⌃      |
| Command   | ⌘      |
| Shift     | ⇧      |
| Caps Lock | ⇪      |
| Tab       | ⇥      |
| Esc       | ⎋      |
| Power     | ⌽      |
| Return    | ↩      |
| Delete    | ⌫      |
| Up        | ↑      |
| Down      | ↓      |
| Left      | ←      |
| Right     | →      |

Emoji:

:exclamation: Use emoji icons to enhance text. :+1: Look up emoji codes at [emoji-cheat-sheet.com](http://emoji-cheat-sheet.com/)

    Markup : Code appears between colons :EMOJICODE:
