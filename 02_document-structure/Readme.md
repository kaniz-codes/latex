## Document Structure in LaTeX

### What I Learned
- The basic structure of a LaTeX document starts with `\documentclass{}`, e.g., `article`, `report`, or `book`.
- The main content goes between `\begin{document}` and `\end{document}`.
- Sections are organized using `\section{}`, `\subsection{}`, and `\subsubsection{}`.
- Comments are added with `%`.

### Commands Practiced

```latex
\documentclass{article}     % Define document type
\title{My LaTeX Document}   % Document title
\author{Your Name}          % Author name
\date{\today}               % Date (today's date)
\begin{document}            % Start of content
\maketitle                 % Generate title section
\section{Introduction}      % Section heading
% This is a comment in LaTeX
\end{document}              % End of document
```
---

### 1. `article` Class

Used for short documents such as papers, articles, or assignments.

> **Note:**  
> - The `article` class does **not** support chapters.  
> - Use `\section`, `\subsection`, and `\subsubsection` for structuring.

You can check out the example file [`article.txt`](path/to/article.txt) for the format.

![Example image](path/to/image.png)
