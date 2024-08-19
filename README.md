# HTML Basics

## Introduction

**HTML (HyperText Markup Language)** is the standard language for creating web pages. It structures content on the web, defining elements like text, images, links, and more.

## HTML Tags and Elements

- **HTML Tags**: The basic building blocks of HTML, enclosed in angle brackets (`< >`).
- **HTML Elements**: Consist of a start tag, content, and an end tag.
  - Example: `<p>This is a paragraph.</p>`

## Inline Elements

- **Non-Replaced Inline Elements**: Display their content directly, like text inside a `<span>`.
- **Replaced Inline Elements**: Display external content or resources, such as images inside an `<img>` tag.

### Characteristics of Inline Elements:
1. Only take up space as wide as their content.
2. Do not start on a new line.
3. Padding and margin adjustments are applicable horizontally.
4. **Examples**: `<span>`, `<img>`, `<a>`.

## Block-Level Elements

- **Characteristics of Block-Level Elements**:
  1. Take up the full width available.
  2. Start on a new line.
  3. **Examples**: `<div>`, `<p>`, `<h1>`.

## `<!DOCTYPE>` Declaration

The `<!DOCTYPE>` declaration informs the browser about the version of HTML that the document is written in.

## Importance of the `<head>` Tag

The `<head>` tag contains metadata and links to external resources:

1. **Metadata**: Information such as language, author, and title.
2. **External Resources**: Links to JavaScript, CSS, images, fonts, and CDN links.
3. **Favicon**: The icon displayed in the browser tab.

### Meta Tags

Meta tags provide information about the document, including charset, viewport settings, title, description, author details, and SEO information.

## Semantic HTML Elements

Semantic HTML elements clearly describe their meaning in a human- and machine-readable way, improving the structure and accessibility of web pages.

### Examples:
- `<header>`
- `<nav>`
- `<article>`
- `<section>`
- `<footer>`

## Web Workers

Web workers are background threads in JavaScript that execute code independently of the main thread.

## The `<title>` Tag

The `<title>` tag is used for:
- Bookmarking/Favorite pages.
- Social media sharing.
- Displaying the title in the browser tab.

## `<article>` vs. `<section>`

- **`<section>`**: A generic container used to group related content together.
- **`<article>`**: An independent self-contained unit with a title and content.

## HTML Attributes

HTML attributes provide additional information about HTML elements.

### Common Attributes:
- `class`
- `id`
- `style`
- `data-*` (data attributes)

### Specific Attributes:
- `href`
- `src`
- `alt`
- `width`
- `height`

## Links in HTML

- **`<link>` Tag**: Used to link external resources like CSS files.
- **`<a>` (Anchor) Tag**: Used to create hyperlinks.

## The `<base>` Element

The `<base>` element sets a base URL for all relative URLs in the document and is placed inside the `<head>` section.
