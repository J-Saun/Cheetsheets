# Markdown Cheatsheet<a name="TOP"></a>

### Index

<a id="index"></a>

[Emphasis](#emphasis)

[Links](#links)

[Tables](#tables)

[Code block](#code)

[Lists](#lists)

[Blockquote](#blockquote)

[Emphasis](#emphasis)

[Horizontal Line](#hr)

[Task Lists](#task-lists)

[Definitions](#definitions)

[Horizontal Rule](#hr)

[HTML](#html)

[Combinations](#combinations)

[create an anchor](#anchors-in-markdown)

---

### References

<a id="references"></a>

[Unicode]("https://www.compart.com/en/unicode/")

<a href="#index">ꜛ Index</a>

### Headings

<a id="headings"></a>

---

# Heading 1

```
    # Heading 1
```

```
    ============= (below H1 text)
```

## Heading 2

```
      ## Heading 2
```

```
     --------------- (below H2 text)
```

### Heading 3

      ### Heading 3

#### Heading 4

      #### Heading 4

##### Heading 5

      ##### Heading 5

---

### Emphasis

<a id="emphasis" />

Common text

    Just add txt to the md file

_Emphasized text_

```
    _Emphasized text_
```

```
    *Emphasized text*
```

~~Strikethrough text~~

    ~~Strikethrough text~~

**Strong text**

```
      __Strong text__
```

```
       **Strong text**
```

**_Strong emphasized text_**

```
      ___Strong emphasized text___
```

      ```
       ***Strong emphasized text***
      ```

<a href="#index">ꜛ Index</a>

### Links

<a id="links" />

[Named Link](http://www.google.fr/ "Named link title") and http://www.google.fr/ or <http://example.com/>

      [Named Link](http://www.google.fr/ "Named link title") and http://www.google.fr/ or <http://example.com/>

[heading-1](#heading-1 "Goto heading-1")

     [heading-1](#heading-1 "Goto heading-1")

<a href="#index">ꜛ Index</a>

### Tables

<a id="tables" />

| First Header | Second Header |
| ------------ | ------------- |
| Content Cell | Content Cell  |
| Content Cell | Content Cell  |

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
| Content Cell | \| <-- pipe   |

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

<a href="#index" >ꜛ Index</a>

### Code

<a id="code" />

`code()`

    `code()`

> Specify the language next to the ticks ex. ```javascript

```javascript
var specificLanguage_code = {
  data: {
    lookedUpPlatform: 1,
    query: "Kasabian+Test+Transmission",
    lookedUpItem: {
      name: "Test Transmission",
      artist: "Kasabian",
      album: "Kasabian",
      picture: null,
      link: "http://open.spotify.com/track/5jhJur5n4fasblLSCOcrTp",
    },
  },
};
```

     ```javascript
             ```

<a href="#index" >ꜛ Index</a>

### Lists

<a id="lists" />

- Bullet list
  - Nested bullet
    - Sub-nested bullet etc
- Bullet list item 2

```
 Markup : * Bullet list
              * Nested bullet
                  * Sub-nested bullet etc
          * Bullet list item 2

-OR-

 Markup : - Bullet list
              - Nested bullet
                  - Sub-nested bullet etc
          - Bullet list item 2
```

1. A numbered list
   1. A nested numbered list
   2. Which is numbered
2. Which is numbered

```
 Markup :   1. A numbered list
                1. A nested numbered list
                2. Which is numbered
            2. Which is numbered
```

- [ ] An uncompleted task
- [x] A completed task

```
 Markup : - [ ] An uncompleted task
          - [x] A completed task
```

- [ ] An uncompleted task
  - [ ] A subtask

```
 Markup : - [ ] An uncompleted task
              - [ ] A subtask
```

<a name="index" >Index</a>

### Blockquote

<a name="blockquote" />

> Blockquote
>
> > Nested blockquote

```
    > Blockquote
    >> Nested Blockquote
```

> ##### Checklist
>
> - [x] Task 1
> - [ ] Task 2
> - [ ] Task 3
>
>   > ##### List
>   >
>   > - List Item
>   >   - Sub List Item
>   > - Another Item
>   > - Another Item

```
> ##### Checklist
>
>   - [x] Task 1
>   - [ ] Task 2
>   - [ ] Task 3
>> ##### List
>>
>>  - List Item
>>      - Sub List Item
>>  - Another Item
>>  - Another Item
```

> ##### With a Table
>
> > **Title**
> > Left aligned | Right aligned | Center aligned
> > | :--- | ---: | :---:
> > Content Cell | Content Cell | Content Cell
> > Content Cell | Content Cell | Content Cell
> >
> > _\*Note to remember_
>
> And on with the table

```
> ##### With a Table
>
>> **Title**
>> Left aligned Header | Right aligned Header | Center aligned Header
>> | :--- | ---: | :---:
>> Content Cell  | Content Cell | Content Cell
>> Content Cell  | Content Cell | Content Cell
>>
>> _*Note to remember_
>
> And on with the table
```

<a href="#index" >ꜛ Index</a>

### Horizontal line

<a idd="hr" />

_Horizontal line :_

---

      - - - -

<a name="index" >Index</a>

### Images

<a name="images" />

_Image with alt :_

![picture alt](http://via.placeholder.com/200x150 "Title is optional")

     ![picture alt](http://via.placeholder.com/200x150 "Title is optional")

Foldable text:

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

[ꜛ Go To TOP](#index)

    [text goes here](#section_name)
    section_title<a name="section_name"></a>

Hotkey:

<kbd>⌘F</kbd>

<kbd>⇧⌘F</kbd>

    Markup : <kbd>⌘F</kbd>

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