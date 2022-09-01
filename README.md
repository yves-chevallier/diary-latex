# Cours HES-ÉTÉ LaTeX

## Programme

### Lundi

- [x] Historique
    - [x] Donald Knuth (TAOTP The Art Of Programming), langage TeX
    - [x] Leslie Lamport a inventé LaTeX
    - [x] Distribution : TeXlive, MikteX 
- [x] Installation 
    - [x] WSL 2 
    - [x] Ubuntu 
    - [x] TeXLive
    - [x] Visual Studio Code
- [x] Encodage de caractères
    - [x] ASCII sur 128 caractères en 1960
    - [x] Tables d'extensions en 1980 : ISO-8859-1
    - [x] Unicode UTF-8 

#### Installation de l'environnement

Installer :

  - WSL2
  - Ubuntu
  - VS Code
  - Windows Terminal

Configurer Windows Terminal pour ouvrir Ubuntu par défaut. Éventuellement cocher l'option de copier le texte à la sélection. 

Depuis Ubuntu installer TexLive:

```
sudo apt update
sudo apt install texlive-base texlive-latex-recommended texlive-latex-extra texlive-lang-french latexmk
```

### Mardi

- [x] Environement Math en LaTeX
  - [x] `$...$` Sur une ligne
  - [x] `$$...$$` Sur plusieurs lignes
  - [x] `\begin{equation}...\end{equation}` avec numérotation
- [x] Tables
  - [ ] `\begin{tabular}{lcr}` Pour des tableaux standards
  - [x] `\usepackage{tabularx}` Pour des tableaux pleine page
- [x] `\usepackage{graphicx}` Figures (insertion d'images)
- [x] Références avec `\begin{thebibliography}`
- [x] `\usepackage{lipsum}` Pour générer du texte aléatoire (`\lipsum[1..4]`)
- [x] `\usepackage{hyperref}` Pour avoir les liens sur un PDF
- [x] `\usepackage{listings}` Pour représenter du code source

### Mercredi

    - [x] Tables multicolumns/multirows (https://www.tablesgenerator.com/)
    - [x] En-tête / Bas de page
    - [x] Markdown / RST -> Pandoc (https://pandoc.org/try/)
    - [x] Bibliographie
      - [x] Installer `sudo apt install texlive-bibtex-extra biber`
    - [x] Lettrine
    - [x] Tabbing
    - [x] Pythontex
    - [x] GitHub
      - [x] Issues ?
      - [x] Pull Request ?
      - [x] Code insight, contributions des gens
    - [x] PythonTeX, exemple simple

### Jeudi

    - [x] Installation de Docker
    - [x] Tutoriel de Docker 
      - [x] `docker run -it ubuntu`
      - [x] `docker ps`
      - [x] `docker image ls`
    - [x] Clone du [template tb](http://github.com/heig-vd-tin/template-tb/)
      - [x] Ouvrir dans DevContainer
      - [x] Compiler le rapport
      - [x] Visualiser le rapport

### Vendredi

    - [x] Rédaction du rapport de fin de HES-ÉTÉ
    - [x] Rendu du rapport
    - [x] Les étudiants sont libres de venir ou non en classe
