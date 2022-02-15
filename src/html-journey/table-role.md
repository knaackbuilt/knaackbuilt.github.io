---
layout: layout.njk
title: Is <table role="grid"> ok?
---

# {{title}}


Is table role="grid" a problem?

- <https://datatables.net/forums/discussion/68343/usage-of-the-role-attribtes>
- <https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/Grid_Role>
- <https://www.w3.org/TR/wai-aria-practices/examples/grid/dataGrids.html>
 
**Conclusion:** Yeah it's an issue if the table isn't a data grid. If you're presenting tabular data for general use, attributing table role grid is probably causing users of assistive tech to expect a function and interactivity that you aren't intending to put there.

