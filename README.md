# HacktoberFest Lome 2023 PDF data Extraction

Ce repository a été créé pour documenter le codelab sur l'extraction de données tabulaires à partir de fichiers PDF dans le cadre de Hacktoberfest. Dans ce guide, nous vous montrerons comment exploiter la puissance de l'extraction de données tabulaires à partir de fichiers PDF en utilisant des outils tels que Camelot, pdfplumber et tabula-py.

## Pourquoi l'extraction de données tabulaires à partir de fichiers PDF est-elle importante ?

Les fichiers PDF sont couramment utilisés pour stocker des informations structurées sous forme de tableaux. Cependant, extraire ces données de manière manuelle peut être fastidieux et chronophage. L'extraction de données tabulaires à partir de fichiers PDF vous permet d'automatiser ce processus et d'obtenir rapidement des données structurées et exploitables.

## Comment s'y prendre ?

### Étape 1: Installation des outils nécessaires

Bien qu'ils existe une plétore de librairies python à l'instar de :

- Camelot (qui est dédié aux tableaux)
- tabula-py (pareil)
- pdfplumber (plus généraliste)

Nous avons choisi d'utiliser pdfplumber et Jupyter Notebook pour le processus d'extraction de données.

### Étape 2: Préparation du fichier PDF

Assurez-vous d'avoir le fichier PDF que vous souhaitez traiter à portée de main. Vous pouvez trouver le fichier PDF dans le repository. Vous pouvez également le télécharger et l'utiliser directement sur Google Colab en le plaçant dans votre Google Drive.

* [Fichier Jupyter Notebook](PDF_Plumber_Inseed_Data_Extraction.ipynb)
* [Le fichier PDF](INSEED_September_2023-6.pdf)

## Conclusion

L'extraction de données tabulaires à partir de fichiers PDF est une technique puissante qui peut vous faire gagner du temps et vous permettre d'obtenir rapidement des données structurées et exploitables. En utilisant des outils tels que Camelot, pdfplumber et tabula-py, vous pouvez automatiser ce processus et faciliter votre travail d'analyse de données.

## Pour aller plus loin

- [Automatiser le web scraping avec Github Actions](https://youtu.be/5CynXnR2UJ0)
- [Extracting Accounting Data from PDFs (Part 1)](http://www.python4cpas.com/2018/12/extracting-accounting-data-from-pdfs.html)
- [Parse PDF Files While Retaining Structure with Tabula-py | Pythonic Excursions](https://aegis4048.github.io/parse-pdf-files-while-retaining-structure-with-tabula-py)