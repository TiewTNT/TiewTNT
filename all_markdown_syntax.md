[![Markdown](https://www.bing.com/th?id=AMMS_ff6f3f7a38b554421b6e614be6e44912&w=188&h=132&c=7&o=6&dpr=1.25&pid=SANGAM)](https://www.bing.com/search?q=Markdown&cvid=cc28678ad4654dc2a21003c3a0e4cf7f&aqs=edge.0.0l9.4196j0j1&pglt=43&FORM=ANNTA1&PC=HCTS)

# Markdown Cheat Sheet

This Markdown cheat sheet provides a quick overview of all the Markdown syntax elements. It can’t cover every edge case, so if you need more information about any of these elements, refer to the reference guides for [basic syntax](https://www.markdownguide.org/basic-syntax) and [extended syntax](https://www.markdownguide.org/extended-syntax).

#### Table of Contents
- [Basic Syntax](#basic-syntax)
- [Extended Syntax](#extended-syntax)
- [Links](#links)

---

## Basic Syntax [↩︎](#markdown-cheat-sheet) {#basic-syntax}

These are the elements outlined in John Gruber’s original design document. All Markdown applications support these elements.

### Heading

```markdown
# H1
## H2
### H3
#### H4
##### H5
###### H6 (H6 is like normal text.)
```

# H1
## H2
### H3
#### H4
##### H5
###### H6

### Bold

```markdown
**bold text**
```

**bold text**

### Italic

```markdown
*italized text*
```

*italicized text*

### Blockquote

```markdown
> blockquote
```

> blockquote

### Ordered List

```markdown
1. First item
2. Second item
3. Third item
4. and so on...
```

1. First item
2. Second item
3. Third item
4. and so on...

### Unordered List

```markdown
- First item
- Second item
- Third item
- and so on...
```

- First item
- Second item
- Third item
- and so on...

### Code

```markdown
`code`
```

`code`

### Horizontal Rule

```markdown
---
```

---

### Link

```markdown
[Markdown Guide](https://www.markdownguide.org)
```

[Markdown Guide](https://www.markdownguide.org)

### Image

```markdown
![alt text](https://www.markdownguide.org/assets/images/tux.png)
```

![alt text](https://www.markdownguide.org/assets/images/tux.png)

---

## Extended Syntax [↩︎](#markdown-cheat-sheet) {#extended-syntax}

These elements extend the basic syntax by adding additional features. Not all Markdown applications support these elements.

### Table

```markdown
| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |
```

| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

### Fenced Code Block

````markdown
```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```
````

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

Add language name to highlight syntax for that language.

````markdown
```python
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```
````

```python
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

### Footnote

```markdown
Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.
```

Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.

### Heading ID

```markdown
#### My Great Heading  (id: #custom id) {#custom-id}
```

#### My Great Heading  (id: #custom id) {#custom-id}

Linking to Heading IDs
You can link to headings with custom IDs in the file by creating a standard link with a number sign (#) followed by the custom heading ID. These are commonly referred to as anchor links.

```markdown
[Heading ID link](#custom-id)
```

[Heading ID link](#custom-id)

### Definition List

```markdown
Term
: definition 1
: defenition 2
```

Term
: definition 1
: defenition 2

### Strikethrough

```markdown
~~The world is flat.~~
```

~~The world is flat.~~

### Task List

To select a checkbox, add an x in between the brackets ([x]).

```markdown
- [x] Task 1
- [ ] Task 2
- [ ] Task 3
```

- [x] Task 1
- [ ] Task 2
- [ ] Task 3

### Emoji

```markdown
That is so funny! :joy:
```

That is so funny! :joy:

(See also [Copying and Pasting Emoji](https://www.markdownguide.org/extended-syntax/#copying-and-pasting-emoji))

[List of emoji shortcodes](https://gist.github.com/rxaviers/7360908)

### Highlight

```markdown
I need to highlight these ==very important words==.
```

I need to highlight these ==very important words==.

### Subscript

```markdown
H~2~O
```

H~2~O

### Superscript

```markdown
X^2^
```

X^2^

### Math

Inline math:
```markdown
$\infty = \infty + 1$
```
$\infty = \infty + 1$

<br>

Math field:
```markdown
$$
9 + 9 = 18
\infty = \infty + 1
$$
```

$$
9 + 9 = 18\\
\infty = \infty + 1
$$

Use \\\ to make line breaks in math fields.

To use math symbols type "\\" then the symbol's name.

```markdown
$\infty$
```

$\infty$

[List of math symbols](https://kapeli.com/cheat_sheets/LaTeX_Math_Symbols.docset/Contents/Resources/Documents/index)

---

## <h2 style="color: green;">Links[↩︎](#markdown-cheat-sheet) </h2>  {#links}

[Basic syntax](https://www.markdownguide.org/basic-syntax)
[Extended syntax](https://www.markdownguide.org/extended-syntax)
[Hacks](https://www.markdownguide.org/hacks/)
[List of emoji shortcodes](https://gist.github.com/rxaviers/7360908)
[HTML codes](https://dev.w3.org/html5/html-author/charref) 
[List of math symbols](https://kapeli.com/cheat_sheets/LaTeX_Math_Symbols.docset/Contents/Resources/Documents/index)