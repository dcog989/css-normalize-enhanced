# CSS Normalize Enhanced

A modern, opinionated, hybrid normalize/reset stylesheet for browsers 2020+. It provides a solid foundation with sensible defaults and more aggressive resets for a cleaner slate in modern web development.

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
*   **Lists (Enhanced Reset):** Removes default `ul`/`ol` list styles (`list-style: none`).
*   **Embedded Content:** Sensible defaults for `img`, `video`, `svg`, etc.
*   **Logical Properties:** Uses modern logical properties for margins and padding where appropriate.
*   **Customization:** Includes distinct `mark` and `::selection` styles.

## Why "Enhanced"?

This stylesheet goes beyond traditional normalization by:
1.  Providing more aggressive resets for elements like forms and lists.
2.  Making slightly more opinionated choices for a cleaner starting point (e.g., `font-size: inherit` for headings, `list-style: none`).
3.  Focusing exclusively on modern browsers, shedding legacy code.

## Usage

1.  **Download:** Get [`normalize-enhanced.css`](https://github.com/dcog989/css-normalize-enhanced/raw/main/normalize-enhanced.css).
2.  **Include:** Link it in the `<head>` of your HTML before your project's main stylesheets:
    ```html
    <link rel="stylesheet" href="path/to/normalize-enhanced.css">
    ```
    Alternatively, `@import` it at the top of your primary CSS/SCSS file:
    ```css
    @import url("path/to/normalize-enhanced.css");
    ```

## Contributing

Contributions, issues, and feature requests are welcome: [issues page](https://github.com/dcog989/css-normalize-enhanced/issues).

## License

This project is licensed under the MIT License.
