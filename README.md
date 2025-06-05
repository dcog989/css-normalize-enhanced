# CSS Normalize Enhanced

A modern, opinionated, hybrid normalize / reset stylesheet for modern browsers (2020+).

## Key Features

*   **Modern Focus:** Targets browsers released 2020 and later.
*   **Box Sizing:** Applies `box-sizing: border-box` intuitively.
*   **Smooth Scrolling:** Enables `scroll-behavior: smooth` by default.
*   **Typography:**
    *   Resets heading font sizes (`font-size: inherit`).
    *   Consistent `font-family` for `body` and `code`/`pre`.
    *   Improved `abbr[title]` and `text-decoration-skip-ink`.
*   **Forms (Enhanced Reset):**
    *   Applies `appearance: none` to form elements for a consistent base, requiring custom styling for elements like checkboxes and radios.
    *   Normalizes button appearance and Firefox focus behavior.
*   **Embedded Content:** Sensible defaults for `img`, `video`, `svg`, etc.
*   **Logical Properties:** Uses modern logical properties for margins and padding where appropriate.
*   **Customization:** Includes distinct `mark` and `::selection` styles.

## Usage

1.  **Download:** Get [`normalize-enhanced.css`](https://github.com/dcog989/css-normalize-enhanced/raw/main/normalize-enhanced.css).
2.  **Include:** Link it in the `<head>` of your HTML before your project's main stylesheets:
    ```html
    <link rel="stylesheet" href="path/to/normalize-enhanced.css">
    ```

## Contributing

Contributions, issues, and feature requests are welcome: [issues page](https://github.com/dcog989/css-normalize-enhanced/issues).

## License

This project is licensed under the MIT License.
