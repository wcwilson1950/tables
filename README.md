# HTML Table Editor Exploration

This project explores various strategies to make HTML tables usable as interactive editors. The goal is to develop a flexible, configurable HTML table editor that supports editing, validation, error reporting, and customization via JavaScript or declarative markup.

## Project Purpose

The project is a sandbox for experimenting with different approaches to table editing in HTML and JavaScript. It starts with a simple implementation and will evolve to support more advanced features, including:

- Editing multiple columns
- Using `contenteditable`
- Supporting different data types and validation rules
- Cell-level error reporting
- Configurable editor behavior via JavaScript or table markup (e.g., column headers, row attributes)

## Current Version

The first version, [`single_v1.html`](single_v1.html), demonstrates:

- Making a single column in the table editable (Quantity)
- In-place editing using an `<input>` field
- Keyboard navigation (Enter/Tab/Escape)
- Logging cell updates

## Planned Features

Future versions will explore:

- Editing multiple columns
- Using `contenteditable` for direct cell editing
- Supporting various input types (numbers, dates, selects, etc.)
- Per-cell and per-column validation
- Error display and reporting for invalid input
- Declarative configuration using column header attributes or row data
- Full JavaScript API for dynamic configuration

## Getting Started

Open [`single_v1.html`](single_v1.html) in your browser to try the current implementation.

## Contributing

Feel free to experiment, add new HTML/JS files, and document new strategies for table editing. Suggestions and pull requests are welcome.

## License

MIT License