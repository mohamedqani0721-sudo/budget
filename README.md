````markdown
# Budget Tracker

## Project Description

This project is a simple Budget Tracker created using HTML and CSS.

The Week 2 upgrade adds an expense table, an improved expense form, multimedia content, an interactive details section, and advanced CSS selectors.

## Features

### 1. Expense Table

The expense table uses:

- `<table>`
- `<thead>`
- `<tbody>`
- `<tr>`
- `<th>`
- `<td>`

It contains five sample expenses with their name, amount, category, and date.

The table also includes borders, cell padding, a colored header, alternating row colors, and a hover effect.

### 2. Add Expense Form

The form allows users to enter:

- Expense name
- Expense amount
- Expense category
- Expense date

The category is selected from a dropdown containing:

- Food
- Transport
- Rent
- Entertainment
- Other

The form also contains an "Add Expense" button with `type="button"`.

The button does not perform an action yet because JavaScript functionality will be added in a later week.

### 3. Multimedia

The page includes a small Budget Tracker logo using an `<img>` element.

It also contains an embedded YouTube video using an `<iframe>`.

### 4. Interactive Elements

A `<details>` and `<summary>` element provides a collapsible "How to use this tracker" section.

Table rows change appearance when the mouse moves over them, and the button displays a pointer cursor.

### 5. Advanced CSS Selectors

The stylesheet uses several advanced CSS selectors, including:

- Descendant selector:
  `.expenses-section td`

- Direct child selector:
  `.add-expense-section > h2`

- Position pseudo-class:
  `tr:nth-child(even)`

- Negation pseudo-class:
  `input:not([type="submit"])`

- Focus pseudo-class:
  `input:focus`

## Technologies Used

- HTML5
- CSS3

## Project Structure

```text
budget-tracker/
│
├── index.html
├── style.css
└── README.md
````

## How to Run

1. Download or clone the repository.
2. Open the project folder.
3. Open `index.html` in a web browser.

The Budget Tracker will then be displayed in the browser.

```
```
