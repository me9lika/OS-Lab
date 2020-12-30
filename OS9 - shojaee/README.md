LaTeX is a high-quality typesetting system; it includes features designed for the production of 
technical and scientific documentation. LaTeX is the de facto standard for the communication and 
publication of scientific documents.

steps :
1) go to https://www.overleaf.com and create new project
2) for title -> \title
3) for text section -> \section{Text}  then write your text
4) for image section -> \section{Image} \includegraphics[scale=imageSize]{uploaded image name}   
5) for table section ->
                \section{Table} 
                        \begin{tabular}{|c|c|c|}
                        \hline
                            a & b & c\\ 
                        \hline
                            e & f & g\\ 
                        \hline
                \end{tabular}
6) for formulas section -> \section{Formulas} $Formulas$
7) for code section -> \section{Codes}
\begin{lstlisting}[language=Python]
%code block
\end{lstlisting}
\end{document}
                                               

