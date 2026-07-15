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
* Building basic form layouts with labels, inputs, select boxes, and fieldsets
* Applying external CSS styles to HTML documents
* Styling typography, links, table headers, and images
* Understanding how HTML structure and CSS presentation work together
* Building multi-column layouts with `inline-block`
* Applying reusable class-based styles
* Controlling spacing, borders, and image dimensions

The scope will be updated as the project grows.

## Project Status

This project is in an early development stage.

Current work:

* Repository initialized
* Initial HTML pages added
* Basic text, list, table, image, link, and form elements implemented
* External CSS introduced
* Travel page styling added
* Gallery layout implemented with reusable HTML and CSS classes

## Pages

| File          | Description                                                                                                                                                    |
| ------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `intro.html`  | A simple self-introduction page built with headings, lists, paragraphs, line breaks, and inline text formatting tags                                           |
| `travel.html` | A travel plan page built with an HTML table, merged rows and columns, images, external links, and external CSS styling                                         |
| `signup.html` | A basic signup form page built with form elements, fieldsets, labels, text inputs, password inputs, number inputs, radio buttons, a checkbox, and a select box |
| `gallery.html` | A responsive gallery page arranged in a three-column layout with a header and status badge |

## Styles

| File                | Description                                                      |
| ------------------- | ---------------------------------------------------------------- |
| `styles/travel.css` | Styles the travel page heading, table headers, links, and images |
| `styles/gallery.css` | Defines the gallery grid, image sizing, spacing, header layout, and badge styling |

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

The page now separates content structure from presentation by moving visual rules into `styles/travel.css`.

### `styles/travel.css`

The stylesheet introduces the first visual layer of the project.

It currently defines:

* Heading size, weight, color, and line height
* Table header alignment, size, weight, and color
* Link color, decoration, and emphasis
* Consistent image width with automatic height adjustment

### `signup.html`

The signup page introduces a basic form structure for collecting account and profile information.

It includes:

* Fieldsets and legends
* Labels connected to form controls
* Text, password, and number inputs
* Select options
* Radio buttons and checkbox controls
* Form submission input

### `gallery.html`

The gallery page presents a collection of images in a simple three-column layout.

It includes:

- Semantic page header
- Gallery rows and cells
- Reusable class-based layout structure
- Image alternative text
- External stylesheet integration
- A small status badge beside the page title

### `styles/gallery.css`

The gallery stylesheet introduces layout and spacing techniques using native CSS.

It currently defines:

- A basic CSS reset
- Three-column cells using `inline-block`
- Percentage-based widths and margins
- Responsive image sizing
- Centered gallery rows
- Header spacing and bottom border
- Inline heading and badge presentation

## Development Notes

This repository is updated incrementally as new pages, styles, and interactions are implemented.

Documentation is kept aligned with the actual codebase, including:

* Added files
* Implemented behavior
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
