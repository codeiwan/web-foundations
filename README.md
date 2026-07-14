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
* Understanding how basic HTML elements are rendered in the browser
* Preparing a foundation for styling and interaction in later updates

The scope will be updated as the project grows.

## Project Status

This project is in an early development stage.

Current work:

* Repository initialized
* README drafted
* Project direction defined
* Initial HTML pages added
* Basic text, list, table, image, link, and form elements practiced

## Pages

| File          | Description                                                                                                                                                    |
| ------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `intro.html`  | A simple self-introduction page built with basic HTML elements such as headings, lists, paragraphs, line breaks, and inline text formatting tags               |
| `travel.html` | A travel plan page built with an HTML table, merged rows and columns, images, and external links                                                               |
| `signup.html` | A basic signup form page built with form elements, fieldsets, labels, text inputs, password inputs, number inputs, radio buttons, a checkbox, and a select box |

## Implementation Notes

### `intro.html`

The first page introduces basic HTML document composition through a self-introduction layout.

It includes:

* Main heading
* Horizontal divider
* Section headings
* Unordered list
* Ordered list
* Paragraphs
* Line breaks
* Strong text emphasis
* Italic text emphasis

This page is intentionally simple and focuses on understanding how HTML elements structure content before applying CSS or JavaScript.

### `travel.html`

The travel page organizes a short Bali travel plan using a table-based layout.

It includes:

* Document metadata with character encoding and page title
* Main heading
* Horizontal divider
* Table headers
* Table rows and cells
* Merged rows with `rowspan`
* Merged columns with `colspan`
* Image elements for travel-related visuals
* External anchor links for destination references

This page focuses on representing structured schedule data with HTML while combining text, images, and hyperlinks in a single document.

### `signup.html`

The signup page introduces a basic form structure for collecting account and profile information.

It includes:

* Document metadata with character encoding, page title, and keyword metadata
* Form element with request method
* Fieldsets for grouping related form controls
* Legends for form section titles
* Labels connected to input fields
* Text and password inputs
* Number inputs with minimum and maximum values
* Select box with month options
* Radio buttons for gender selection
* Checkbox for agreement confirmation
* Submit input for form submission

This page focuses on understanding how HTML form controls are structured and grouped before adding visual styling or JavaScript validation.

## Development Notes

This repository will be updated incrementally as new pages, components, and interactions are implemented.

Each update will aim to keep the documentation aligned with the actual codebase, including:

* What was added
* What changed
* Why the change was made
* How the project structure evolved

## Commit Convention

Commit messages will generally follow this format:

```bash
type: short description
```

Common types:

| Type       | Description                                 |
| ---------- | ------------------------------------------- |
| `feat`     | Add a new page, feature, or interaction     |
| `fix`      | Fix a bug or incorrect behavior             |
| `docs`     | Update documentation                        |
| `style`    | Update visual styling or formatting         |
| `refactor` | Improve structure without changing behavior |
| `chore`    | Update project setup or miscellaneous files |

Example:

```bash
docs: initialize project README
```

## License

This repository is for personal practice and development.
