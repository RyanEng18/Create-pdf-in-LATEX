# Create-pdf-in-LATEX

\documentclass{article}
\usepackage{graphicx} % Required for inserting images

\title{ATIVIDADE REALIZADA ATRAVÉS DO LATEX}
\author{Ryan Paulino}
\date{19/03/2025}

\begin{document}

\maketitle


\section{Lógica Proposicional e Aplicações}

1. (Rosen 1.1.1) Quais das sentenças abaixo são proposições? Qual o valor de verdade das que são proposições?
\begin{itemize}
    \item (a) Curitiba é a capital do Paraná.
    \item (b) Joinville é a capital de Santa Catarina.
    \item (c) 2 + 3 = 5
    \item (d) 5 + 7 = 10
    \item (e) x + 2 = 11
    \item (f) Responda a esta questão.
\end{itemize}

\begin{table}[h]
    \centering
    \begin{tabular}{c|c}
    \hline
    Sentenças & Valor de Verdade \\
       A   & Verdadeira \\
       B   & Falsa \\
       C   & Verdadeira \\
       D  & Falsa \\
    \hline
       
    \end{tabular}
\end{table}

    \vspace{1cm}
    \textbf{2. (Rosen 1.1.5) Considere que p e q são as proposições: “Nadar na praia em Copacabana é permitido” e “Foram descobertos tubarões perto da praia”, respectivamente. Expresse cada uma dessas proposições compostas como uma sentença em português.}

    \begin{itemize}
       \item(a) $\neg  q$ \quad \= "Nadar na praia em copacabana não é permitido" "Não foram descobertos tubarões perto da praia" \\
       
       \item(b) $p \wedge q$ \> "Nadar na praia em Copacabana é permitido e Foram descobertos tubarões perto da praia" \\
       
       \item(c) $\neg p \vee q$ \> "Nadar na praia em copacabana não é permitido ou Foram descobertos tubarões perto da praia \\
       
       \item(d) $p \rightarrow \neg q$ \> "Se nadar na praia em Copacabana é permitido, então Não foi descoberto tubarões perto da praia" \\
       
       \item(e) $p \leftrightarrow \neg q$ \> "Nadar na praia em Copacabana é permitido somente se não for descoberto tubarões perto da praia" \\
       
       \item(f) $\neg p \wedge (p \vee \neg q)$ \> "Nadar na praia em Copacabana não é permitido, e ou Nadar na praia em Copacabana é permitido, ou não foram descobertos tubarões perto da praia." \\
    \end{itemize}
    
\vspace{1cm}

\textbf{3. (Rosen 1.1.7) Considere que p e q são as proposições:}

   \begin{itemize}
    \item \( p \): "Está abaixo de zero."
    \item \( q \): "Está nevando."
\end{itemize}

Escreva estas proposições usando \( p \), \( q \) e conectivos lógicos.

\begin{itemize}
        \item(a) Está abaixo de zero e nevando. \> $p \wedge q$ \\
    \item(b) Está abaixo de zero, mas não está nevando. \>
    
    \item(c) Não está abaixo de zero e não está nevando.
    
    \item(d) Está nevando ou abaixo de zero (ou os dois).
    
    \item(e) Se está abaixo de zero, está também nevando.
    
    \item(f) Está ou nevando ou abaixo de zero, mas não está nevando se estiver abaixo de zero.
    
    \item(g) Para que esteja nevando, é necessário e suficiente que esteja abaixo de zero.
    
\end{itemize}

 
    
    
\end{document}
