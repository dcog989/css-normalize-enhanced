# CSS Normalize Enhanced

This CSS file provides a modern "normalize" stylesheet for current web browsers (Chrome, Firefox, Safari, Edge, and their recent versions). It establishes a consistent styling baseline, leveraging improved browser defaults and modern web development best practices.

## Philosophy

This normalize is based on these principles:

* **Modern Browsers:** Targets up-to-date browsers, avoiding extensive resets for outdated ones.
* **Minimal Reset:** Focuses on smoothing inconsistencies and providing sensible defaults, rather than aggressive resets.
* **Embrace Modern Defaults:** Retains reasonable browser defaults, enhancing and standardizing rather than stripping everything away.
* **Accessibility Focused:** Prioritizes accessibility with rules for text readability (`line-height`), user-friendly focus indicators (`:focus-visible`), improved underline rendering (`text-decoration-skip-ink: auto`), and better word wrapping (`overflow-wrap: break-word`).
* **`box-sizing: border-box`:** Uses `box-sizing: border-box` for predictable layout management.
* **System Font Stack:** Employs a system font stack (`system-ui, ...`) for performance and a native look.
* **Font Smoothing:** Includes `-webkit-font-smoothing` and `-moz-osx-font-smoothing` for enhanced text rendering.
* **Modern Form Styling:** Resets form elements (`appearance: none`, etc.) for consistent and modern UI patterns.
* **Clear Code:** Organized into logical sections with comments for readability and maintainability.

## CSS Structure

The CSS is organized into these sections:

1. **Document:** Base styles for `html` and `body` (`box-sizing`, `line-height`, scroll behavior, font stack, font smoothing).
2. **Typography:** Styles for headings, paragraphs, text elements, and quotes.
3. **Embedded Content:** Styles for `img`, `figure`, and `figcaption`.
4. **Forms:** Resets and styles for form elements.
5. **Interactive:** Styles for interactive elements (`details`, `summary`, `:focus-visible`).
6. **Accessibility:** Rules for text wrapping and underline rendering.
7. **Lists:** Resets list styles (`ul`, `ol`, `li`).
8. **Tables:** Basic table styling.
9. **SVG and Canvas:** Styles for `canvas`.
10. **Interactive: Cursors:** Sets `cursor: pointer` on interactive elements.
11. **Selection:** Default text selection colors.

## Usage

1. **Download/Copy:** Download [`normalize-enhanced.css`](https://github.com/dcog989/css-normalize-enhanced/blob/main/normalize-enhanced.css) or copy the code.
2. **Include in HTML:** Link `normalize-enhanced.css` as the **first** stylesheet in your `<head>`, *before* custom stylesheets.

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Your Document</title>
  <link rel="stylesheet" href="/css/normalize-enhanced.css"> 
  <link rel="stylesheet" href="/css/style.css"> 
</head>
<body>[content goes here]</body>
</html>
```

## Customization

Customize typography, colors, focus styles, margins, padding, and form element styling in your own stylesheets. Direct modification of `normalize-enhanced.css` is not recommended.


## Credits

This normalize is inspired by and incorporates best practices from:

- normalize.css (https://necolas.github.io/normalize.css/)
- sanitize.css (https://github.com/csstools/sanitize.css)
- reboot.css (https://github.com/twbs/bootstrap/blob/main/scss/_reboot.scss)

It also draws from the broader concept of CSS normalization and modern CSS best practices (`box-sizing: border-box`, system font stacks, `:focus-visible`, accessibility).

This normalize is a contemporary interpretation of normalization for modern browsers.

---

**Disclaimer:** Test your websites across target browsers. CSS normalization is a starting point; further project-specific styling is always required.
