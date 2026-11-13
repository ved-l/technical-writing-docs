\# LaTeX Documentation



\## 1. Basic Commands \& Document Structure

```latex

\\documentclass\[12pt, a4paper]{article}

\\usepackage\[utf8]{inputenc}



\\begin{document}

\\section{Introduction}

\\subsection{Text Formatting}

\\textbf{Bold}, \\textit{Italic}, and \\underline{Underlined} text.



\\begin{itemize}

&#x20; \\item Bullet point one

&#x20; \\item Bullet point two

\\end{itemize}



\\begin{table}\[h]

\\centering

\\begin{tabular}{|l|c|r|}

\\hline

\\textbf{Tool} \& \\textbf{Category} \& \\textbf{Format} \\\\ \\hline

LaTeX \& Typesetting \& PDF \\\\ \\hline

Doxygen \& API Docs \& HTML/PDF \\\\ \\hline

\\end{tabular}

\\caption{Comparison of Tools}

\\end{table}



\\end{document}

