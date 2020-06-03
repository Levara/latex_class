# Latex tutorial notes

## Korisni linkovi

- http://detexify.kirelabs.org/classify.html
- subfigure/subfig/subcaption razlika: https://tex.stackexchange.com/questions/122314/figures-what-is-the-difference-between-using-subfig-or-subfigure
    - prvo caption pa label za subcaption

- equation editor: 
  https://www.codecogs.com/latex/eqneditor.php
 
## Tutoriali 

- https://www.overleaf.com/learn/latex/Free_online_introduction_to_LaTeX_(part_1) 
- https://www.overleaf.com/learn/latex/Tutorials


## Intro vježbe

### 1. Overleaf

* Basic starter project - New project -> Example project*

- Osnovni paketi
- Osnovne naredbe: \documentclass, \title, \author, \chapter, \section,
  \subsection, \paragraf
- Text styles
- Naredbe (commands) vs. Okoline (environments)
- Referenciranje dijelova, slika, formula itd.
- Bibtex: file, naredbe (\bibliographystyle, \cite)

### 2. Prikaz naprednih funkcionalnosti

- tables
- subfigures, subcaptions
- figure\*, table\*, twocolumns
- algoritmi, ispis koda

### 3. New commands / renew commands
### 4. input/include




# Hints

- Latex primjene van radova:
    * latex formulas in matlab
    * gitlab/github pages
    * mathjaxx



- Placement of figures

  ```tex
  % ***************************************************************************************************
  % Configure constraints for placing floats on pages
  %    FIXES MOST PROBLEMS WITH PLACING FLOATS
  % ***************************************************************************************************

  \setcounter{topnumber}{2} %maximum number of floats at top of page - 	default:2
  \setcounter{bottomnumber}{2} %maximum number of floats at bottom of page - default:1
  \setcounter{totalnumber}{4} %maximum number of floats on a page - default:3
  \renewcommand{\topfraction}{0.8} %maximum fraction of page for floats at top default:0.7
  \renewcommand{\bottomfraction}{0.85} % 	maximum fraction of page for floats at bottom default:	0.3
  \renewcommand{\textfraction}{0.15} % 	minimum fraction of page for text default:0.2
  \renewcommand{\floatpagefraction}{0.7} %	minimum fraction of floatpage that should have floats 	default: 0.5 
  ```




