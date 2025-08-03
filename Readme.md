## Learn Latex with Kaniz
# Election System
This project
## Add Image

```
\begin{figure}[h]
    \centering
    \includegraphics[width=0.5\textwidth]{your-image.png}
    \caption{Screenshot of the terminal}
    \label{fig:kaniz1}
\end{figure}

```

```
\begin{center}
    \includegraphics[width=1\textwidth]{2.0.5.png}
\end{center}
```

### Custom Alignment

**Center Alignment**

```
\begin{center}
.
.
\end{center} % ← Ends centering here

```

#### border

```
% Create a blue border with rounded corners and centered "Lab Report"
\begin{tcolorbox}[colframe=blue, colback=white, sharp corners, width=10cm, height=3cm, halign=center, valign=center, fonttitle=\bfseries\Large, boxrule=0.8mm, arc=8mm]
    \textcolor{blue}{\textbf{\Huge Lab Report}}
\end{tcolorbox}
```

### List

```
\begin{itemize}
    \item Create a new user named \textbf{developer1} using the \texttt{useradd} command.
    \item Set a password for the newly created user using the \texttt{passwd} command.
    \item Create a new group named \textbf{development} using the \texttt{groupadd} command.
    \item Add the user \textbf{developer1} to the \textbf{development} group using the \texttt{usermod} command.
    \item Check and display the group memberships of the user \textbf{developer1} using the \texttt{groups} command.
\end{itemize}
```

**Parent class/super/base class:** The class whose properties are derived.
