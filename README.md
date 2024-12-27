# CSS Specificity Bug

This repository demonstrates an uncommon bug related to CSS selector specificity. The `bug.css` file contains CSS code that unexpectedly overrides a more general style due to selector specificity. The `bugSolution.css` file provides the corrected CSS code to resolve the issue.

The bug stems from the fact that the selector `div p` has higher specificity than the selector `p`. This is because the `div p` selector is more specific; it only applies to `<p>` elements that are direct children of a `<div>` element.

The solution involves understanding CSS specificity and either adjusting selector order or making selectors equally specific or using the !important flag cautiously