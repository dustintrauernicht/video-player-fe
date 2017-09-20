Syntax
- Include one space before the opening brace of declaration blocks for legibility.
- Place closing braces of declaration blocks on a new line.

/* Good CSS */
.selector,
.selector-secondary,
.selector[type="text"] {
  padding: 15px;
  margin-bottom: 15px;
  background-color: rgba(0,0,0,.5);
  box-shadow: 0 1px 2px #ccc, inset 0 1px 0 #fff;
}

Related property declarations should be grouped together following the order:
1. Positioning
2. Box model
3. Typographic
4. Visual

Class names
- Keep classes lowercase and use dashes (not underscores or camelCase). Dashes serve as natural breaks in related class (e.g., .btn and .btn-danger).

Organization
- Organize sections of code by component.
- Develop a consistent commenting hierarchy.
- Use consistent white space to your advantage when separating sections of code for scanning larger documents.
- When using multiple CSS files, break them down by component instead of page. Pages can be rearranged and components moved.

Normalize reset
- Must be loaded before styles

Media query placement
- Must be loaded last



