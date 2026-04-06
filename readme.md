**Disclaimer:** This LaTeX template is provided "as is" without warranty of any kind, either express or implied. It is an independent, unofficial creation and is not affiliated with, authorized, maintained, sponsored, or endorsed by the University of Iowa or the University of Iowa Department of Chemistry. Users are solely responsible for ensuring that their final document complies with all current formatting and submission guidelines required by the graduate program.

## Cover Page
- Do not edit the files in the style folder. 
- In the main.tex replace the document title, student name, date, advisor's name, and the name of the remaining GAC members.

## Word Count
-

## Figures
- Figures should be placed in the figures folder and inserted using \includegraphics (e.g., \includegraphics[alt={Alternative text for the image},width=0.75\linewidth]{figures/Figure1.jpg}) .
- Figures should be high resolution (600 dpi). Do not snapshot images. 
- Figures should include a unique label (e.g., \label{fig:1}) between the \begin{figure} and \end{figure}. 
- All figures should be placed where it appears in the document or the next page with the [ht] in the \begin{figures} (e.g., \begin{figures}[ht] ).


## Tables
Tables should include a unique label (e.g., \label{tab:1}) between the \begin{table} and \end{table}. 
All tables should be placed where it appears in the document or the next page with the [ht] in the \begin{table} (e.g., \begin{table}[ht] ).

## Table Captions




  
## References
- Add your references in BibTex format to the bibliography.bib.
- The Latex command \autocite{} instead of \cite{} needs to be used to ensure the proper ACS citation format (numeric superscript) over square brackets.
- When citing websites to ensure the website title and the website URL are separated by a comma, a comma has to be manually added at the end of the website name.
- Avoid using journal name abreviations (e.g., "Angewandte Chemie International Edition" instead of "Angew. Chem. Int. Ed.")
- Check that all chemical formulas in the article's titles are correctly formated (e.g., subscripts and superscripts).
  
## Accessibility
- The resulting PDF may lack the structural tags required for full compatibility with screen readers and other assistive technologies. For example, the final PDF file is untagged. Currently there is not a good solution to create tagged PDFs from Latex but the current template implements the ideas presented in a recent Overleaf article ( https://docs.overleaf.com/writing-and-editing/creating-accessible-pdfs). 