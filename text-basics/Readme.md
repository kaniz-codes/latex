# Learn Latex with Kaniz
This document is a personal LaTeX guideline and cheatsheet for beginners. It collects useful LaTeX commands and structures I commonly used

## Table of Contents
- [Useful Packages to Include](#useful-packages-to-include)
- [New Paragraphs](#new-paragraphs)
- [New Line (Line Break)](#new-line-line-break)
- [Comments](#comments)
- [Text Formatting](#text-formatting)
- [Tables](#tables)
- [Add Image](#add-image)
- [Custom Alignment](#custom-alignment)
- [Create a Border Box](#create-a-border-box)
- [List](#list)
- [Mathematical Expressions](#mathematical-expressions)

## Useful Packages to Include 
```latex
\usepackage{graphicx}   % For image insertion
\usepackage{tcolorbox}  % For boxed content
\usepackage{xcolor}     % For custom colors
\usepackage{listings}   % For code formatting (optional)
\usepackage{caption}    % For custom captions
\usepackage{hyperref}   % Allows reference of figures, tables, etc. using labels

```
## New Paragraphs
To start a new paragraph, leave a `blank line` between two blocks of text.
```latex
This is the first paragraph.

This is the second paragraph.
```
## New Line (Line Break)
To add a line break without starting a new paragraph
```latex
This is the first line.\\
This is the second line.
```
or
```latex
This is the first line. \newline
This is the second line.
```
## Comments
Add comments inside LaTeX documents using `%`
```latex
% This is a comment and will not appear in the output
```
or
```latex
This is the first line. \newline
This is the second line.
```
## Text formatting
**Bold Text**
```latex
\textbf{I'm Kaniz}
```
**Italic Text**
```latex
\textit{I'm Kaniz}
```
**Underlined Text**
```latex
\underline{I'm Kaniz}
```
### Combined Formatting
```latex
\textbf{\textit{Bold and Italic}}
\underline{\textbf{Important}}
```

## Tables
Basic table example
```latex
\begin{tabular}{|c|c|c|}
\hline
Name & Age & City \\
\hline
Kaniz & 58 & Dhaka \\
Fatema & 30 & New York \\
\hline
\end{tabular}

```

## Add Image
With Caption and Label
```latex
\begin{figure}[h]
    \centering
    \includegraphics[width=0.5\textwidth]{your-image.png}
    \caption{Screenshot of the terminal}
    \label{fig:kaniz1}
\end{figure}
```
or
Full Width (No Caption)

```latex
\begin{center}
    \includegraphics[width=1\textwidth]{2.0.5.png}
\end{center}
```
## Custom Alignment

**Center Alignment**

```latex
\begin{center}
Your content goes here...
\end{center}
```

## Create a Border Box
Use `tcolorbox` to create colored boxes with custom styles:

```latex
\begin{tcolorbox}[colframe=blue, colback=white, sharp corners, width=10cm, height=3cm, halign=center, valign=center, fonttitle=\bfseries\Large, boxrule=0.8mm, arc=8mm]
    \textcolor{blue}{\textbf{\Huge Lab Report}}
\end{tcolorbox}
```
Make sure to include the `tcolorbox` and `xcolor` packages in your preamble:

```latex
\usepackage{tcolorbox}
\usepackage{xcolor}
```
## List

**Bullet List**

```latex
\begin{itemize}
    \item Create a new user named \textbf{developer1} using the \texttt{useradd} command.
    \item Set a password for the newly created user using the \texttt{passwd} command.
    \item Create a new group named \textbf{development} using the \texttt{groupadd} command.
    \item Add the user \textbf{developer1} to the \textbf{development} group using the \texttt{usermod} command.
    \item Check and display the group memberships of the user \textbf{developer1} using the \texttt{groups} command.
\end{itemize}
```
**Numbered List**

```latex
\begin{enumerate}
    \item First step
    \item Second step
    \item Third step
\end{enumerate}

```
## Mathematical Expressions
**Inline Math**
Use `$ ... $` to write math inside a paragraph.
```latex
The equation $E = mc^2$ is famous.
```

## Add line
**Basic Line**
```latex
\noindent\rule{\linewidth}{0.4pt}
```
**Alternative (Custom Width)**
```latex
\noindent\rule{0.8\linewidth}{1pt}  % 80% width and 1pt thickness
```
## Add Hyperlink
**Add Link in text with custom color**

```latex
\documentclass{article}
\usepackage{xcolor}
\usepackage{hyperref}
```

```latex
\href{https://kaniz111.com}{\textcolor{blue}{Kaniz Fatema}}
```
***Define a custom color***
```latex
% Define a custom color
\definecolor{customblue}{HTML}{1A73E8}  % Replace with any hex code

\begin{document}

Visit \href{https://kaniz111.com}{\textcolor{customblue}{Kaniz Fatema}} for more information.

\end{document}
```

## Resources

- [Learn LaTeX in 30 minutes](https://www.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes)
- [Youtube playlist](https://www.youtube.com/playlist?list=PLaxOs-8sLebvrPbJ62bZknwI89cwe1L4a)
- [LaTeX Templates](https://www.latextemplates.com/)
