# Web Foundations

A small web project for building and refining core frontend fundamentals with HTML, CSS, and JavaScript.

## Overview

**Web Foundations** is a progressive frontend practice project focused on creating structured, styled, and interactive web pages without relying on external frameworks.

The project starts from basic page composition and gradually expands into reusable UI patterns, form interactions, DOM manipulation, and small browser-based features.

The main purpose of this repository is to build a solid foundation in how the browser renders, styles, and updates web pages using native web technologies.

## Tech Stack

| Category        | Technology  |
| --------------- | ----------- |
| Markup          | HTML        |
| Styling         | CSS         |
| Programming     | JavaScript  |
| Runtime         | Browser     |
| Version Control | Git, GitHub |

## Current Scope

At the current stage, this repository focuses on the following areas:

* Writing semantic HTML structures
* Organizing text content with headings, paragraphs, and lists
* Structuring tabular information with HTML tables
* Using links and images to connect pages with external resources and visual content
* Building form layouts with native HTML controls
* Applying external stylesheets to individual pages
* Creating multi-column and content-focused layouts
* Using reusable class-based CSS rules
* Controlling typography, spacing, borders, and image dimensions
* Applying state-based link styles with pseudo-classes
* Understanding how HTML structure and CSS presentation work together

The scope will be updated as the project grows.

## Project Status

This project is in an early development stage.

Current work:

* Initial HTML pages implemented
* Text, list, table, image, link, and form elements applied
* External stylesheets introduced
* Travel page styling completed
* Three-column gallery layout implemented
* Structured news article layout implemented

## Pages

| File           | Description                                                                                                            |
| -------------- | ---------------------------------------------------------------------------------------------------------------------- |
| `intro.html`   | A simple self-introduction page built with headings, lists, paragraphs, line breaks, and inline text formatting tags   |
| `travel.html`  | A travel plan page built with an HTML table, merged rows and columns, images, external links, and external CSS styling |
| `signup.html`  | A signup form built with grouped form controls, labels, input fields, radio buttons, a checkbox, and a select box      |
| `gallery.html` | A gallery page arranged in a three-column layout with reusable cells, responsive images, and a status badge            |
| `news.html`    | A structured news article page with metadata, action buttons, image captions, article sections, and related links      |

## Styles

| File                 | Description                                                                                                        |
| -------------------- | ------------------------------------------------------------------------------------------------------------------ |
| `styles/travel.css`  | Styles the travel page heading, table headers, links, and images                                                   |
| `styles/gallery.css` | Defines the gallery layout, image sizing, spacing, header presentation, and badge styling                          |
| `styles/news.css`    | Defines the article container, typography, buttons, image panels, content sections, footer links, and hover states |

## Implementation Notes

### `intro.html`

The introduction page demonstrates basic HTML document composition through a simple self-introduction layout.

It includes:

* Headings and horizontal dividers
* Ordered and unordered lists
* Paragraphs and line breaks
* Strong and italic text emphasis

### `travel.html`

The travel page organizes a short Bali travel plan using a table-based layout.

It includes:

* Document metadata
* Table headers, rows, and cells
* Merged rows with `rowspan`
* Merged columns with `colspan`
* Images with alternative text
* External destination links
* An external stylesheet linked through the document head

The page separates its content structure from presentation through `styles/travel.css`.

### `styles/travel.css`

The travel stylesheet defines:

* Heading typography
* Table header presentation
* Link appearance
* Consistent image sizing

### `signup.html`

The signup page introduces a structured form for collecting account and profile information.

It includes:

* Fieldsets and legends
* Labels connected to form controls
* Text, password, and number inputs
* Select options
* Radio buttons and checkbox controls
* Form submission input

### `gallery.html`

The gallery page presents a collection of images in a reusable three-column layout.

It includes:

* Semantic page header
* Reusable row and cell classes
* Image alternative text
* External stylesheet integration
* A status badge beside the page title

### `styles/gallery.css`

The gallery stylesheet defines:

* A basic CSS reset
* Three-column cells using `inline-block`
* Percentage-based widths and margins
* Responsive image sizing
* Centered gallery rows
* Header spacing and borders
* Inline heading and badge presentation

### `news.html`

The news page recreates a content-focused article layout using semantic document regions.

It includes:

* A centered article container
* Publisher and publication information
* Comment and share buttons
* Main article content
* Images with descriptive captions
* Repeated article sections with headings
* Related and popular news link groups
* Semantic `header`, `article`, `section`, and `footer` elements

The page uses reusable classes to separate the article structure from its visual presentation.

### `styles/news.css`

The news stylesheet defines:

* A centered container with a maximum width
* Header typography and metadata alignment
* Reusable outlined button styles
* Image panels with captions
* Section spacing and dividers
* Paragraph typography and indentation
* Footer link groups
* Link states using `:visited` and `:hover`
* Direct-child selectors for targeted styling

## Development Notes

This repository is updated incrementally as new pages, styles, and interactions are implemented.

Documentation is kept aligned with the actual codebase, including:

* Added files
* Implemented layouts and behavior
* Styling changes
* Structural improvements

## Commit Convention

Commit messages generally follow this format:

```bash
type: short description
```

| Type       | Description                                 |
| ---------- | ------------------------------------------- |
| `feat`     | Add a new page, feature, or interaction     |
| `fix`      | Fix a bug or incorrect behavior             |
| `docs`     | Update documentation                        |
| `style`    | Update visual styling or formatting         |
| `refactor` | Improve structure without changing behavior |
| `chore`    | Update project setup or miscellaneous files |

## License

This repository is for personal practice and development.
