+++
title = "LaTeX"
page_template = "page.html"
+++

## Advice on LaTeX

- Use modern implementations of LaTeX to take advantage of Unicode and other useful features.
    - Use [LuaLaTeX](https://www.luatex.org/) instead of LaTeX or pdfLaTeX
    - Use [BibLaTeX](https://www.overleaf.com/learn/latex/Bibliography_management_with_biblatex) instead of BibTex
- Use correct [typefaces](https://physics.nist.gov/cuu/pdf/typefaces.pdf). Particularly, *italics* should be used for variables but not for descriptive terms. [More...](https://en.wikibooks.org/wiki/LaTeX/Mathematics#Adding_text_to_equations)
    - Wrong: $t_{max}$
    - Right: $t_\text{max}$
- Do not manually add separators in large numbers. `\usepackage{siunitx}`. Then, wrap large numbers in `\num{}`.
    - Bad: 12,345
    - Good: `\num{12345}`
- Do not manually type reference names, such as Table, Figure, Theorem. Instead, `\usepackage{hyperref}`, and then `\autoref{fig:xxx}`, `\autoref{tbl:xxx}`, `\autoref{thm:xxx}`
    - Not recommended: In Figure~\ref{fig:overview}
    - Good: In \autoref{fig:overview}