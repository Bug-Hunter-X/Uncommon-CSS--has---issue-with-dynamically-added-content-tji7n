# Uncommon CSS :has() Issue with Dynamic Content

This repository demonstrates an uncommon issue related to the CSS `:has()` pseudo-class and how it interacts with dynamically added content or content loaded asynchronously.

The problem occurs when using `:has()` to target an element based on the presence of a child element, but that child element is added to the DOM after the initial page render.  In such cases, the `:has()` selector might not immediately recognize the change, resulting in the style not being applied.

The `bug.css` file contains the problematic CSS, and `bugSolution.css` presents a potential workaround.

See the detailed explanation in `bug.css` for more information.