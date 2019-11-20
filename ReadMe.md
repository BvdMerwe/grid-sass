# n-column Grid Sass

This is a css grid implementation that was built to work on most browsers including ones without css-grid or css-flex capabilities.

## Initialisation

Change the following paramenters and compile to get a grid up to 12 columns

1. $max_cols: 8; number between 1 and 12

---
2. $gutter: 1.5%; percentage value to keep responsive

---
3. $col_width: (100 / $max_cols); some equal fraction of max_cols

---
4. $margin: 100% / $max_cols; some percentage value

---
