# LaTeX cheatsheet
Random LaTeX stuff that I always forget.

## Quotations
\`\`This is a sentence''

## Units
[International System of Units](https://en.wikipedia.org/wiki/International_System_of_Units)
* Number and unit: `\SI{100}{\mega\bit\per\second}`
* Unit only (outside math mode): `\si{\mega\bit\per\second}`
* Unit only (inside math mode): `100\,\si{\mega\bit\per\second}`

## Subscripts and superscripts
* Inside math mode:
    - Subscript: `variable_n` or `variable_{multiple subscript chars}`
    - Superscript: `variable^n` or `variable^{multiple superscript chars}`
* Outside math mode: `\textsubscript{n}` or `\textsuperscript{th}`

## Insert image
``` latex
\begin{figure}[H]
    \centering
    \includegraphics[scale=1]{resources/filename.png}
    \caption{This is a caption}
\end{figure}
```
