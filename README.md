# Personal Budget & Expense Tracker — Week 2

A responsive, static budget tracker built with HTML and CSS for the Week 2 assignment. It demonstrates semantic HTML tables, a structured expense form, multimedia embedding, a collapsible help section, and advanced CSS selectors.

## Project files

- **`index.html`** — The page structure and content:
  - Header and budget tracker introduction with a logo image.
  - Expense form with labelled fields and a category dropdown (Food, Transport, Rent, Entertainment, Other).
  - Expense table with a `thead`, `tbody`, and five sample records.
  - Collapsible “How to use this tracker” instructions using `details` and `summary`.
  - YouTube video embedded using an `iframe`.
- **`style.css`** — The visual design:
  - Colours, spacing, panels, form controls, table borders, and responsive layout.
  - Alternating table row backgrounds and a hover effect.
  - Focus styles for inputs, a pointer cursor for the button, and styling for category labels.
  - Advanced selectors including descendant selectors, `:nth-child(even)`, `:hover`, `:focus`, and `:not([type="submit"])`.

## How to run

1. Download or clone this repository.
2. Open `index.html` in a modern web browser.
3. Keep `style.css` in the same folder so the page styling loads correctly.
4. An internet connection is needed to load the remote logo and embedded YouTube video.

## Important note

This is a **static HTML/CSS project**. The **Add Expense** button is intentionally `type="button"` and does not save or add records yet. JavaScript functionality will be introduced in a later week. The rows currently shown are sample data.

## Technologies

- HTML5
- CSS3
- Responsive web design
