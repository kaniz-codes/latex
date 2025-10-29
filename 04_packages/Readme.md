# Latex Packeges 
Some useful LaTeX packages and document settings I've explored on the way learning.

### clean document class
```latex
\documentclass[a4paper,10pt]{article}
```
- sets up the basic structure of the document.
- `a4paper` means the paper is standard `A4 size`.
- `10pt` sets the font size to `10 points`.

### Manage margines
```latex
\usepackage[margin=1in]{geometry}
```
- here `margin=1in` it sets 1-inch margins all around.
- `geometry` Controls the page layout, including margins, paper size and page orientation.
- keeps content balanced on the page.

### Customizing list
```latex
\usepackage{enumitem}
```
- I can remove indntation, customize spacing between items or make the lists more compact.

### Clickable links
```latex
\usepackage{hyperref}
```
- automatically creats internal links for refarences and table of contents

### section and subsection headings customeization
```latex
\usepackage{titlesec}
```
- I could change font size, color, spacing and style of heading.

### Page margins
```latex
\usepackage[margin=1in]{geometry}
```
### multiple columns
``latex
\usepackage{multicol}
```

### paragraph formating
```latex
\usepackage{parskip}
```

### colors
```latex
\usepackage{xcolor}
```

### graphics
```latex
\usepackage{graphicx}
```

### Control float placement
```latex
\usepackage{float}
```
