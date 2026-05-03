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
using some of the ideas like wrapping text in asterisks for **emphasis**.

## Syntax

### Styling

- Phrases can be strongly emphasized, i.e. made bold using `**` (double
  asterisks). Example: **This text is strongly emphasized and appears in bold**.
- Phrases can be gently emphasized, i.e. italicized using `*` (single asterisk).
  Example: *This is an italicized phrase*.

### Headings

- H1 starts with `#` (hashtag/octothorpe).
- H2 starts with `##` 
- H3 starts with `###`
- H4 starts with `####`

Example: `# Title` in Markdown is the same as `<h1>Title</h1>` in HTML.

### Hyperlinks

Link text is enclosed in `[]`, immediately followed by the link enclosed in `()`.

Example: [This is an example link](https://example.com)

You can also link to sections of the same document.

Example: [This is a link to the following section: Code](#code)

### Code

Code keywords may be enclosed between a pair of "`" (backtick) characters.
Longer code blocks may be enclosed between a pair of "```" (triple backtick)
characters on new lines.

Enclosing code blocks in a pair of triple backticks is also called code fencing.
You may also specify the code language in the first line, after the backticks.

Examples:

- Function keyword: `function`.
- Code block/fence of unspecified language:

  ```
  <html>
    <p>This is a code block in Markdown</p>
  </html>
  ```

- Code block/fence in JavaScript:

  ```js
  function logToConsole() {
    console.log("This is a JavaScript code block in Markdown");
  }
  ```

### Bullet Points

Bullet points may start with any of the following symbols: `-` (hyphen), `*`
(asterisk), `+` (plus).

Example list:

- An item
- Another item

Same list using asterisks instead of hyphens:

* An item
* Another item

### Ordered Lists

Items in an ordered list may start with the number of that item in the list, or
with number one (1).

Example:

1. First item
2. Second item

Same list with all items numbered with just 1:

1. First item
1. Second item

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
