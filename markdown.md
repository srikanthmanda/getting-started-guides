# Markdown

## Index

- [What is Markdown?](#what-is-markdown)
- [Syntax](#syntax)
  - [Styling](#styling)
  - [Headings](#headings)
  - [Hyperlinks](#hyperlinks)
  - [Code](#code)
  - [Bullet Points](#bullet-points)
  - [Ordered Lists](#ordered-lists)
- [Additional Notes](#additional-notes)
- [Resources](#resources)

## What is Markdown?

Markdown is a plain text format. It enables us to use style elements like
emphasis and structural elements like headings in plain text documents, without
having to use complicated markup tags (hence the name).

Markdown documents are easy to write and read, using just plain text editors.
But with additional tools, they can be easily converted to other formats like
HTML and PDF.

Markdown is widely used in the areas of technical documentation. Popular tools
like Google Docs support Markdown formatting. In fact, you might already be
using some of the ideas like wrapping text in asterisks for `**emphasis**`
(which becomes **emphasis**).

## Syntax

> [!NOTE]
> This document is intended to be read as a HTML page. But if you're reading the
> Markdown source, please note that code blocks are used to preserve the syntax
> inside the Markdown snippets.

### Styling

- Phrases can be strongly emphasized, i.e. made bold using `**` (double
  asterisks). Example: `**strong emphasis (bold)**` becomes **strong emphasis
  (bold)**.
- Phrases can be gently emphasized, i.e. italicized using `*` (single asterisk).
  Example: `*italicized phrase*` becomes *italicized phrase*.

### Headings

- H1 starts with `#` (hashtag/octothorpe).
- H2 starts with `##` 
- H3 starts with `###`
- H4 starts with `####`

Example: `# Title` in Markdown is the same as `<h1>Title</h1>` in HTML.

### Hyperlinks

Link text is enclosed in `[]`, immediately followed by the link enclosed in `()`.

Example: `[example](https://example.com)` becomes [example](https://example.com).

You can also link to sections of the same document using `(#anchor)`.

Example: `[next section: Code](#code)` becomes [next section: Code](#code).

### Code

Inline code is enclosed in ` (backtick) characters.

Example: \`function\` becomes inline code `function`.

Longer code blocks may be enclosed between a pair of ``` (triple backtick)
characters on new lines. This is called code fencing. You can also specify
the language after the opening backticks.

Examples:

- Code block/fence of unspecified language:

  ````
  ```
  <html>
    <p>This is a code block in Markdown</p>
  </html>
  ```
  ````
  
  This renders as:

  ```
  <html>
    <p>This is a code block in Markdown</p>
  </html>
  ```

- Code block/fence in JavaScript:

  ````
  ```js
  function logToConsole() {
    console.log("This is a JavaScript code block in Markdown");
  }
  ```
  ````

  This renders as:

  ```js
  function logToConsole() {
    console.log("This is a JavaScript code block in Markdown");
  }
  ```

### Bullet Points

Bullet points may start with any of the following symbols: `-` (hyphen), `*`
(asterisk), `+` (plus).

Example list with hyphens:

```
- An item
- Another item
```

Example list with asterisks:

```
* An item
* Another item
```

Both the above lists render as:

- An item
- Another item

### Ordered Lists

Ordered lists can use sequential numbering or repeat one (1) for all items.

Example list with items numbered sequentially:

```
1. First item
2. Second item
```

Example list with all items numbered with one (1):

```
1. First item
1. Second item
```

Both the above lists render as:

1. First item
2. Second item

## Additional Notes

- You may mark text as H1 and H2 headings by underlining it with equal signs
  (`=`) and hyphens (`-`), respectively (instead of using the hashtags format).
- You can also mark text as H5 and H6 headings by starting them with five and
  six hashtags, respectively.
- Markdown also supports tables, blockquotes (for excerpts and callouts), and
  footnotes (e.g. for citations). Read the resources below for more information.

## Resources

- [Markdown: Basics](https://daringfireball.net/projects/markdown/basics), by
  its creator John Gruber.
- [GitHub Flavored Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

---

Navigation:

- [↑ Go to top](#markdown)
- [↩ Return to Index](README.md)
