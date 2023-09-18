# Text

- Headings and paragraphs
- Bold, italic, emphasis
- Structural and semantic markup

## Headings
```<h1>```
```<h2>```
```<h3>```
```<h4>```
```<h5>```
```<h6>```

If there are further sections under the subheadings then ```<h3>``` element is used, and so on...

## Paragraphs

```<p>text</p>```

By default each browser will show each paragraph on a new line with some space between it and any subsequent paragraphs.

## Bold & Italic

```<b>This text is bold</b>```

```<i>This text is italic</i>```

## Superscript & Subscript

Three squared

```3<sup>2</sup>```

Carbon Dioxide

```CO<sub>2</sub>```

## White space

When the browser comes across two or more spaces next to each other, it only displays one space. Similarly if it comes across a line break, it treats that as a single space too. This is known as <b>white space collapsing</b>

## Line breaks and horizontal rules

```<br />```: Adds a line break.

```<hr />```: create a break between themes

There are a few elements that do not have any words between an opening and closing tag. The are known as <b>empty elements</b>, they usually have only one tag.

Before the closing angled bracket of an empty element there will often be a space and a forward slash character.

## Semantic Markup

There are some text elements that are not intended to affect the structure of your web pages, but they do add extra information to the pages.

## Strong & Emphasis

```<strong>This content is important</strong>``` -> Indicates that its content has strong importance. By default browsers will show the contents of a strong element in bold.

```<em>Emphasis</em> ``` -> indicates emphasis that subtly changes the meaning of a sentence. By default contents of an em element are in italic.

## Quotations

```
<blockquote>
    <p>This is used for longer quotes</p>
</blockquote>
```

Browsers tend to indent the contents of this element, however you should not use this element just to indent a piece of text.

```
<p>As A.A. Milne said. <q>Some people tal to animals.</q></p>
```

This is used for shorter quotes that sit within a paragraph.

## Abbreviations & acronyms

```
<abbr title="Professor" >Prof</abbr>
```

## Citations & Definitions

```
<p><cite>A Brief History of time</cite>by Stephen Hawking</p>
```

Browsers will render the content of a cite element in italics.

```
<p>A <dfn>black hole</dfn>is a region os space that not even light can scape.</p>
```

This is used to indicate the defining instance of a new term.

## Author details

```
<address>
    <p>742 Evergreen Terrace. Springfield.</p>
    <p><a href="mailto:homer@example.org">homer@example.org</a></p>
</address>
```

Contains details for the author of the page.