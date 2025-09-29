## Document Structure in LaTeX
 This contains the basic structure of a LaTeX document and explains the commonly used document classes like `article`, `report` and `book`.
### What I Learned
- Start with `\documentclass{}` to define the type of document.
- Content goes between `\begin{document}` and `\end{document}`.
- Structure your document using: `\section{}`, `\subsection{}`, `\subsubsection{}`
- Comments in LaTeX begains with `%`

### Document Structure

```latex
\documentclass{article}     % Document class
\title{My LaTeX Document}   % Title
\author{Your Name}          % Author
\date{\today}               % Date (Today's date)
\begin{document}            % Start of content
\maketitle                  % Render title
\section{Introduction}      % Section heading
% This is a comment
\end{document}              % End document
```

### article Class

Used for short documents such as papers, articles, or assignments.

> [!NOTE] 
> - The `article` class does **not** support chapters, only sections.  
> - Supports: `\section`, `\subsection`, and `\subsubsection` for structuring.

Check out  [`article.txt`](02_document-structure\article.tex) for the format.

### report Class
 Designed for longer documents with multiple chapters such as technical reports, theses.

> [!NOTE] 
> - Includes chapters `\chapter{}` in addition to sections. 
> - Autometically starts chapters on a new page.

Check out  [`report.txt`](02_document-structure\report.tex) for the format.

### book Class

Used for writing full length books.

> [!NOTE] 
> - Includes front matter, chapters and back matter.
> - Supports double sided printing.

Check out  [`book.txt`](02_document-structure\book.tex) for the format.

## Resources

Here are some useful links I found while learning:

- [What are the available "documentclass" types and their uses?](https://tex.stackexchange.com/questions/782/what-are-the-available-documentclass-types-and-their-uses) 